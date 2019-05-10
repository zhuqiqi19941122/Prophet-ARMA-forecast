# Prophet-ARMA-forecast
Enterprise income and expense  forcasting ( FinTech Elite training camp 2019) 

企业App中海量的客户收支数据，无时无刻不在反映客户交易行为。通过企业收支数据预测，可以合理规划企业现金收支情况，协调现金收支与经营、投资、融资活动的关系，保持现金收支平衡和偿债能力，同时也为现金控制提供依据。本赛题将提供企业App中对公客户7个月的历史收支数据和客户7个月的理财产品持仓数据。希望参赛选手通过分析建模，根据客户最近7个月的收支数据，解决如下问题：

（1） 预测客户未来一个月（2018年11月）的每天的财务支出总和；

（2） 预测客户未来一个月（2018年11月）的每天的财务收入总和；

训练数据(X_rev_exp_4_10.csv )为633个客户在2018年4月到10月的收支数据,可用于模型建立的训练及测试。注意：有些客户在某天可能无任何收支数据，认为当天该客户的收支均为0。

理财数据(X_finance.csv)也是影响企业收支的一部分因素，可在建模的过程中考虑，但是并非这633个客户在该时间段内都持有理财产品。


function： 对企业未来一个月的收支进行预测

usage： python Prophet_model

requirments: python3,pandas,numpy,matplotlib,datetime,fbprophet

tip: 数据不能下载
