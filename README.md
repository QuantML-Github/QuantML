# 机器学习&量化学术交流

欢迎加入机器学习&量化学术交流群

本项目目前包括：

**QUANT-RESOURCES**:

- Awesome-quant [awesome-quant](https://github.com/wilsonfreitas/awesome-quant)

- Awesome-quant(Chinese) [awesome-quant](https://github.com/thuquant/awesome-quant)<br>


**PAPERS AND MODELS**:

- Awesome Time Series Forecasting/Prediction Papers [TSFpaper](https://github.com/ddz16/TSFpaper/tree/a4e106b9579d49ba55370e70935e9acff467120a) 

- A Survey on Time-Series Pre-Trained Models [time-series-ptms](https://github.com/qianlima-lab/time-series-ptms)

- Pytorch Transformer based Time Series Models [transformer-ts](https://github.com/kashif/pytorch-transformer-ts)

**MODEL ZOO**

#### 截面模型

| Model Name                               | Paper   | Type | IC          | ICIR        | Annualized Return | Information Ratio | Max Drawdown | Alpha | Information Ratio(alpha) | Max Drawdown(alpha) | PLOT | 
|------------------------------------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
|Linear|[LINK]|LINEAR|0.07515|4.30512|6.84%|0.45324|27.61%|10.36%|0.83945|12.79%|[PLOT](./PLOT/backtest_result_linear_single_d5_top400_drop400_alpha360.html)|
|CATBOOST| [LINK](https://proceedings.neurips.cc/paper/2018/file/14491b756b3a51daac41c24863285549-Paper.pdf)| TREE |  0.07899| 4.86365| 9.65% | 0.57736 | 30.68% | 13.46% | 1.62153 | 12.30% | [PLOT](./PLOT/backtest_result_catboost_single_d5_top400_drop400_alpha360.html)
|LGBM|[LINK]|TREE|0.07497|4.44188|7.20%|0.45381|32.82%|11.03%|0.89911|12.91%|[PLOT](./PLOT/backtest_result_lightgbm_single_d5_top400_drop400_alpha360.html)
|DoubleEnsemble|[LINK](https://arxiv.org/pdf/2010.01265.pdf)|TREE| 0.07555|4.30537|6.13%|0.39556|34.53%|10.00%|0.78544|14.05%|[PLOT](./PLOT/backtest_result_doubleensemble_single_d5_top400_drop400_alpha360.html)|
|MLP|[LINK]|MLP|0.07093|6.27798|13.44%|0.83009|20.08%|17.02%|1.44013|10.59|[PLOT](./PLOT/backtest_result_mlp_single_d5_top400_drop400_alpha360.html)|


#### 时序模型

| Model Name                               | Paper   | Type | IC          | ICIR        | Annualized Return | Information Ratio | Max Drawdown | Alpha | Information Ratio(alpha) | Max Drawdown(alpha) | PLOT | 
|------------------------------------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
|LSTM|[LINK]|RNN|0.09774|8.10504|24.60%|1.26978|26.16%|28.84%|2.15556|10.41%|[PLOT](./PLOT/backtest_result_lstm_single_d5_top400_drop400_alpha360.html)|
|GRU|[LINK]|RNN| 0.07913| 7.82825| 14.64% | 0.84717 | 27.88% | 18.64% | 1.68949 | 9.35% |  [PLOT](./PLOT/backtest_result_gru_single_d5_top400_drop400_alpha360.html)|
|DA-RNN|[LINK](https://www.ijcai.org/Proceedings/2017/0366.pdf)| LSTM+TRANS| 0.06753 | 5.59841| 19.21% | 1.11488 | 26.43% | 23.12% | 2.71108 | 7.87% | [PLOT](./PLOT/backtest_result_alstm_single_d5_top400_drop400_alpha360.html) | 
|Transformer|
|Informer|
|Autoformer|
|LTSF-Linear|
|TIDE|
|PatchTST|

**FACTOR ZOO**

## 量价因子

| FACTOR   | 表达式   | IC均值        | ICIR        | IC>0占比 | \|IC\|>0.03占比 |多头组年化收益 | 多空年化收益 | 
|------------------------------------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
|Alpha0|


<br>
UPDATING...<br>
<br>
欢迎交流

<br>
<div align="left">
	<img src="wechat.jpg" width="25%">
</div>
