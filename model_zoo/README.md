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
|Linear|
|CATBOOST| [LINK](https://proceedings.neurips.cc/paper/2018/file/14491b756b3a51daac41c24863285549-Paper.pdf)| TREE |  0.07899| 4.86365| 9.65% | 0.57736 | 30.68% | 13.46% | 1.62153 | 12.30% | [LINK](./PLOT/backtest_result_catboost_single_d5_top400_drop400_alpha360.html)
|XGBOOST|
|LGBM|
|DoubleEnsemble|


#### 时序模型

| Model Name                               | Paper   | Type | IC          | ICIR        | Annualized Return | Information Ratio | Max Drawdown | Alpha | Information Ratio(alpha) | Max Drawdown(alpha) | PLOT | 
|------------------------------------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
|LSTM|
|GRU|
|DA-RNN|[LINK](https://www.ijcai.org/Proceedings/2017/0366.pdf)| LSTM+TRANS| 0.06753 | 5.59841| 19.21% | 1.11488 | 26.43% | 23.12% | 2.71108 | 7.87% | [LINK](./PLOT/backtest_result_alstm_single_d5_top400_drop400_alpha360.html) | 
|Transformer|
|Informer|
|Autoformer|
|LTSF-Linear|
|TIDE|
|PatchTST|




## SELF-SUPERVISED PRE-TRAINED MODEL

TBD




