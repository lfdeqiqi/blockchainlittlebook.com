# Level 1 萌新入门
# 一.五分钟快速入门（基础了解）
# 1.1 FIBOS 简介
## 1.1.1 简介
FIBOS 斐波，是一个创造和发展区块链应用生态的平台。FO 是 FIBOS 斐波生态的流通通证，是 FIBOS 链上资源的权益凭证，也是 FIBOS 生态中的基础价值媒介。

FIBOS 斐波采用了 DPOS 共识机制：均衡去中心化与超强性能，满足大规模商业应用的要求。独创双智能合约开发引擎及体系：自研的 JavaScript 智能合约引擎，同时兼容 eos C++ 智能合约。简化智能合约开发步骤，降低了开发门槛，使区块链商用的开发、部署、学习和迭代成本指数级下降。

## 1.1.2 FO钱包下载方式
点击网站进入 FO 钱包下载界面  [https://wallet.fo/zh-cn](https://wallet.fo/zh-cn)

[FO 钱包下载安装教程.pdf](https://uploader.shimo.im/f/OrdCZf1Vhg09vXkP.pdf)

 

# 1.2.账户注册
## 1.2.1 注册方式
**没有 FIBOS 账户的用户：**

（1）打开 FO 钱包，点击创建钱包

（2）输入要创建账户的名称（名称即用户的 FIBOS 地址），由 12 位字符组成，只能使用小写字母+数字 1~5 组成。

（3）设置密码，账户的密码只会保存在用户本地，如果忘记密码，可以通过清除 FO 钱包全部数据来重新导入账户设置密码，密码由 8 位字符组成。

（4）完成密码设置后，系统会为账户生成一份私钥，必须妥善保存。

（5）创建账户完成后，系统为账户抵押 0.2 FO 用于获得少量的 CPU 以及 NET 资源，并且会分配少量的 RAM 用于存储用户信息。 

**拥有FIBOS账户的用户：**

（1）可以通过输入私钥完成账户导入

（2）可以通过导入Keystore来完成账户导入

## 1.2.2 私钥，Keystore
私钥： 是由系统随机生成的 64 位十六进制的字符组成，具备唯一性。必须严密保存，才能保护账户安全。

Keystore： 在 FIBOS 内，Keystore 由系统利用你的FO账户密码生成的一组字串符，用 Keystore 导入账户时需要输入正确的密码才能导入。如果运用 Ketstore ，建议运用复杂的密码，并且将 Keystore 放在安全的存储程序中，并且密码一定需要记住，密码无法通过各种方式找回。

# 1.3.账户安全
FIBOS 内保证账户安全有两种方式：

1：私钥保存： 由于区块链的不可逆性，FIBOS 内并不会保存用户的账户密码，用私钥直接可以登录相应的账户，所以私钥的保存十分重要。建议将私钥存放在纸面上或者记录在非联网存储的软件上。

2：Keystore： 通过将特殊方式生成一组字串符，该字串符内含有私钥以及账户密码信息，需要通过密码解锁才能直接导入私钥账户以及设定的密码信息，Keystore 生成后会被区块链保存，使用 Keystore 保存私钥需要牢记密码以及妥善保存 Keystore 。

# 1.4.FO获取方式
## 1.4.1 交易所
### 1.4.1.1 交易所直接购买
   目前只有少部分交易所可以直接通过币币交易（ 比如 USDT / FO ）购买 FO，可购买的交易所网址如下：

CoinTiger ：[https://www.cointiger.com](https://www.cointiger.com/)

LBank ：[http://lbank.info/](http://lbank.info/)

ZG.COM ：[https://www.zg.com/](https://www.zg.com/)

AEX.com ：[https://www.aex.plus](https://www.aex.plus/)

Newdex ：[https://newdex.io/](https://newdex.io/)

比特兔 ：[https://bitrabbit.io/](https://bitrabbit.io/)

### 1.4.1.2 通过交易所购买后跨链获得
通过交易所（ ZG.COM，比特兔，Newdex 等）购买 FIBOS 支持的货币 ETH（USDT，DAI），再用购买的货币通过 IBC（[http://cross.fo/](http://cross.fo/)）跨链转换成 FIBOS 内相应的稳定币 FOETH（ FOUSDT ， FODAI ），最后通过 DEX 交易所（[http://exchange.fo/](http://exchange.fo/)）交易成 FO，通过交易所购买需要完成人物身份验证，需要消耗一定时间，交易风险小。

## 1.4.2 OTC
### 1.4.2.1 OTC中心化场外钱包交易
通过法币交易购买 USDT（ETH，DAI），再通过 IBC（[http://cross.fo/](http://cross.fo/)）跨链转换成FIBOS 内相应的稳定币，最后通过 DEX 交易所（[http://exchange.fo/](http://exchange.fo/)）交易成FO。OTC交易不需要验证身份，方便快捷，但是需要自己承担部分风险，所以建议去成熟的 OTC平台。

[FO于AEX充值、交易及提现教程 ..pdf](https://uploader.shimo.im/f/ZVOk9PUtMFshqx8D.pdf)

### 1.4.2.2 通过智能合约 OTC 平台直接买卖小额 FO
FO内的智能合约 OTC 平台为 FO OTC，通过 FO OTC 可以直接用法币和商家购买 FO ，通过智能合约方式，极大降低了交易风险，目前 FO OTC 暂未开放。

# 1.5.转账
如何在FO钱包中进行转账、跨链转账、查询 ？

[http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=330](http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=330)

# 1.6.Dapp 使用
## 1.6.1 DAPP 平台简介（基于FIBOS）
FIBOS 是一个结合 FIBJS 以及 EOS 的 JavaScript 的运行平台，它允许使用 JavaScript 编写智能合约。

JavaScript 开发 + BANCOR 协议智能通证 + 开发者服务，FIBOS 平台实现了快速开发、快速部署和稳定且流动的通证体系，帮助开发者一步进入区块链时代。

## 1.6.2 使用方式
下载 FO 钱包，点击 DAPP 即可。

# 1.7.基础常见问题
1.问：怎么老是创建 FO 账户失败？

答：账户名必须是 12 位字符，由小写字母和数字 1—5 组成的。

 

2.问：FO 地址是什么？

答：FO 地址即创建钱包时的名称。

 

3.问：我的 FO 地址是什么？

答：在钱包首页左上角显示的就是您的 FO 地址。

 

4.问：为什么我的苹果手机覆盖后再下载 FO 钱包却用不了？

答：您好，您备份私钥后，卸载重新安装一下就可以了。

 

5.问：为什么我 FO 钱包上的节点信息不能显示？

答：可能是网络问题。

# 二.什么是FIBOS
# 2.1.了解FIBOS
FIBOS是一个很社区化的生态，FIBOS的每一个重要的决定，都是由社区充分讨论后决定的。无论大到Bancor的拆除，还是小到跨链矿工手续费的支付方式，都会在社区中充分讨论，形成共识后，再予以实施。

同时社区也是生态的重要开发者，比如红包，钱包，钱包插件，FIBOS的决议，基本上的路线，都是社区充分讨论，形成提案后由BP投票执行的。

# 2.2.FIBOS 理念      
FIBOS 的愿景是通过帮助创业者高效低成本的开发和运营去中心化应用 ( Dapp ) 来建造 一个基于区块链的实体经济。 

# 2.3.FIBOS 产品
## 2.3.1 钱包、插件钱包等相关教程
FO 钱包使用：

[http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=330](http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=330)

FO 插件钱包使用 ：

[http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=468](http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=468)

MetaMask 使用 ：

[http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=329](http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=329)

## 2.3.2 exchange.fo
是 FIBOS 官方制作的最去中心化的交易设施，用 DEX 协议作为底层架构，交易通过智能合约完成。

**交易中心：**

**限价交易**：“限价” 即只有当市场价格到了你报的买入价或卖出价后才会成交,如果不到则不会成交,那些未立刻成交的限价委托通常称之为“挂单”。

**市价交易**：“市价”即根据已有的挂单进行成交,如果你要求以市价买入,你会优先和卖1成交,如果卖1的挂单成交完了还未达到你委托的买入量,则和卖2成交,如果还未达到委托量,再和卖3成交,以此类推。

**底仓交易**：用户将交易对所需的双方货币与系统交易存放在系统交易仓中，存入仓底后用户可以参与对应交易对中每笔交易的手续费分行。

**订单管理：**

管理当前订单，可撤销未完成的订单，查看自己的成交记录，以及历史挂单记录。

## 2.3.3 cross.fo
是 FIBOS 官方制作的跨链设施，用 IBC 协议作为底层架构，方便不同区块链货币快速跨链转换。目前跨链仅支持 ETH，USDT，DAI。

如何跨链：[http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=465](http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=465)

# 2.4.市场
| 交易所名称   | 链接   | 已上架的交易对   | 是否需要VPN   | 
|:----|:----|:----|:----|
| CoinTiger   | [https://www.cointiger.com](https://www.cointiger.com/)   | FO/USDT   | 是   | 
| LBank    | [http://lbank.info/](http://lbank.info/)   | FO/USDT   | 是   | 
| ZG.COM   | [https://www.zg.com/](https://www.zg.com/)   | FO/USDT   | 否   | 
| AEX.com   | [https://www.aex.plus](https://www.aex.plus/)   | FO/CNC  FO/BTC   | 否   | 
| Newdex   | [https://newdex.io/](https://newdex.io/)   | FO/EOS   | 是   | 
| 比特兔   | [https://bitrabbit.io/](https://bitrabbit.io/)   | FO/ETH   | 否   | 

目前FO在各交易所的流通量

| 交易所名称   | 流通量   | 
|:----:|:----:|
| AEX | 10,741,245.8537 | 
| CoinTiger  | 10,701,464.3514 | 
| LBank | 4,434,362.8287 | 
| ZG.com  | 804,971.3703 | 
| BitRabbit | 150,658.4926 | 
| Newdex  | 10,444.1134 | 

# 2.5.合作伙伴
VENUS ：[http://www.vnscoin.org/](http://www.vnscoin.org/)

IMEOS ONE ：[https://imeos.one/](https://imeos.one/)

HelloEos ：[https://www.helloeos.com.cn/](https://www.helloeos.com.cn/)

第三极 ：[http://labs.fo/](http://labs.fo/)

创世资本 ：[http://newgenesiscap.com/ch](http://newgenesiscap.com/ch)

mimondo ：[http://imondo.io/](http://imondo.io/)

慢雾科技：[https://www.slowmist.com/](https://www.slowmist.com/)

Maker ：[https://makerdao.com/zh-CN/](https://makerdao.com/zh-CN/)

BYTON（比原链）：[https://bytom.io/](https://bytom.io/)

麦子钱包 ：[http://www.mathwallet.org/cn/](http://www.mathwallet.org/cn/)

USDE ：[https://pizza.live/](https://pizza.live/)

# Level 2 萌新进阶
# 三.FIBOS 生态
# 3.1. 节点
负责维护网络运行的终端就可以称之为——节点。

在互联网领域，企业所有的数据运行都集中在自己的服务器中，那么这个服务器就是一个节点。

在 FIBOS 中，公有链上的节点通过投票，得票数在前 21 位的节点获得记账权并提供服务，系统会生成加密货币给予他们奖励。

创建节点详见 ：[https://dev.fo/zh-cn/guide/node-instruction.html](https://dev.fo/zh-cn/guide/node-instruction.html)。

**投票机制**：用户可以将已拥有的 FO 抵押成 CPU 资源以及 NET 资源获取票数，可以利用票数参与节点投票，每人最多可以给 30 个节点投票，每个节点获取的票数相同，他人帮助抵押的资源不能获得票数。

例子：小明拥有 200FO ，他将 200FO 抵押称 100CPU 资源和 100NET 资源，此时他获得了 200 票数。他可以最多可以给社区内 30 各节点投票，每个节点获取的票数均为 200。

# 3.2.各个浏览器 
| 名称   | 地址   | 开发者   | 简介   | 
|:----|:----|:----|:----|
| ROCKS Explorer   | [https://see.fo](https://see.fo/)    | fibosrockskr 节点   | see.fo 是 fibosrockskr 节点为社区提供的浏览器，可以查看各种区块链信息，并发起各种交易。头条 dapp 是浏览器的趣味应用，用户可以通过竞价发布个人的各种信息。   | 
| fibscan 浏览器   | [https://fibscan.io/#/](https://fibscan.io/#/)   | fibscandotio   | fibscan 是由 fibscandotio 为社区提供的浏览器。主要提供提供区块、交易、账户等信息的搜索、查询及追踪等功能   | 
| Chain Moe   | [http://explorer.chain.moe/fo](http://explorer.chain.moe/fo)  | FIBOS   | FIBOS 区块链浏览器，可查看链上最新区块、最新交易、区块高度、内存等信息，页面简洁明了、使用简单方便。   | 

# 3.3.FIBOS DeFi（分布式金融系统）
## 3.3.1 IBC 协议
FIBOS IBC（[cross.fo](http://cross.fo)），是一种无需额外治理层，仍可实现真正去中心化的资产跨链方案，带来原生级资产安全性能、更好的使用体验、更稳定的价值尺度。ETH 链上的 USDT、ETH、Dai 等优质数字资产已可在双链中自由流通。其余开发者也可以通过合作接入IBC协议参与跨链转换。

如何使用IBC协议：[http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=465](http://forum.fo/index.php?app=forums&module=forums&controller=topic&id=465)

## 3.3.2 DEX 协议
FIBOS DEX （[exchange.fo](http://exchange.fo)）协议，实现了无中心资产交易，成为了具有通过合约完成交易撮合、算法交易提供深度及流动性、无需注册无需认证、任意 token 间发起交易对、无需冲提等特点的“零”障碍资产流动基础协议。通过该协议用户可以参与 FIBOS 内的货币交易，FIBOS 的合作伙伴在 FIBOS 链上发行的 token 也可以通过 DEX 协议建立交易对参与交易。

# # 3.4. 支持的钱包、插件等外界应用
FO 钱包 ：基于 FIBOS 生态系统的智能钱包，支持 FIBOS 链上币种一键兑换，支持多币种一站式管理，内置 DAPP Store 直接抵达用户。钱包内可直接尽心抵押投票，享受年化 6% 的投

票激励收益。

下载地址 ：[https://wallet.fo/zh-cn](https://wallet.fo/zh-cn)

[FO 钱包下载安装教程.pdf](https://uploader.shimo.im/f/GUe2V1OcCxgivk0w.pdf)



FO wallet插件 ：FO Wallet 插件钱包是 FIBOS 网络的 PC 端入口。简洁的设计风格、强大

的性能及持续的迭代优化，都为了给您带来更流畅的 FIBOS 生态体验。

下载地址 ：[https://wallet.fo/zh-cn/fowallet](https://wallet.fo/zh-cn/fowallet)

[FOWallet 插件教程.docx](https://uploader.shimo.im/f/vY9OFxealAoQdGV1.docx)



Math（插件版）：麦子钱包是 FIBOS 的合作方之一，麦子钱包（插件版）支持 FO 的快速

交易。

下载地址 ：[http://mathwallet.org/cn/](http://mathwallet.org/cn/)

[Math 钱包插件使用.pdf](https://uploader.shimo.im/f/7Gvsl5BN10ggpZWr.pdf)



# 3.5.如何成为开发者
点击进入开发者社区快速入门 ：[https://dev.fo/zh-cn/](https://dev.fo/zh-cn/)

# 四.FIBOS 社区
# 4.1 社交平台
官网：[FIBOS.IO](http://FIBOS.IO)

论坛：[http://forum.fo/](http://forum.fo/)

微博：[FIBOSio](https://weibo.com/fibosio)

Twitter：[https://twitter.com/fibos_io](https://twitter.com/fibos_io)

Github：[https://github.com/fibosio](https://github.com/fibosio)

Facebook：[https://www.facebook.com/FibosIO](https://www.facebook.com/FibosIO)

# 4.2 社群
微信：FIBOSIO

QQ群：392113712

telegram：[https://t.me/FIBOSIO](https://t.me/FIBOSIO)

# Level 3 萌新进化
# 五.FIBOS 社区活动
# “一念巨浪”系列 Dapp 大赛 二期 2018年12月14日
为了激励更多有梦想、有创意的开发者和项目方，第二季“一念巨浪”DAPP“征集大赛现已启动，本次大赛已获得20多家机构、社区、媒体的大力支持，其中包括创世资本、节点资本、BKFUND、拜占庭资本等知名投资机构；HelloEOS、EOSAsia、IMEOS、BCCN 等强影响力社区；慢雾科技、比特派、BeeDApp、ENU 等多个生态合作伙伴；巴比特、链世界、共享财经、节点财经、麟角财经、币虎财经、高度财经、未来财经、币快报、白话区块链、世链财经、块连线、闪电头条、情报局等深度合作媒体。同时获得东南大学区块链实验室等高校学术机构的指导。

活动链接 ：世链财经 [http://shilian.com/huiyi/2019/0108/19591.html](http://shilian.com/huiyi/2019/0108/19591.html)  

数据报告：二师兄区块链 [https://www.esxqk.com/216386/](https://www.esxqk.com/216386/)

# CoinTiger 上线活动 2019年 6月19日	
为庆祝 FIBOS斐波（FO）上线 CoinTiger 交易所（cointiger.one），FIBOS 联合 CoinTiger 举办了【80,000 FO，加入 FIBOS & CoinTiger 微信群即送】和【充值 FO，瓜分 160,000 FO】活动，获得了 FIBOS 及 Cointiger 社区的积极参与和热烈反响，感谢大家的支持，我们将会不断致力于 FIBOS 斐波的社区维护和发展。

数据报告 ：金色财经 [https://www.jinse.com/blockchain/405020.html](https://www.jinse.com/blockchain/405020.html)

# ZG 上线活动   2019年6月29日
为庆祝FIBOS斐波（FO）上线 ZG.COM交易所（ZG.COM），FIBOS 联合 ZG.COM举办了斐波/FIBOS 红包雨，活动结束时，净充值（充币+买入-卖出-提币）数大于2,000 FO 的用户将根据人数瓜分 FO ，最高可瓜分 150,000 FO 奖励。

数据报告 ：币乎 [https://bihu.com/article/1002331592](https://bihu.com/article/1002331592)

# OK 江湖录活动    2019年7月19日
在 FOX1.0--cross.fo 上线之际，迎来了我们优秀的合作伙伴—OKEX 交易所主办的“OK 江湖录”系列访谈活动。主要对 FIBOS 发起人 响马 进行访谈。 

访谈详情 ：币乎 [https://bihu.com/article/1569918670](https://bihu.com/article/1569918670)

# Lbank 相关活动  2019年7月18日
为庆祝「 LBank 上线 FIBOS 交易」，LBank 将启动奖励量共 200,000 FO 的净买入大赛 + 登录空投 FO 的双重活动。

数据报告 ：LBANK  [https://lbankinfo.zendesk.com/hc/zh-cn/articles/360031058094](https://lbankinfo.zendesk.com/hc/zh-cn/articles/360031058094)

# 六.FIBOS 大事记
| 时间 | 事件 |                       链接 | 
|:----|:----|:----|
| 2018年8月28日   | FIBOS 主网上线 	   | [https://fibos.io/zh-cn/newsdetail/bei-jing-shi-jian-2018-nian-8-yue-28-ri-20-shi-fibos-zhu-wang-zheng-shi-qi-dong-cheng-gong-](https://fibos.io/zh-cn/newsdetail/bei-jing-shi-jian-2018-nian-8-yue-28-ri-20-shi-fibos-zhu-wang-zheng-shi-qi-dong-cheng-gong-)   | 
| 2018年8月30日   | 克服第一次共识危机	   |    | 
| 2018年9月1日   | 21 节点社区化完成   |    | 
| 2018年9月2日   | FO 钱包 1.0版本发布   |    | 
| 2018年9月4日   | 成功狙击粉尘攻击	   | [https://fibos.io/zh-cn/newsdetail/she-qu-gong-gao-fibos-cheng-gong-di-yu-ben-ci-fen-chen-gong-ji-](https://fibos.io/zh-cn/newsdetail/she-qu-gong-gao-fibos-cheng-gong-di-yu-ben-ci-fen-chen-gong-ji-)   | 
| 2018年9月20日   | FO 钱包支持锁仓通证	   |    | 
| 2018年10月6日   | 慢雾科技参选超级节点	   |    | 
| 2018年10月16日   | 正式支持 JS 合约引擎	   | [https://fibos.io/zh-cn/newsdetail/2018-nian-10-yue-17-ri-js-he-yue-shang-xian-zhu-wang-cheng-gong](https://fibos.io/zh-cn/newsdetail/2018-nian-10-yue-17-ri-js-he-yue-shang-xian-zhu-wang-cheng-gong)   | 
| 2018年10月19日   | FO钱包新增锁仓通证转账	   |    | 
| 2018年10月22日   | FO钱包上线多个 DAPP 	   | [https://fibos.io/zh-cn/newsdetail/san-kuan-dapp-ru-zhu-fo-qian-bao-](https://fibos.io/zh-cn/newsdetail/san-kuan-dapp-ru-zhu-fo-qian-bao-)   | 
| 2018年10月27日   | 第一季 DAPP 大赛正式启动   | [https://fibos.io/zh-cn/newsdetail/shou-ji-dapp-da-sai-ru-wei-ming-dan](https://fibos.io/zh-cn/newsdetail/shou-ji-dapp-da-sai-ru-wei-ming-dan)   | 
| 2018年11月7日   | 修复主网数据库分叉	   |    | 
| 2018年11月23日   | 响马接受巴比特视频直播	   | [https://www.8btc.com/video/316227](https://www.8btc.com/video/316227)   | 
| 2018年12月5日   | FO 钱包支持红包	   |    | 
| 2018年12月7日   | 主网上线100天   | [https://m.weibo.cn/status/4314549391979952?](https://m.weibo.cn/status/4314549391979952?)   | 
| 2018年12月14日   | 第二季 DAPP 大赛正式启动	   | [http://shilian.com/huiyi/2019/0108/19591.html](http://shilian.com/huiyi/2019/0108/19591.html)   | 
| 2019年1月4日	   | 响马进行《区块链安全》直播	   | [https://m.weibo.cn/status/4324715612491144?](https://m.weibo.cn/status/4324715612491144?)   | 
| 2019年1月18日   | FO 钱包支持节点投票	   |    | 
| 2019年1月28日	   | FO 钱包支持推荐分享	   |    | 
| 2019年2月18日	   | 举办元宵灯谜系列活动	   | [https://fibos.io/zh-cn/newsdetail/fibos-yuan-xiao-deng-mi-da-ji-he](https://fibos.io/zh-cn/newsdetail/fibos-yuan-xiao-deng-mi-da-ji-he)   | 
| 2019年3月1日	       | 发布生态繁荣计划	   | [https://fibos.io/zh-cn/newsdetail/zhu-li-sheng-tai-fan-rong-fibos-tui-chu-xin-ji-hua](https://fibos.io/zh-cn/newsdetail/zhu-li-sheng-tai-fan-rong-fibos-tui-chu-xin-ji-hua)   | 
| 2019年3月5日	       | FO 上线 AEX 交易所	   | [http://www.beekuaibao.com/notice/626469436378427392](http://www.beekuaibao.com/notice/626469436378427392)   | 
| 2019年3月11日	   | HelloPool 参选超级节点	   |    | 
| 2019年3月16日		   | FO 正式与 EOS 解绑，总量销毁 90%   | [http://www.btb8.com/eos/1903/40276.html](http://www.btb8.com/eos/1903/40276.html)   | 
| 2019年3月27日	   | 响马接受巴比特《8问》 专访	   | [http://www.sohu.com/a/305201567_104036](http://www.sohu.com/a/305201567_104036)   | 
| 2019年3月29日	   | 郭宏才参选超级节点	   |    | 
| 2019年4月2日	       | 上线 Newdex 交易所	   | [https://www.chainnode.com/post/307836](https://www.chainnode.com/post/307836)   | 
| 2019年4月10日   | AEX 新增 FO/CNC 交易对   | [https://www.aex-global.com/page/article.html?id=138895&comment_id=1377275&owner_id=502083&reply_user_id=381447&post_id=138895&&msg_id=4238990](https://www.aex-global.com/page/article.html?id=138895&comment_id=1377275&owner_id=502083&reply_user_id=381447&post_id=138895&&msg_id=4238990)   | 
| 2019年4月12日	   | Starteos 参选超级节点	   |    | 
| 2019年4月21日		     | 响马接受AEX 首期《大咖有话说》专访   | [https://www.aex.plus/page/article.html?id=333244](https://www.aex.plus/page/article.html?id=333244)   | 
| 2019年5月9日	       | FIBOS 中文名征集活动启动	   | [https://www.1zj.com/2019/gxx_0509/48868.html](https://www.1zj.com/2019/gxx_0509/48868.html)   | 
| 2019年5月17日	   | FIBOS 中文名为“斐波”	   | [https://www.1zj.com/2019/gxx_0523/50157.html](https://www.1zj.com/2019/gxx_0523/50157.html)   | 
| 2019年5月20日	   | 520社区表白活动	   |    | 
| 2019年5月28日	    | FO 钱包更新 UI 设计	   |    | 
| 2019年6月2日	        | 拜占庭资本参选超级节点	   |    | 
| 2019年6月5日	        | FO钱包支持链上转账	   |    | 
| 2019年6月19日	    | 上线 CoinTiger 交易所 	   | [https://www.jinse.com/blockchain/405020.html](https://www.jinse.com/blockchain/405020.html)   | 
| 2019年6月29日	   | 上线 ZG.com 交易所	   | [https://www.bishijie.com/kuaixun_327036](https://www.bishijie.com/kuaixun_327036)   | 
| 2019年7月4日	        | 与比原链达成战略合作	   | [http://www.heightfn.one/flash/20190704/vr9hxkcre2yzemwb.html](http://www.heightfn.one/flash/20190704/vr9hxkcre2yzemwb.html)   | 
| 2019年7月6日	        | 响马出席白话区块链线下活动	   | [https://blog.csdn.net/mrRqAEr7ci9s2v0/article/details/85333574](https://blog.csdn.net/mrRqAEr7ci9s2v0/article/details/85333574)   | 
| 2019年7月18日	    | 上线 LBank 交易所 	   | [https://lbankinfo.zendesk.com/hc/zh-cn/articles/360025770193-%E5%85%B3%E4%BA%8E-LBank-%E4%B8%8A%E7%BA%BF-FIBOS-%E4%BA%A4%E6%98%93%E7%9A%84%E5%85%AC%E5%91%8A](https://lbankinfo.zendesk.com/hc/zh-cn/articles/360025770193-%E5%85%B3%E4%BA%8E-LBank-%E4%B8%8A%E7%BA%BF-FIBOS-%E4%BA%A4%E6%98%93%E7%9A%84%E5%85%AC%E5%91%8A)   | 
| 2019年7月19日	    | 响马接受 OK 江湖录访谈	   | [https://www.chainnews.com/articles/434822069654.htm](https://www.chainnews.com/articles/434822069654.htm)   | 
| 2019年7月20日	   | FIBOS IBC 协议发布	   | [https://fibos.io/zh-cn/newsdetail/fox1-0-cross-fo-zhen-zheng-de-qu-zhong-xin-hua-kua-lian-fang-an-yi-shi-yun-xing-shang-xian](https://fibos.io/zh-cn/newsdetail/fox1-0-cross-fo-zhen-zheng-de-qu-zhong-xin-hua-kua-lian-fang-an-yi-shi-yun-xing-shang-xian)   | 
| 2019年7月21日	   | FO 钱包支持 IBC 协议    |    | 
| 2019年7月24日	    | 举办《斐波创作家》征文活动	   |    | 
| 2019年7月29日	    | 举办有奖竞猜系列活动	   |    | 
| 2019年8月1日	        | FO 钱包支持消息推送	   |    | 
| 2019年8月2日	        | DEX 内测版本发布	   |    | 
| 2019年8月8日	        | 官方平台发布所征集文章	   |    | 
| 2019年8月15日   | FIBOS 一周年贡献社区投票	   |    | 
| 2019年8月19日	   | FIBOS DEX 协议正式上线   | [https://fibos.io/zh-cn/newsdetail/fibos-dex-xie-yi-zhan-dian-exchange-fo-xian-yi-zheng-shi-shang-xian-](https://fibos.io/zh-cn/newsdetail/fibos-dex-xie-yi-zhan-dian-exchange-fo-xian-yi-zheng-shi-shang-xian-)   | 
| 2019年8月19日   | 与 MakerDAO 达成合作	   | [https://fibos.io/zh-cn/newsdetail/fibos-makerdao-da-cheng-he-zuo-huo-ban-guan-xi](https://fibos.io/zh-cn/newsdetail/fibos-makerdao-da-cheng-he-zuo-huo-ban-guan-xi)   | 
| 2019年8月20日	    | exchange.fo 接入DEX 协议	   | [https://www.weibo.com/6563835901/I2YFgrlZT?type=comment#_rnd1571905490549](https://www.weibo.com/6563835901/I2YFgrlZT?type=comment#_rnd1571905490549)   | 
| 2019年8月23日	   | 响马受邀参与哔哔 News	   | [https://www.chainnews.com/articles/067210852245.htm](https://www.chainnews.com/articles/067210852245.htm)   | 
| 2019年8月27日	   | 6 位创世顾问献上周年祝福   | [https://www.weibo.com/6563835901/I4uw7EcsI?type=comment#_rnd1571905621287](https://www.weibo.com/6563835901/I4uw7EcsI?type=comment#_rnd1571905621287)   | 
| 2019年8月28日	    | FIBOS 成立一周年	   | [https://www.hellobtc.com/kp/hd/08/2174.html](https://www.hellobtc.com/kp/hd/08/2174.html)   | 
| 2019年8月29日	   | FIBOS 一周年总结，对社区贡献者进行奖励	   |    | 
| 2019年8月30日	    | FIBOS/Fibjs 开发者 1,000万 FO 奖励计划	   |    | 
| 2019年9月5日	        | 与 Math 达成合作伙伴关系	   | [https://www.chainnews.com/articles/490552652416.htm](https://www.chainnews.com/articles/490552652416.htm)   | 
| 2019年9月6日	       | FO 钱包支持 DEX 协议    |    | 
| 2019年9月10日	   | 与 PIZZA 达成合作伙伴关系	   | [https://www.chainnode.com/post/373447](https://www.chainnode.com/post/373447)   | 
| 2019年9月18日	   | IBC 协议支持 ETH 跨链	   |    | 
| 2019年9月19日	   | FO 钱包支持 ETH 跨链	   |    | 
| 2019年9月20日	    | 公众号支持生态入口反馈	   |    | 
| 2019年9月21日	   | 投票激励比率调整为 2%	   | [https://fibos.io/zh-cn/newsdetail/fibos-tou-piao-shou-yi-bi-lv-yi-diao-zheng-fu-lin-ji-hua-xian-dao-tou-piao-ji-li-huo-dong-bi-lv-diao-zheng-ti-an-](https://fibos.io/zh-cn/newsdetail/fibos-tou-piao-shou-yi-bi-lv-yi-diao-zheng-fu-lin-ji-hua-xian-dao-tou-piao-ji-li-huo-dong-bi-lv-diao-zheng-ti-an-)   | 
| 2019年9月26日	   | FO 钱包支持 Keystore	   |    | 
| 2019年9月29日	    | 斐波入选陀螺财经明星专栏榜   | [https://www.tuoluocaijing.cn/article/detail-68259.html](https://www.tuoluocaijing.cn/article/detail-68259.html)   | 
| 2019年9月30日	   | IBC协议登录比特派钱包   | [https://www.weibo.com/6404560407/I9lGXBXSt?type=repost#_rnd1571906133092](https://www.weibo.com/6404560407/I9lGXBXSt?type=repost#_rnd1571906133092)   | 

# 七.常见问题
1.问：为什么钱包里看不到 DAPP 的入口？

   答：是您的网络问题哦，更换网络可以解决该问题。

2.问：抵押网络报错是什么原因呢？

   答：可能是您内存不足，可以抵押一点 FO 购买内存。

3.问：请问怎么把时代的 FO 提到 FO 钱包里面

    答：您好，在我的资产中，点击 FO 提币，添加提币地址，填入您的 FO 地址即可。

4.问：FO 地址是什么？

   答：FO 地址即创建钱包时的名称。

5.问：FIBOS在开发方面只支持 MacOS,不支持 Windows 吗？

   答：这边现在支持 MacOS ，Ubuntu。 Windows 和 EOS 不支持，如果用 Windows 开发可以考虑用 Docker ，或者虚拟机。

6.问：怎么投票领取收益呢？

   答：打开 FO 钱包后，抵押资源——进入哦投票页面，选择要投票哦的节点，进行投票，至此投票完成。点击总收益领取投票奖励。

7.问：FO 红包怎么领取？

   答：点击 FO 红包链接，点击右上角选择在浏览器中打开，跳转到 FO 钱包就可以领取了。

8.问：为什么我的苹果手机覆盖后再下载 FO 钱包却用不了？

   答：您好，您备份私钥后，卸载重新安装一下就可以了。

9.问：现在要怎么才能兑换 FIBOS ？

   答：您好，可以在 AEX 交易所与 Newdex 交易所进行交易。

10.问：我投票了，为什么从昨晚到现在我的投票收益一直显示为0？

    答：您好，可能是网络问题，您切换一下网络试试。

11.问：我想把 FO 全部抵押投票，但怎么配置呢？

    答：您好，可以将 FO 先抵押为 CPU 或者 NET 资源就可以投票了。

# 八.区块链知识入门
# **1.什么是区块链  **
## **1.1 区块链的概念**
区块链是分布式数据存储、点对点传输、共识机制、加密算法等计算机技术的新型应用模式。区块链本质上是一个去中心化的数据库，同时作为数字货币的底层技术，是一串使用密码学方法相关联产生的数据块，每一个数据块中包含了一批次数字货币网络的交易信息，用于验证其信息的有效性（防伪）和生成下一个区块 。

## **1.2 区块链的特点**
### **1.2.1 共识机制**
区块链作为一个去中心化的分布式账本系统，然而在实际运行中，怎么解决因为去中心化后，保证整个系统能有效运行，各个节点诚实记账，在没有所谓的中心的情况下，互相不信任的个体之间就交易的合法性达成共识的共识机制。 

### **1.2.2 弱中心化**
区块链网络通常由数量众多的节点组成，根据需求不同会由一部分节点或者全部节点承担账本数据维护工作，少量节点的离线或者功能丧失并不会影响整体系统的运行。 

### **1.2.3 信息不可篡改 **
区块链系统中所记录的重要信息，均被摘要算法所覆盖，链越长对信息的确认次数越多，且所有 参与记账的节点均会存储一份数据拷贝。少量节点对数据的篡改是不被承认的，也无法影响系统整 体的运行。

### **1.2.4 智能合约**
智能合约由区块链内的多个用户共同参与制定，可用于用户之间的任何交易行为。协议中明确了双方的权利和义务，开发人员将这些权利和义务以电子化的方式进行编程，代码中包含会触发合约自动执行的条件。一旦编码完成，这份智能合约就被上传到区块链网络上，即全网验证节点都会接收到你的合约。

# **2.区块链的分类与共识机制**
## **2.1 区块链分类**
区块链分为3种，分别是公有链。联盟链。以及私有链

### **2.2 公有链**
公有链，是一个完全开放的分布式系统。公有链中的节点可以很自由的加入或者退出，不需要严格的验证和审核，比如比特币、以太坊、EOS 等。共识机制在公有链中不仅需要考虑网络中存在故障节点，还需要考虑作恶节点，并确保最终一致性。

### **2.3 联盟链**
联盟链，是一个相对开放的分布式系统。对于联盟链，每个新加入的节点都是需要验证和审核的，比如 Fabric、BCOS 等。联盟链一般应用于企业之间，对安全和数据的一致性要求较高，所以共识机制在联盟链中不仅需要考虑网络中存在故障节点，还需要考虑作恶节点，同时除过确保最终一致性外，还需要确保强一致性。

### **2.4 私有链**
私有链，是一个封闭的分布式系统。由于私有链是一个内部系统，所以不需要考虑新节点的加入和退出，也不需要考虑作恶节点。私有链的共识算法还是传统分布式系统里的共识算法，比如 zookeeper 的 zab 协议，就是类 paxos 算法的一种。只考虑因为系统或者网络原因导致的故障节点，数据一致性要求根据系统的要求而定。

## **2.2 共识机制**
### **2.2.1 POW**
PoW 是指系统为达到某一目标而设置的度量方法。简单理解就是一份证明，用来确认你做过一定量的工作。监测工作的整个过程通常是极为低效的，而通过对工作的结果进行认证来证明完成了相应的工作量，则是一种非常高效的方式。PoW 是按劳分配，算力决定一起，谁的算力多谁记账的概率就越大，可理解为力量型比较。	

### **2.2.2 POS**
POS 与POW 相比，不需要证明你在记账前做了某项工作，而是证明你拥有某些财产。开始竞争出块记账前，拥有权益的节点将自己的权益放入 POS 机制中，同时身份变为验证者，POS机制根据验证者下注的多少，采用随机的方式选出一个记账者进行出块记账。这个随机并不是真正的随机，一般跟下注的权益成正比，谁的权益多，谁获取记账权的概率就越大。如果选出的记账者在一段时间内没有记账，POS 机制重新选择记账节点，当出块完成，开始进入下一轮的记账。

### **2.2.3 DPOS**
DPOS：授权股权证明机制，基于 POS ，类似投票选举。任何持有货币的人都可以成为块生产者，都拥有投票权。每次投票前，候选 BP可以给自己拉票（线下方式），每次投票超过50%代表有效，然后生成一个 BP 候选池，每次从 BP 候选池中选择排名靠前的 21 个节点作为BP ，并对选出的 21 个 BP 随机排序。

# 九.媒体链接
1.三氪猫数字货币媒体	 FIBOS，友好的 EOS ？

[https://3kemao.com/archives/68984](https://3kemao.com/archives/68984)

2.简书	EOS侧链——FIBOS 简介	

[https://www.jianshu.com/p/f1fad0e0d8af](https://www.jianshu.com/p/f1fad0e0d8af)

3.简书	现在，还该不该投 Fibos ？	

[https://www.jianshu.com/p/979744621f33](https://www.jianshu.com/p/979744621f33)

4.CSDN	FIBOS-EOS 入门	

[https://blog.csdn.net/wxb880114/article/details/82347032](https://blog.csdn.net/wxb880114/article/details/82347032)

5.搜狐	Eos大涨的助力者——FIBOS 是什么 ？	

[https://www.sohu.com/a/251314097_610666](https://www.sohu.com/a/251314097_610666)

6.巴比特	西祠胡同创始人响马发起，上线三天注册用户超两万的 FIBOS 是什么	

[https://www.8btc.com/article/265681](https://www.8btc.com/article/265681)

7.book118	搭建一个 FIBOS 开发环境	

[https://max.book118.com/html/2018/1016/8072071045001127.shtm](https://max.book118.com/html/2018/1016/8072071045001127.shtm)

8.必链社	FIBOS：上线五天注册用户超两万 EOS 第一个现象级侧链！	

[http://www.bitdashi.com/news/info-1809040848381125.shtml](http://www.bitdashi.com/news/info-1809040848381125.shtml)

9.简书	【新手教学】手把手教你兑换 Fibos 的 Fo 智能通证！	

[https://www.jianshu.com/p/b2f55e52eda9](https://www.jianshu.com/p/b2f55e52eda9)

10.简书	聊聊 FIBOS，一个现象级EOS侧链！	

[https://www.jianshu.com/p/819105448a58](https://www.jianshu.com/p/819105448a58)

11.天涯社区	EOS的第一侧链FIBOS，你换币了吗？	

[http://bbs.tianya.cn/post-1179-23905-1.shtml](http://bbs.tianya.cn/post-1179-23905-1.shtml)

12.千币网	EOS近期走强原因之一｜FIBOS和IBO进来了解一下	

[http://www.btc112.com/EOS/37960.html](http://www.btc112.com/EOS/37960.html)

13.Segmentfault	FIBOS入坑指南——本地开发环境搭建	

[https://segmentfault.com/a/1190000017160787](https://segmentfault.com/a/1190000017160787)

14.简书	投 FIBOS 代码太难？MORE wallet推出傻瓜式一键投兑FO功能	

[https://www.jianshu.com/p/4b1f2f2825f7](https://www.jianshu.com/p/4b1f2f2825f7)

15.二师兄区块链	IMX交易所支持FIBOS 一键兑换FO	

[https://www.esxqk.com/88476/](https://www.esxqk.com/88476/)

16.陀螺财经	EOS侧链——FIBOS简介	

[https://www.tuoluocaijing.cn/article/detail-9156.html](https://www.tuoluocaijing.cn/article/detail-9156.html)

17.简书	Bancor 算法给 FIBOS 带来了什么？	

[https://www.jianshu.com/p/f78acacb1a20?from=timeline&isappinstalled=0](https://www.jianshu.com/p/f78acacb1a20?from=timeline&isappinstalled=0)

18.一直播	FIBOS小课堂:用JS开发区块链,你也可以!	

[http://www.yizhibo.com/l/gYhy84B1ptmaleVJ.html](http://www.yizhibo.com/l/gYhy84B1ptmaleVJ.html)

19.链得得APP	「大文观链」又一个EOS RAM？FIBOS基础介绍	

[https://baijiahao.baidu.com/s?id=1610549641211026742&wfr=spider&for=pc](https://baijiahao.baidu.com/s?id=1610549641211026742&wfr=spider&for=pc)

20.知乎	FIBOS 是什么？	

[https://zhuanlan.zhihu.com/p/43908086](https://zhuanlan.zhihu.com/p/43908086)

21.币乎	EOS合约开发之利器---FIBOS	

[https://bihu.com/article/1255782](https://bihu.com/article/1255782)

22.简书	未来发行项目的新模式？IBO+Fibos深度解读

[https://www.jianshu.com/p/cf504a71fee1](https://www.jianshu.com/p/cf504a71fee1)

23.新浪博客	7天3大变化！EOS侧链Fibos上线，网友：穿新鞋子走老路	

[http://blog.sina.com.cn/s/blog_d0632f1b0102z1br.html](http://blog.sina.com.cn/s/blog_d0632f1b0102z1br.html)

24.币莱财经	IBO+Fibos深度解读	

[https://www.niubilai.com/index/information/content/ctype/new/id/2550](https://www.niubilai.com/index/information/content/ctype/new/id/2550)

25.腾讯云+社区——企鹅号	四分钟上线 FIBOS 节点服务器	

[https://cloud.tencent.com/developer/news/361117](https://cloud.tencent.com/developer/news/361117)

26.确定财经	RAM交易之后，侧链FIBOS上线，IBO时代来临？	

[https://www.queding.cn/zixun/kuaixun/94929.html](https://www.queding.cn/zixun/kuaixun/94929.html)

27.JavaScript中文网	FIBOS入坑指南——本地开发环境搭建	

[https://www.javascriptcn.com/read-46615.html](https://www.javascriptcn.com/read-46615.html)

28.CTOLib码库	fibos-tracker 是一个 FIBOS 区块链 数据 API 服务框架	

[https://linux.ctolib.com/anlebcoder-fibos-tracker.html](https://linux.ctolib.com/anlebcoder-fibos-tracker.html)

29.36氪	Fibos创始人响马：当成本趋近于零，区块链就会有大规模应用	

[https://36kr.com/video/38586?from=message](https://36kr.com/video/38586?from=message)

30.百度贴吧	IMX交易所支持FIBOS 一键兑换FO	

[http://tieba.baidu.com/p/5876217686](http://tieba.baidu.com/p/5876217686)

31.站长之家	去中心化交易所Newdex正式开放CUSD、FIBOS交易区	

[http://www.chinaz.com/news/mt/2019/0404/1006799.shtml](http://www.chinaz.com/news/mt/2019/0404/1006799.shtml)

32.看准资讯	去中心化交易所Newdex正式开放CUSD、FIBOS交易区	

[https://www.kanzhun.com/news/425607.html](https://www.kanzhun.com/news/425607.html)

33.比特币之家	EOS第一侧链FIBOS发起人响马和你聊聊IEO后市将会如何？	

[http://www.btc798.com/articles/38839.html](http://www.btc798.com/articles/38839.html)

34.币圈网	Eos大涨的助力者——FIBOS是什么？	

[http://biiquan.com/article/40016](http://biiquan.com/article/40016)

35.深链财经	FIBOS创始人响马：区块链解决的就是资金流动的问题	

[https://www.shenliancaijing.com/portal/activity/activedetail.html?id=2499](https://www.shenliancaijing.com/portal/activity/activedetail.html?id=2499)

36.链向财经	FIBOS的主网上线，能否改变EOS的现状？	[https://www.baidu.com/link?url=Mri7SnaJ0GN_lewurkRLyXgexdMiA_GyxXN22I8J4f8jst0H_jO4Gsbw69hSaz7xjJ-xSRcuVOfp3fhYh5rh0K&wd=&eqid=e82cdbfe00015feb000000055cc814ad](https://www.baidu.com/link?url=Mri7SnaJ0GN_lewurkRLyXgexdMiA_GyxXN22I8J4f8jst0H_jO4Gsbw69hSaz7xjJ-xSRcuVOfp3fhYh5rh0K&wd=&eqid=e82cdbfe00015feb000000055cc814ad)

