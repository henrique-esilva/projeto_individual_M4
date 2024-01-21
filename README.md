# projeto_individual_M4
Repositório destinado à entrega do projeto individual do módulo 4 do curso Análise de Dados

## Proposta
O objetivo deste projeto é criar um relatório para uma empresa fictícia de desenvolvimento de softwares. Deve ser feita uma análise exploratória a partir de [registros](#registros) referentes a certo projeto de desenvolvimento ao longo de uma semana.

### Registros
| dia | horas trabalhadas | tarefas concluídas | bugs corrigidos |
| --- | --- | --- | --- |
| segunda-feira | 6 | 3 | 5 |
| terça-feira | 7 | 2 | 4 |
| quarta-feira | 8 | 1 | 6 |
| quinta-feira | 6 | 4 | 4 |
| sexta-feira | 7 | 3 | 5 |
| sábado | 5 | 2 | 3 |
| domingo | 4 | 1 | 2 |

## Entrega
O [notebook](https://colab.research.google.com/drive/1Ug9BDQu3-vrAeYFlavV7t0gvr2hptusy?usp=sharing) usado durante a elaboração do projeto e também seu objeto de entrega

## Desenvolvimento
Foi criada uma tabela (DataFrame Pandas) chamada `registros_da_semana` a partir dos registros apresentados na proposta.  
* adicionada linha 'total' com a soma dos valores de todas as colunas
* adicionada coluna 'prdutividade' feita a partir da razão das colunas 'bugs corrigidos' e 'horas trabalhadas'
* adicionadas linhas 'média' e 'mediana', feitas a partir apenas dos dados da tabela original

Ao final, foi criada uma função que compara determinada coluna das sete priemeiras linhas da tabela com a média deste mesmo campo  
A função então foi usada para encontrar os dias em que cada métrica (horas trabalhadas, tarefas concluídas, bugs corrigidos, produtividade) superou a sua média, o que é exposto em um relatório por extenso, no qual também consta o maior e menor valor de cada métrica.

## Ferramentas
Para este projeto foram usadas algumas tecnologias, dentre as quais vale destacar:
* Google Colaboratory - ferramenta da Google, bem como outras tecnologias Google
* Python - linguagem de programação
* Pandas e NumPy - módulos Python
* Markdown - linguagem simplificada de marcação
