# study
This is my study journey in this time 

一个简单的学习日记

# 18.6.2020 本周知识内容总结
本周对SqlServer的一个用法学习 openquery 数据库远端服务器链接开启对远程服务器的增删改查业务。对此函数的具体的使用并未深入，仅仅是测试了远端的使用标准值函数。本次查询到此函数的本意是找一个可以远程调用数据库函数的方法，但由于openquery的方法只找到 select * from openquery、insert···等这种形式的方法，所以想要直接调用方法返回一个值并在另一个select语句中实现的想法到此就终结了。

形式上选择了另一个方法，直接远程将需要的值都插入临时表，在用临时表里的内容去连接在判断值得正确性

# 1.21.2021
间隔时间有点久，但还是想起来回来更新了，总结一下6月份以来的一段经验。
1. 对于存储过程调用时，如果涉及到在存储过程内的增删改操作，要在段首加 set nocount on 语句。因为在java调用存储过程时，会返回第一个查到的句子，而这句话的意义为将增删改或其他操作产生的提示语句 如“影响了xx行”这样的句子剔除。避免了由于配置操作产生的这类句子直接返回而没有返回正确的值导致调用查到的内容没有的情况。
2.

对于2思考了很久，好像更多的是业务知识，技术上的知识这半年没有长进，简单说一下*风险监控，风险控制，监控报表，数据同步，kettle导入，风控指标，*等等的开发，更多的接触了许多交易上的业务知识。但技术上的长进确实很小这方面的不足有待提高。


