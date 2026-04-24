📊 EXPERIMENTO DE CASHBACK - DESAFIO MELLIUZ

📌 VISÃO GERAL:
Este projeto apresenta uma análise exploratória de dados de um experimento de cashback, focando em entender o comportamento do volume de vendas ao longo do tempo. Fez parte de um desafio para o processo seletivo da Meliuz (que me agradou bastante e gerou um certificado de participação: https://drive.google.com/file/d/1oWOkTeHpsIo1kgvuVAsrtxh8Lvbgd9tz/view?usp=sharing)

A análise foi desenvolvida com abordagem prática e orientada ao negócio, priorizando leitura executiva e conclusões acionáveis aplicáveis a estratégias de retenção e crescimento.

🎯 OBJETIVO DO DESAFIO-PROJETO
Analisar como um programa de cashback influencia o volume de vendas ao longo de um período de 6 meses, respondendo a perguntas-chave sobre variabilidade e comportamento de vendas.

📊 DATASET
Confira no Colab: https://colab.research.google.com/drive/1slcR0ejixmAQNrfhnSUMZkvGlMUPDzGv?usp=sharing

📋 ESTRUTURA DOS DADOS
dados: Dados brutos mensais
mes: Mês de referência (Janeiro a Junho)
vendas: Quantidade de vendas registradas no período

🔧 METODOLOGIA
A análise seguiu um fluxo simples e reproduzível:

1️⃣ IMPORTAÇÃO DOS DADOS
Carregamento dos dados com Pandas
Verificação inicial de dimensões e tipos

2️⃣ VERIFICAÇÃO DE CONSISTÊNCIA DOS DADOS
Análise de tipos de dados
Validação de integridade dos registros
Identificação de valores ausentes ou inconsistentes

3️⃣ AGRUPAMENTO POR PERÍODO
Organização de vendas por mês
Consolidação de dados mensais

4️⃣ CRIAÇÃO DE TABELA RESUMIDA
Tabela consolidada com mês e volume de vendas
Estrutura clara para comparação temporal

5️⃣ VISUALIZAÇÃO GRÁFICA
Gráficos para identificar padrões e tendências
Representação visual do comportamento mensal

6️⃣CONCLUSÕES

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

💡 Próximos Passos Sugeridos
Para expandir esta análise:

📊 Análise de segmentação de clientes por valor de cashback
📈 Previsão de vendas futuras com base em padrões históricos
🎯 Teste A/B para diferentes percentuais de cashback
💰 Cálculo de ROI (retorno sobre investimento) da estratégia


Este projeto demonstra capacidade de análise exploratória, interpretação de dados e tradução em recomendações de negócio.
Desenvolvido com foco em clareza, consistência e aplicabilidade prática.
