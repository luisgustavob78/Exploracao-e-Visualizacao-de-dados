# Exploracao-e-Visualizacao-de-dados

# Objetivo

O objetivo da análise realizada foi extrair insights a partir dos dados que pudessem responder perguntas sobre os recursos humanos de uma empresa, tais como:

* Descobrir a influência dos gerentes sobre a performance dos funcionários
* Avaliar as carcteísticas comuns de quem é demitido
* Avaliar o perfil de diversidade da empresa
* analisar a equidade de pagamentos dentro da empresa

## Gerentes e performances

Avaliando graficamente as performances por gerente, foi possível observar que não existe uma diferenças significativas entre eles em relação à performance de seus subordinados, já que, na média, o desempenho é relativamente equilibrado.

![](https://github.com/luisgustavob78/Exploracao-e-Visualizacao-de-dados/blob/master/gif_managersScores.gif)

Isso não se repete quando o parâmetro de análise é a satisfação do funcionário e alguns gerentes apresentam diferenças consideráveis entre si nesse aspecto.

![](https://github.com/luisgustavob78/Exploracao-e-Visualizacao-de-dados/blob/master/image_managerSatisfaction.gif)

## Demissões

Para analisar quais fatores levam um funcionário à demissão, usou-se um cálculo de Ganho de Informação de cada variável sobre a variável alvo (demitido ou não). 

![](https://github.com/luisgustavob78/Exploracao-e-Visualizacao-de-dados/blob/master/gif_terminations.gif)

Nesse caso, um insight interessante surgiu: apesar de não influenciar significativamente na performance, os gerentes possuem uma relevância considerável em quem vai ser demitido. Junto a eles, a fonte pela qual a pessoa foi contratada são os maiores fatores de demissão.

## Diversidade

Para avaliar esse aspecto, foi preciso pensar sobre o que de fato significa 'diversidade', um problema de definição de problema comum em data science, que é saber exatamente o que a análise deve responder. Nesse caso, a diversidade foi considerada em termos de descendência, raça, gênero e idade. Analisando essas variáveis, ficou claro que algumas fontes de recrutamento apresentam resultados bastante ddiferentes entre si quando o assunto é diversidade.

![](https://github.com/luisgustavob78/Exploracao-e-Visualizacao-de-dados/blob/master/gif_diversity.gif)

# Base de Dados

A base de dados pode ser encontrada em: https://www.kaggle.com/rhuebner/human-resources-data-set
