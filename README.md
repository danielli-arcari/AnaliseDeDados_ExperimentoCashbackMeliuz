# 📊 Experimento de Cashback – Méliuz | Análise Exploratória de Dados

## Autora

**Danielli Meilene Coutinho Arçari**
Analista de Dados Júnior (em formação)

---

## Contexto do Problema

Programas de cashback são utilizados para incentivar compras e aumentar o volume de vendas. No entanto, aumentos pontuais de incentivo nem sempre geram crescimento sustentável. Este projeto analisa um conjunto de dados inspirado em um experimento de cashback, com foco em entender **como o volume de vendas se comporta ao longo do tempo**.

A análise foi construída com abordagem prática, orientada a negócio e alinhada ao nível de um **Analista de Dados Júnior**, priorizando clareza, leitura executiva e conclusões acionáveis.

---

## Fonte dos Dados

Os dados utilizados neste projeto foram obtidos a partir da seguinte atividade prática:

* Fonte: [https://app.networkme.com.br/main/activities/146659c7-2e0f-41ff-b1a3-58e76f9e1ee6/play](https://app.networkme.com.br/main/activities/146659c7-2e0f-41ff-b1a3-58e76f9e1ee6/play)

O dataset contém registros de vendas associadas a um programa de cashback, organizados por período mensal.

---

## Perguntas de Negócio

A análise concentrou-se **exclusivamente** nas seguintes questões:

1. Quantas vendas ocorreram em cada mês?
2. Existe variação no volume de vendas entre os meses analisados?

---

## Estrutura do Dataset

| Coluna | Descrição                        |
| ------ | -------------------------------- |
| data   | Data da venda                    |
| mes    | Mês de referência                |
| vendas | Quantidade de vendas registradas |

---

## Metodologia

A análise seguiu um fluxo simples e reproduzível:

1. Importação dos dados com Pandas
2. Verificação de consistência e tipos de dados
3. Agrupamento das vendas por mês
4. Criação de tabela resumo mensal
5. Visualização gráfica do volume de vendas
6. Interpretação orientada a negócio

---

## Resultados da Análise

### Quantidade de Vendas por Mês

Tabela consolidada a partir do dataset:

| Mês       | Vendas |
| --------- | ------ |
| Janeiro   | 120    |
| Fevereiro | 98     |
| Março     | 145    |
| Abril     | 110    |
| Maio      | 160    |
| Junho     | 102    |

📌 **Leitura Analítica:** O número de vendas varia entre os meses, indicando comportamento não uniforme ao longo do período analisado.

---

### Variação do Volume de Vendas

A análise comparativa entre os meses mostrou que:

* Há meses com volume significativamente maior de vendas.
* Também existem meses com retração relevante.
* Não foi observada estabilidade no volume de vendas ao longo do tempo.

📌 **Leitura Analítica:** O volume de vendas apresenta oscilações mensais claras, sugerindo influência de fatores pontuais, como campanhas promocionais.

---

## Conclusões

A partir da análise exploratória, conclui-se que:

* O volume de vendas varia significativamente entre os meses.
* Os aumentos observados são pontuais e não se sustentam nos períodos seguintes.
* O comportamento é compatível com ações promocionais de curto prazo.

---

## Implicações de Negócio

Do ponto de vista estratégico:

* Cashback pode ser eficaz para **estimular vendas no curto prazo**.
* Não deve ser tratado como única estratégia de crescimento.
* Para resultados sustentáveis, é necessário combinar incentivo financeiro com retenção e recorrência.

---

## Tecnologias Utilizadas

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Considerações Finais

Este projeto demonstra domínio de conceitos fundamentais de **análise exploratória de dados**, leitura de métricas e tradução de números em decisões de negócio. O escopo, a metodologia e a comunicação dos resultados estão alinhados ao perfil de **Analista de Dados Júnior**, com foco em clareza, consistência e aplicabilidade prática.
