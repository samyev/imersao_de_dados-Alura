<h1 align="center">Imersao de dados 3 - Alura</h1>

Aqui vamos analisar dados de uma tabela que trás informações sobre células que foram expostas a modificações genéticas através de experiẽncias com drogas(remédios) e controle, quando precisamos isolar uma certa substância para podermos ter uma melhor precisão dos dados coletados na pesquisa. Na tabela a baixo podemos analiasr o tipo de tratamento que cada célula obteve, o tempo que levou para que a droga fizesse o efeito esperado sobre a célula, a quantidade de dosagem aplicada na célula, a droga utilizada e a porcetagem de RNAs afetados em cada gene de DNA alterado pelos experimentos.

## Dados Experimentos

~~~python
import pandas as pd

url_dados = 'https://github.com/alura-cursos/imersaodados3/blob/main/dados/dados_experimentos.zip?raw=true'

dados = pd.read_csv(url_dados, compression = 'zip')
print(dados)
~~~
