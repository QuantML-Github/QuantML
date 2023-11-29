# 机器学习&量化学术交流


本项目目前包括：

**QUANT-RESOURCES**:

- Awesome-quant [awesome-quant](https://github.com/wilsonfreitas/awesome-quant)

- Awesome-quant(Chinese) [awesome-quant](https://github.com/thuquant/awesome-quant)<br>

- Time-Series Works and Conferences [Time-Series-Works-Conferences
](https://github.com/lixus7/Time-Series-Works-Conferences)


**PAPERS AND MODELS**:

- DDG-DA: Data Distribution Generation for Predictable Concept Drift Adaptation [DDG-DA](https://arxiv.org/abs/2201.04038)

- Awesome Time Series Forecasting/Prediction Papers [TSFpaper](https://github.com/ddz16/TSFpaper/tree/a4e106b9579d49ba55370e70935e9acff467120a) 

- A Survey on Time-Series Pre-Trained Models [time-series-ptms](https://github.com/qianlima-lab/time-series-ptms)

- Pytorch Transformer based Time Series Models [transformer-ts](https://github.com/kashif/pytorch-transformer-ts)


<BR>

## **MODEL ZOO**

#### 截面模型

| Model Name                               | Paper   | Type | IC          | ICIR        | Annualized Return | Information Ratio | Max Drawdown | Alpha | Information Ratio(alpha) | Max Drawdown(alpha) | PLOT | 
|------------------------------------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
|Linear|[LINK]()|LINEAR|0.07515|4.30512|6.84%|0.45324|27.61%|10.36%|0.83945|12.79%|[PLOT](./PLOT/backtest_result_linear_single_d5_top400_drop400_alpha360.html)|
|CATBOOST| [LINK](https://proceedings.neurips.cc/paper/2018/file/14491b756b3a51daac41c24863285549-Paper.pdf)| TREE |  0.07899| 4.86365| 9.65% | 0.57736 | 30.68% | 13.46% | 1.62153 | 12.30% | [PLOT](./PLOT/backtest_result_catboost_single_d5_top400_drop400_alpha360.html)
|LGBM|[LINK]()|TREE|0.07497|4.44188|7.20%|0.45381|32.82%|11.03%|0.89911|12.91%|[PLOT](./PLOT/backtest_result_lightgbm_single_d5_top400_drop400_alpha360.html)
|DoubleEnsemble|[LINK](https://arxiv.org/pdf/2010.01265.pdf)|TREE| 0.07555|4.30537|6.13%|0.39556|34.53%|10.00%|0.78544|14.05%|[PLOT](./PLOT/backtest_result_doubleensemble_single_d5_top400_drop400_alpha360.html)|
|MLP|[LINK]()|MLP|0.07093|6.27798|13.44%|0.83009|20.08%|17.02%|1.44013|10.59%|[PLOT](./PLOT/backtest_result_mlp_single_d5_top400_drop400_alpha360.html)|


#### 时序模型

| Model Name                               | Paper   | Type | IC          | ICIR        | Annualized Return | Information Ratio | Max Drawdown | Alpha | Information Ratio(alpha) | Max Drawdown(alpha) | PLOT | 
|------------------------------------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
|LSTM|[LINK](https://direct.mit.edu/neco/article-abstract/9/8/1735/6109/Long-Short-Term-Memory?redirectedFrom=fulltext)|RNN|0.09134|7.47619|17.93%|0.96085|29.32%|22.01%|1.68747|12.28%|[PLOT](./PLOT/backtest_result_lstm_single_d5_top400_drop400_alpha360.html)|
|GRU|[LINK](https://arxiv.org/pdf/1412.3555.pdf)|RNN| 0.07913| 7.82825| 22.11% | 1.21610 | 24.93% | 26.20% | 2.16575 | 9.15% |  [PLOT](./PLOT/backtest_result_gru_single_d5_top400_drop400_alpha360.html)|
|DA-RNN|[LINK](https://www.ijcai.org/Proceedings/2017/0366.pdf)|RNN+Attn| **0.09456** | **8.28988**| **22.17%** | 1.19277 | 26.22% | 26.31% | 2.10914 | 9.20% | [PLOT](./PLOT/backtest_result_alstm_single_d5_top400_drop400_alpha360.html) | 
|TRA|[LINK]()|RNN|0.08400|8.10454|13.79%|0.81530|26.77%|17.71%|1.62311|[PLOT](./PLOT/backtest_result_tra_single_d5_top400_drop400_alpha360.html) | 
|TCN|[LINK](https://arxiv.org/abs/1803.01271)|CNN|0.09114|7.57064|16.95%|0.94854|26.44%|20.92%|1.70229|10.09%|[PLOT](./PLOT/backtest_result_tcn_single_d5_top400_drop400_alpha360.html)|
|Transformer|[LINK](https://arxiv.org/abs/1706.03762)|Attn|0.08938|6.94548|18.27%|1.02255|25.98%|22.05%|1.66291|11.42%|[PLOT](./PLOT/backtest_result_transformer_single_d5_top400_drop400_alpha360.html)|
|Localformer|[LINK](https://arxiv.org/abs/2202.10240)|Attn|0.09066|6.47978|17.55%|1.01227|25.91%|21.24%|1.62241|10.72%|[PLOT](./PLOT/backtest_result_localformer_single_d5_top400_drop400_alpha360.html)|
|Informer|[LINK](https://arxiv.org/abs/2012.07436)|Attn+CNN|0.00702|1.69430|3.93%|0.30673|28.63%|7.59%|0.75850|13.03%|[PLOT](./PLOT/backtest_result_informer_single_d5_top400_drop400_alpha360.html)|
|Autoformer|[LINK](https://arxiv.org/abs/2106.13008)|Attn| 0.04984|4.36314|9.99%|0.65911|24.41%|13.34%|1.12588|11.77%|[PLOT](./PLOT/backtest_result_autoformer_single_d5_top400_drop400_alpha360.html)|
|PatchTST|[LINK](https://arxiv.org/abs/2211.14730)|Attn|0.00500|0.82580|3.96%|0.30926|27.72%|7.58%|0.75946|11.17%|[PLOT](./PLOT/backtest_result_patchtst_single_d5_top400_drop400_alpha360.html)|
|iTransformer|[LINK](https://arxiv.org/abs/2310.06625)|Attn| 0.04645|2.80729|9.20%|0.63440|21.66%|12.38%|1.03928|12.12%|[PLOT](./PLOT/backtest_result_itransformer_single_d5_top400_drop400_alpha360.html)
|DLinear|[LINK](https://arxiv.org/abs/2205.13504)|MLP|0.06246|3.47573|13.90%|0.92929|20.35%|17.11%|1.39859|9.80%|[PLOT](./PLOT/backtest_result_dlinear_single_d5_top400_drop400_alpha360.html)|
|TiDE|[LINK](https://arxiv.org/abs/2304.08424)|MLP|-0.0447|-2.39685|-16.25%|-0.60535|43.30%|-12.94%|-0.74022|34.66%|[PLOT](./PLOT/backtest_result_tide_single_d5_top400_drop400_alpha360.html)|
|TiDGE|[LINK](https://arxiv.org/abs/2304.08424)|RNN+MLP|0.04695|3.83880|2.13%|0.21000|33.73%|5.86%|0.54744|12.41%|[PLOT](./PLOT/backtest_result_tidge_single_d5_top400_drop400_alpha360.html)


#### **Meta Learning**

| Model Name                               | Paper   | Type | IC          | ICIR        | Annualized Return | Information Ratio | Max Drawdown | Alpha | Information Ratio(alpha) | Max Drawdown(alpha) | PLOT | 
|------------------------------------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
|DDG-DA(Linear)|[LINK](https://arxiv.org/abs/2201.04038)|LINEAR|0.12582|6.75107|10.94%|0.68766|27.82%|14.33%|1.11679|12.62%|[PLOT](./PLOT/backtest_result_ddgda-linear_single_d5_top400_drop400_alpha360.html)|

<BR>

## **FACTOR ZOO**

#### 量价因子

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
