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
O [notebook](https://colab.research.google.com/drive/16Hz1S5YFnRSj-HLsWG9CdYCInr4FwvVl?usp=sharing) usado durante a elaboração do projeto e também seu objeto de entrega

## Desenvolvimento
Foi criada uma tabela (DataFrame Pandas) chamada `registros_da_semana` a partir dos registros apresentados na proposta. As métricas (horas trabalhadas, tarefas concluídas e bugs corrigidos, além de uma métrica extra calculada: 'produtividade') foram usadas em outras duas tabelas:  
1. `totais` contendo o somatório de cada métrica em todos os dias da semana
2. `medias` contendo a relação entre o nome da métrica e a razão entre o valor em cada dia da semana em `registros_da_semana` e o número de dias da semana

Foi usada dict comprehension para criar estas duas tabelas

## Ferramentas
Para este projeto foram usadas algumas tecnologias, dentre as quais vale destacar:
* Google Colaboratory - ferramenta da Google
* Python - linguagem de programação
* Pandas - módulo do Python
