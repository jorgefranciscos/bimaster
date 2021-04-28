# Previsão de índices de frete marítimo usando SARIMA e LSTM

#### Alun(o/a): [Jorge Francisco de Jesus da Silva](https://github.com/jorgefranciscos).
#### Orientador(/a/es/as): [Jose Bermudez](https://github.com/).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- [Link para o código](https://github.com/jorgefranciscos/bimaster).

---

### Resumo

Não costuma ser uma tarefa fácil prever os ciclos marítimos por causa de sua irregularidade, que costuma ocorrer em função da oferta e demanda em períodos de recessão ou crescimento econômico acelerado (Kim, 2013). O Baltic Exchange, uma instituição com sede em Londres, fornece índices sobre o mercado marítimo para a negociação e liquidação de contratos físicos e de derivativos. Os índices, publicados diariamente, são usados como referência para tomada de decisão e a previsão assertiva desses índices pode trazer vantagens econômicas e competitivas. Estão divididos em quatro grupos principais em função do tamanho médio e outras características dos navios, totalizando 35 índices. 

Esta monografia tem por objetivo analisar a viabilidade da aplicação de modelos estatísticos e redes neurais para tentar prever esses índices.
A abordagem estatística usou um modelo Auto-regressivo Integrado de Média Móvel – Autoregressive Integrated Moving Average - sazional (SARIMA). Também foi empregado uma rede neural recorrente - Long-Short Term Memory (LSTM). Foram analisados 31 índices (de um total de 35 publicados) na janela de Janeiro de 2013 à Abril de 2021. A aplicação de modelos estatísticos e redes neurais para tentar prever índices de frete marítimo parece promissora. Os modelos LSTM alcançaram valores baixos de MAPE em todas as séries e as previsões ficaram muito próximas dos valores reais.


### Abstract

Usually it is not an easy task to predict maritime cycles because of their irregularity, which usually occurs due to supply and demand in periods of recession or accelerated economic growth (Kim, 2013). The Baltic Exchange, a London-based institution, provides indexes on the maritime market for the trading and settlement of physical and derivative contracts. The indices, published daily, are used as a reference for decision making and the assertive prediction of these indices can bring economic and competitive advantages. They are divided into four main groups ranging from the average size and other characteristics of the ships, totaling 35 indexes. 

This work aims to analyze the feasibility of applying statistical models and neural networks to try to predict these indices. The statistical approach used a autoregressive Integrated Moving Average model - Autoregressive Integrated Moving Average - seasonal (SARIMA). A recurrent neural network - Long-Short Term Memory (LSTM) was also used. 31 indexes (out of a total of 35 published) were analyzed in the window from January 2013 to April 2021. The use of statistical models and neural networks to try to predict sea freight rates seems promising. The LSTM models achieved low MAPE values in all series and the forecasts were very close to the actual values.

---

Matrícula: 191.671.036

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*