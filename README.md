# 从零开始卷量化，示例代码
本仓库为公众号**FinHack炼金术**《从零开始卷量化》系列文章示例代码，该系列包含文章如下：

+ [系列文章](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzAxNDgwNTA3NA==&action=getalbum&album_id=1762624395866324994&scene=173&from_msgid=2649618270&from_itemidx=1&count=3&nolastread=1#wechat_redirect)

```shell
# 安装路径
conda create --name py310 python=3.10.13
# 激活环境
conda activate py310
pip install akshare  backtrader tushare

conda install -c conda-forge ta-lib
# 然后编译C代码

pip install ta-lib
pip install tushare
```

+ [《Windows系统下安装TA_Lib教程》](https://zhuanlan.zhihu.com/p/502358216)

### 从零开始卷量化系列(基础入门篇)：
- [x] 从零开始卷量化(1)-何为量化？
- [x] 从零开始卷量化(2)-第一个量化策略，年化35%？(CAPM，单因子模型)
- [x] 从零开始卷量化(3)-量化回测复盘 (常见回测指标解读)
- [x] 从零开始卷量化(4)-有效市场假说之内幕消息模型，15年15倍！(有效市场假说)
- [x] 从零开始卷量化(5)-多因子模型的尝试，年化51% (多因子模型)
- [x] 从零开始卷量化(6)-基于相对估值法的量化模型 (PE、PEG、PS、PB、PCF)
- [x] 从零开始卷量化(7)-基于绝对估值法的量化模型(DCF、DDM和RIM)
- [x] 从零开始卷量化(8)-基于技术指标的量化模型，模拟盘年化120%！
- [x] 从零开始卷量化(9)-基于短周期因子的打板策略，年化47%！
- [x] 从零开始卷量化(10)-阶段性小结！以及量化平台对比


### 从零开始卷量化系列(代码实现篇)：
- [x] 从零开始卷量化(11)-Python量化速成，一个简单的选股模型
- [x] 从零开始卷量化(12)-Python量化进阶，Pandas数据处理入门！
- [x] 从零开始卷量化(13)-交易数据可视化，Matplotlib初探！
- [x] 从零开始卷量化(14)-搭建本地量化平台，跟我先买个云服务器！【适合新手】
- [x] 从零开始卷量化(15)-本地量化研究四件套：conda/jupyter/pandas/akshare
- [x] [从零开始卷量化(17)-基于TaLib指标库的多股票Backtrader回测(上)](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618567&idx=1&sn=0baef9f3aa427510b95142be9cfda02c&chksm=8394e9bab4e360ac919708b9120ec000bad7d5a4f8616e8de323bf7d30f5173365f776a7bc31&scene=21#wechat_redirect)
- [x] [从零开始卷量化(18)-基于TaLib指标库的多股票Backtrader回测(下) 【完整策略】](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618581&idx=1&sn=4d4b7fb7c21768f7e39da59cf2e6d755&chksm=8394e9a8b4e360bed7226a8e5c6d1093448c82510abb5a59655b56bebbf9c83634114d0d37b7&cur_album_id=2322846473757212672&scene=190#rd)
- [x] [从零开始卷量化(19)-微软开源量化平台QLib初探](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618595&idx=1&sn=19f64aca717c63f4f6cd3c19a16f3d2d&chksm=8394e99eb4e36088edf2823b9f4001abe6077e6825753c451cd444c1aef724ba6657dbd31752&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(20)-基于TaLib和Qlib的指数增强策略a](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618606&idx=1&sn=18d4a8d7c3649863c97a0217794da146&chksm=8394e993b4e3608504173f7a0d96f1e0ceae677f68d70a06901df9f8ada1fd85e5ab19921ef5&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(21)-基于alphalens的因子分析a](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618629&idx=1&sn=14db531e735254f3ae0cee42938ad6c7&chksm=8394e9f8b4e360ee0886eb1057fdcaa29297183ad4e8f3cd4f7ff457a8633dafb5702bf8be96&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(22)-更全面的收益与风险分析，使用empyrical和quantstats！](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618658&idx=1&sn=2494de75e4e59e666c6661ba653430d1&chksm=8394e9dfb4e360c9426c075289012ffa2f0d2d9aa7c8d648270ca926c794675ffb62e1eda8ac&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(23)-深挖Qlib框架中AI功能的实现，机器学习初探！](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618684&idx=1&sn=8f3bd16ce6d4d0c60153a61f8c491298&chksm=8394e9c1b4e360d7b2cfce420a56242c5f1163a19973b0147adc02f8a550c2bb7ddc26286192&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(24)-魔改LightGBM损失函数，2年400%收益！](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618712&idx=1&sn=535db3a4ed84802f1ea4cb9fde6993b3&chksm=8394e825b4e3613372e5070fa243b68ef24801614fbcb98a2ceb4e0015ff2c810da2e34fb018&scene=178&cur_album_id=1762624395866324994#rd)
- [x] 从零开始卷量化(25)-脱离Qlib，手撸一个属于自己的量化投资框架！

### 从零开始卷量化系列(基本面分析篇)：
- [x] [从零开始卷量化(26)-回归基本面量化，跟我一起读财报！](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618731&idx=1&sn=2e4b90c06fa285214136aaf6343eaf06&chksm=8394e816b4e36100d2cf81f33bc4289b644d2aefdb3703ef2ffcab637fe4062ce2ac38321c1f&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(27)-资产负债表之货币资金](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618750&idx=1&sn=89121288cb2833551624f6ae89be9d87&chksm=8394e803b4e36115e8e6fb44479c30ce8be51cf0d1b1556189b3feb8269dc6133118e61e5373&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(28)-从“往来款”信息中获取超额收益！](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618761&idx=1&sn=2f0b061f5c1b7bce0f07540312d21dbc&chksm=8394e874b4e36162b45d0c57900fbec93763863015af949532f9773b1f6042867def3c642f5f&scene=178&cur_album_id=1762624395866324994#rd)
- [x] 从零开始卷量化(29)-存货的秘密
- [x] [从零开始卷量化(30)-资产负债表中的长期资产](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618784&idx=1&sn=33b44dbba11330505151591f3a8e4542&chksm=8394e85db4e3614b712ed2db0f32fe7738bcd16c565df358f53b9e7a77ae1b71036402534c01&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(31)-金融性资产和商誉，回测新高！](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618791&idx=1&sn=b258d59a5c5b5afd0ecee9c9af0acef2&chksm=8394e85ab4e3614c6063327b8b307837a3bdf2c36d5927b70e4fc9da3cdab9ec3f811f3e890b&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(32)-财报分析速成，三大报表一起看！](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618813&idx=1&sn=5f398b0e9cabc31248e44418d31b0a96&chksm=8394e840b4e36156a91647cfcfb96afbe0a5991015c10df134adad1ed0e549aa0368f7eebebd&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(33)-徒手画个杜邦分析图？](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618836&idx=1&sn=d2ac6a1b78033a02b77c423b002c500d&chksm=8394e8a9b4e361bf9046e6fbbe760c68b9614ecd6109124226d2a9302d88f678bd98c3ba6f3e&scene=178&cur_album_id=1762624395866324994#rd)
- [x] [从零开始卷量化(34)-财务困境与财务舞弊模型：ZScore、OScore* 和MScore助你一键排雷！](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618853&idx=1&sn=1da8c226255608f8920b7d744daef2b5&chksm=8394e898b4e3618e8e606ae9c638da406f0f551d98b8d020c5a5a9657c1f09816b26ac55029b&scene=178&cur_album_id=1762624395866324994#rd)
- [x] 从零开始卷量化(35)-手撸一个基本面量化研究框架？

### 从零开始卷量化系列(技术面分析篇)：
备注：基于xlib，半成品的量化框架，参考使用
- [x] [从零开始卷量化(36)-技术面量化：带上python，我们一起看图炒股！](https://mp.weixin.qq.com/s?__biz=MzAxNDgwNTA3NA==&mid=2649618890&idx=1&sn=8b4805c8c645fd854c4b32355b1b40f6&chksm=8394e8f7b4e361e1ba2ebfce9096b5dbb4a97b97e72cbfb50e026df3ca303b72ab265770a635&scene=178&cur_album_id=1762624395866324994#rd)
- [x] 从零开始卷量化(37)-历史行情波动中极值点的判断
- [x] 从零开始卷量化(38)-道氏理论123法则和2B法则的量化代码实现
- [x] 从零开始卷量化(39)-基于道氏理论的选股与回测，看到结果我沉默了…
- [x] 从零开始卷量化(40)-未来函数消灭战！
- [x] 从零开始卷量化(41)-艾略特波浪理论的基础概念
- [x] 从零开始卷量化(42)-艾略特波浪理论中驱动五浪的识别
- [x] 从零开始卷量化(43)-基于波浪理论的量化策略，穿越牛熊！
- [x] 从零开始卷量化(44)-最全面的技术分析方法，江恩理论初探！
- [x] 从零开始卷量化(45)-使用python实现江恩角度线
- [x] 从零开始卷量化(46)-基于江恩斐波那契分割的量化策略，年化24%？
- [x] 从零开始卷量化(47)-国货之光，缠论初探！
- [x] 从零开始卷量化(48)-使用python识别缠论的中枢
