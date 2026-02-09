📊 Experimento de Cashback – Méliuz

📌 Visão Geral
Este projeto apresenta uma análise exploratória de dados de um experimento de cashback, focando em entender o comportamento do volume de vendas ao longo do tempo.
A análise foi desenvolvida com abordagem prática e orientada ao negócio, priorizando leitura executiva e conclusões acionáveis aplicáveis a estratégias de retenção e crescimento.

🎯 Objetivo do Projeto
Analisar como um programa de cashback influencia o volume de vendas ao longo de um período de 6 meses, respondendo a perguntas-chave sobre variabilidade e comportamento de vendas.

📊 Dataset
AspectoDescriçãoOrigemDados de experimento de cashback - MéliuzPeríodo6 meses de análise (Janeiro a Junho)Tamanho6 registros mensais de vendasFonteAtividade prática estruturada

📋 Estrutura dos Dados
dados: Dados brutos mensais
mes: Mês de referência (Janeiro a Junho)
vendas: Quantidade de vendas registradas no período

🔧 Metodologia
A análise seguiu um fluxo simples e reproduzível:

1️⃣ Importação de Dados
Carregamento dos dados com Pandas
Verificação inicial de dimensões e tipos

2️⃣ Verificação de Consistência
Análise de tipos de dados
Validação de integridade dos registros
Identificação de valores ausentes ou inconsistentes

3️⃣ Agrupamento por Período
Organização de vendas por mês
Consolidação de dados mensais

4️⃣ Criação de Tabela Resumida
Tabela consolidada com mês e volume de vendas
Estrutura clara para comparação temporal

5️⃣ Visualização Gráfica
Gráficos para identificar padrões e tendências
Representação visual do comportamento mensal

6️⃣ Interpretação e Conclusões
Análise orientada a decisões de negócio
Recomendações estratégicas baseadas em dados
📈 Resultados Principais

Quantidade de Vendas por Mês

MêsVendasJaneiro120Fevereiro98Março145Abril110Maio160Junho102

📌 Leitura Analítica: O número de vendas varia significativamente entre os meses, indicando um comportamento não uniforme ao longo do período analisado.
Análise de Variação

✅ Meses com volume elevado: Março (145), Maio (160)
✅ Meses com retração: Fevereiro (98), Junho (102)
✅ Padrão observado: Oscilações claras e não lineares

📌 Leitura Analítica: O volume de vendas apresenta oscilações mensais evidentes, sugerindo influência de fatores pontuais, como campanhas promocionais sazonais.

🎯 Conclusões:

Achados Principais

Variação Significativa:
-O volume de vendas oscilou entre 98 e 160 unidades
-Amplitude de variação = 62 vendas (63% do menor valor)

Picos e Vales Identificados:
-Picos: Maio (160) e Março (145)
-Quedas: Fevereiro (98) e Junho (102)

Comportamento Não Sustentável:
-Aumentos observados são pontuais
-Não se sustentam nos períodos seguintes
-Compatível com ações promocionais de curto prazo

Implicações Estratégicas
📌 Do ponto de vista de negócio:
- Cashback é eficaz para picos de curto prazo - Consegue estimular vendas em períodos específicos
- Não é estratégia única de crescimento - Necessita complementação com outras táticas
- Para sustentabilidade, combinar:
    -Incentivos financeiros (cashback)
    -Programas de retenção de clientes
    -Ações de recorrência e fidelização

💻 Tecnologias Utilizadas
Python 3
Pandas - Manipulação e organização de dados
Matplotlib - Visualizações gráficas
Jupyter Notebook - Ambiente de desenvolvimento

🚀 Como Reproduzir

Pré-requisitos:
pythonimport pandas as pd
import matplotlib.pyplot as plt

Passos:
Importe os dados com Pandas
Agrupe por mês (groupby)
Crie tabela resumida
Gere visualizações
Interprete os padrões

📁 Estrutura do Projeto
📦 experimento-cashback-meliuz/
├── 📓 cashback_analysis.ipynb    # Notebook principal
├── 📄 README.md                  # Este arquivo
└── 📊 dados_cashback.csv         # Dataset original

🎓 Competências Demonstradas

✅ Análise Exploratória (EDA): Investigação sistemática de padrões
✅ Manipulação de Dados: Organização e agregação com Pandas
✅ Visualização: Comunicação clara de insights
✅ Pensamento Estratégico: Tradução de dados em decisões de negócio
✅ Comunicação: Leitura executiva e recomendações acionáveis


📚 Contexto

Realizado em: 2026
Fonte: Atividade prática estruturada
Cargo Alvo: Analista de Dados Júnior
Autora: Danielli Meilene Coutinho Arçari

🔗 Links Relacionados

💼 LinkedIn
🌐 Portfólio Completo
📧 Email: axiadmc@gmail.com
💻 GitHub

💡 Próximos Passos Sugeridos
Para expandir esta análise:

📊 Análise de segmentação de clientes por valor de cashback
📈 Previsão de vendas futuras com base em padrões históricos
🎯 Teste A/B para diferentes percentuais de cashback
💰 Cálculo de ROI (retorno sobre investimento) da estratégia


Este projeto demonstra capacidade de análise exploratória, interpretação de dados e tradução em recomendações de negócio.
Desenvolvido com foco em clareza, consistência e aplicabilidade prática.
