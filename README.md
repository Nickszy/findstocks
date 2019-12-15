# findstocks

量化交易是我一直想要研究的方向，这次正好借着课程论文的机会去实践一个比较简单的选股模型。

我认为较为完整的模型需要考虑**资产本身的价值和市场对其认同**两方面的因素。

这次主要通过**财务指标**和**技术指标**两个方面来进行建模。

如果以后有机会还应该将**另类数据**也考虑进来，同时还需要对财务和技术指标进行更严谨的定价。

```
data.ipynb          #  get date from resset
data_process.ipynb  #  normalize ,delete date
choose_stock.ipynb  #  find some stocks better and test them
```

## 版本

| Version | Description | Date       |
| :-----: | ----------: | ---------- |
|  0.0.1  |  用svm选股  | 12/15/2019 |
