predicting vulnerable software components
==================================================

这篇文章的主要贡献在于给出了一个预测在大型软件中，某个模块漏洞出现概率的方法。可以通过该方法预测更容易出现漏洞的模块，从而有针对性的进行审计。
该文章使用的主要方法为从https://bugzilla.mozilla.org中获取了firefox历年来的漏洞，使用机器学习的方法对其进行聚类。

个人觉得这个思路是可以借鉴的，如果白盒符号执行的时候路径过多，可以使用该方式进行启发式的路径选择，从而更高效的测试。
