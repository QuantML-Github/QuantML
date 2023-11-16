# MODEL ZOO

## SUPERVISED MODEL

### CONFIG:

- 框架: [QLIB](https://github.com/microsoft/qlib/tree/main)

- 因子: ALPHA360

- 股票池： 全A

- 频率： 5日频

- 训练集: 2016-2019

- 验证集: 2020

- 测试集: 2021-2023.2

### RESULT

参考QLIB BENCHMARK [结果](https://github.com/microsoft/qlib/tree/main/examples/benchmarks)


#### 截面模型

| Model Name                               | Paper   | Type | IC          | ICIR        | Annualized Return | Information Ratio | Max Drawdown | Alpha | Information Ratio(alpha) | Max Drawdown(alpha) | PLOT | 
|------------------------------------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
|Linear|[LINK]()|LINEAR|0.07515|4.30512|6.84%|0.45324|27.61%|10.36%|0.83945|12.79%|[PLOT](./PLOT/backtest_result_linear_single_d5_top400_drop400_alpha360.html)|
|CATBOOST| [LINK](https://proceedings.neurips.cc/paper/2018/file/14491b756b3a51daac41c24863285549-Paper.pdf)| TREE |  0.07899| 4.86365| 9.65% | 0.57736 | 30.68% | 13.46% | 1.62153 | 12.30% | [PLOT](./PLOT/backtest_result_catboost_single_d5_top400_drop400_alpha360.html)
|LGBM|[LINK]()|TREE|0.07497|4.44188|7.20%|0.45381|32.82%|11.03%|0.89911|12.91%|[PLOT](./PLOT/backtest_result_lightgbm_single_d5_top400_drop400_alpha360.html)
|DoubleEnsemble|[LINK](https://arxiv.org/pdf/2010.01265.pdf)|TREE| 0.07555|4.30537|6.13%|0.39556|34.53%|10.00%|0.78544|14.05%|[PLOT](./PLOT/backtest_result_doubleensemble_single_d5_top400_drop400_alpha360.html)|
|MLP|[LINK]()|MLP|0.07093|6.27798|13.44%|0.83009|20.08%|17.02%|1.44013|10.59|[PLOT](./PLOT/backtest_result_mlp_single_d5_top400_drop400_alpha360.html)|


#### 时序模型

| Model Name                               | Paper   | Type | IC          | ICIR        | Annualized Return | Information Ratio | Max Drawdown | Alpha | Information Ratio(alpha) | Max Drawdown(alpha) | PLOT | 
|------------------------------------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
|LSTM|[LINK]()|RNN|0.09774|8.10504|24.60%|1.26978|26.16%|28.84%|2.15556|10.41%|[PLOT](./PLOT/backtest_result_lstm_single_d5_top400_drop400_alpha360.html)|
|GRU|[LINK]()|RNN| 0.07913| 7.82825| 14.64% | 0.84717 | 27.88% | 18.64% | 1.68949 | 9.35% |  [PLOT](./PLOT/backtest_result_gru_single_d5_top400_drop400_alpha360.html)|
|DA-RNN|[LINK](https://www.ijcai.org/Proceedings/2017/0366.pdf)| LSTM+TRANS| 0.06753 | 5.59841| 19.21% | 1.11488 | 26.43% | 23.12% | 2.71108 | 7.87% | [PLOT](./PLOT/backtest_result_alstm_single_d5_top400_drop400_alpha360.html) | 
|TCN|[LINK]()|CNN|0.07505|4.75362|12.05%|0.76158|25.32%|15.48%|1.26948|12.11%|[PLOT](./PLOT/backtest_result_tcn_single_d5_top400_drop400_alpha360.html)|
|Transformer|
|Informer|
|Autoformer|
|LTSF-Linear|
|TIDE|
|PatchTST|




## SELF-SUPERVISED PRE-TRAINED MODEL

TBD




