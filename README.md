# AnaliseDeDados_ExperimentoCashbackMeliuz
📊 Análise Exploratória de Vendas – Experimento de Cashback Méliuz
Autora

Danielli Meilene Coutinho Arçari
Analista de Dados Júnior (em formação)

Visão Geral

Este projeto apresenta uma análise exploratória de dados (EDA) baseada em um experimento de cashback inspirado no contexto da Méliuz. O foco da análise é compreender o comportamento do volume de vendas ao longo do tempo, identificando variações mensais e padrões relevantes para a tomada de decisão de negócio.

A análise tem caráter descritivo, sem inferência estatística avançada, sendo adequada ao escopo de um projeto de Analista de Dados Júnior.

Fonte dos Dados

Os dados utilizados neste projeto foram obtidos a partir da seguinte atividade prática:

Fonte: https://app.networkme.com.br/main/activities/146659c7-2e0f-41ff-b1a3-58e76f9e1ee6/play

O dataset contém registros de vendas associadas a um programa de cashback, organizados por período.

Objetivo da Análise

Responder às seguintes perguntas de negócio:

Quantas vendas ocorreram em cada mês?

Existe variação no volume de vendas entre os meses analisados?

O volume de vendas se mantém após meses de maior atividade?

Estrutura do Dataset
Coluna	Descrição
data	Data da venda
mes	Mês de referência
vendas	Quantidade de vendas registradas no período
Metodologia

A análise seguiu os seguintes passos:

Carregamento do dataset utilizando Pandas

Inspeção inicial dos dados (head() e info())

Agrupamento das vendas por mês

Visualização gráfica do volume de vendas mensal

Interpretação dos resultados com foco em negócio

Análise Exploratória
Quantidade de Vendas por Mês

Tabela gerada a partir do agrupamento mensal das vendas:

Mês	Quantidade de Vendas
Janeiro	120
Fevereiro	98
Março	145
Abril	110
Maio	160
Junho	102

(valores conforme apresentados no dataset analisado)

📌 Insight: Observa-se variação clara no volume de vendas entre os meses analisados.

Análise do Comportamento ao Longo do Tempo

A visualização gráfica mostrou que:

Existem picos de vendas em determinados meses.

Após meses de maior atividade, ocorre redução no volume de vendas.

O crescimento não se mantém de forma contínua ao longo do período.

📌 Insight: O comportamento indica sazonalidade ou impacto de ações pontuais, como campanhas promocionais.

Conclusões

Com base na análise exploratória, conclui-se que:

O volume de vendas não é constante ao longo do tempo.

Há meses com maior concentração de vendas, seguidos por períodos de retração.

Os picos de vendas não se sustentam nos meses seguintes, sugerindo efeitos temporários.

Implicações de Negócio

Os resultados indicam que estratégias como cashback ou campanhas promocionais:

Podem gerar aumento pontual nas vendas.

Não garantem crescimento sustentado sem ações complementares.

Devem ser avaliadas em conjunto com estratégias de retenção e recorrência.

Tecnologias Utilizadas

Python

Pandas

Matplotlib

Jupyter Notebook

Observação Final

Este projeto demonstra a aplicação prática de análise exploratória de dados, organização de informações e interpretação de resultados, competências fundamentais para a atuação como Analista de Dados Júnior.
