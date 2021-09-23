# Previsão de índices de frete marítimo usando SARIMA e LSTM

#### Alun(o/a): [Jorge Francisco de Jesus da Silva](https://github.com/jorgefranciscos).
#### Orientador(/a/es/as): [Jose Bermudez](https://github.com/).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- [Link para o código](https://github.com/jorgefranciscos/bimaster).

---

### Resumo

A previsão dos ciclos marítimos é uma tarefa complexa devido a sua alta irregularidade, a qual  costuma ocorrer em função da oferta e demanda em períodos de recessão ou crescimento econômico acelerado (Kim, 2013). Neste sentido, o Baltic Exchange, uma instituição com sede em Londres, fornece índices sobre o mercado marítimo para a negociação e liquidação de contratos físicos e de derivativos. Os índices, publicados diariamente, são usados como referência para tomada de decisão, de modo que a previsão assertiva desses índices pode trazer vantagens econômicas e competitivas. Estes estão divididos em quatro grupos principais em função do tamanho médio e outras características dos navios, totalizando 35 índices.

Neste cenário, a presente monografia tem como objetivo analisar a viabilidade da aplicação de modelos estatísticos e redes neurais para prever os índices sobre o mercado marítimo. Para a abordagem estatística avaliou-se um modelo Auto-regressivo Integrado de Média Móvel – Autoregressive Integrated Moving Average - sazonal (SARIMA), e para a abordagem baseada em redes neurais avaliou-se uma rede neural recorrente - Long-Short Term Memory (LSTM). Foram analisados 31 índices (de um total de 35 publicados) na janela de Janeiro de 2013 à Abril de 2021. A aplicação de modelos estatísticos e redes neurais para tentar prever índices de frete marítimo obteve resultados promissores. Em particular, os modelos LSTM alcançaram valores baixos de MAPE (27,22118749 SARIMA e 2,751828261 LSTM em média) em todas as séries de modo que as previsões ficaram muito próximas dos valores reais.



### Abstract

Forecasting maritime cycles is a complex task due to its high irregularity, which usually occurs due to supply and demand in periods of recession or accelerated economic growth (Kim, 2013). In this regard, the Baltic Exchange, an institution based in London, provides indexes on the maritime market for the negotiation and settlement of employment contracts and derivatives. The indexes, published daily, are used as a reference for decision making, so that such an assertive forecast can bring competitive advantages. These are divided into four main groups according to the average size and other characteristics of the ships, totaling 35 indexes.

In this scenario, this monograph aims to analyze the feasibility of applying statistical models and neural networks to predict the indexes on the maritime market. For a statistical approach, a seasonal Autoregressive Integrated Moving Average - Autoregressive Integrated Moving Average - seasonal (SARIMA) model was evaluated, and for an approach based on neural networks, a recurrent neural network - Long-Short Term Memory (LSTM) was evaluated. 31 indexes (out of a total of 35 published) were evalueated in the window from January 2013 to April 2021. The application of statistical models and neural networks to try to predict sea freight indixes have promising results. In particular, the LSTM models achieved low MAPE (27,22118749 SARIMA e 2,751828261 LSTM average) values in all series making the predictions very close to the real values.

---

Matrícula: 191.671.036

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
