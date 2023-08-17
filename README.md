# Megaline: Smart ou Ultra

## Descrição do Projeto
A operadora de celular Megaline está insatisfeita com o fato de muitos de seus clientes estarem usando planos antigos. Eles querem desenvolver um modelo que possa analisar o comportamento do cliente e recomendar um dos planos mais recentes da Megaline: Smart ou Ultra.
Temos acesso a dados de comportamento dos assinantes que já mudaram para os novos planos (do projeto do curso de Análise de Dados Estatísticos). Para esta tarefa de classificação, precisei desenvolver um modelo que escolherá o plano certo. 
Para isso, desenvolvi um modelo com a maior acurácia possível. Neste projeto, o limite para acurácia é 0,75. 

## Instruções do projeto:
1.	Abri e examine o arquivo de dados. Caminho para o arquivo: /datasets/users_behavior_upd.csv Baixar o conjunto de dados
2.	Dividi os dados de origem em um conjunto de treinamento, um conjunto de validação e um conjunto de teste.
3.	Investiguei a qualidade de diferentes modelos alterando hiperparâmetros. Descrevi brevemente os resultados do estudo.
4.	Verifiquei a qualidade do modelo usando o conjunto de teste.

## Descrição dos dados
Cada observação no conjunto de dados contém informações comportamentais mensais sobre um usuário. As informações dadas são as seguintes:
-	сalls — número de chamadas
-	minutes — duração total da chamada em minutos
-	messages — número de mensagens de texto
-	mb_used — Tráfego de Internet usado em MB
-	is_ultra — plano para o mês atual (Ultra - 1, Smart - 0)
