# 便宜月付 VPS：DMIT 洛杉矶、香港、东京月付机型价格全表，从 $6.9 起挑出真正划算的那台

搜"便宜月付 VPS"的人，需求往往很具体：不想一次压一年的钱，想先花几美元跑一个月看看，或者项目还在试水，随时可能换机房。

麻烦的是，月付在很多商家那里是要加价的选项，配置还常被砍一刀。DMIT 属于少数把月付和年付都明码摆出来卖、月付还能从 $6.9 起步的商家。它的机型命名倒是挺劝退——`LAX.AN5.T1.V4C8G` 这种名字第一次看基本靠猜。这篇文章只解决一件事：月付这条路上，哪些机型值得买，每档差价买到了什么。

## 先搞明白：DMIT 的便宜是分档换来的

DMIT 所有套餐按回中国大陆的路由质量分三档，价格差距主要来自这里，跟 CPU 和内存关系不大。

| 线路档 | 回程路由 | 适合谁 |
| --- | --- | --- |
| Tier 1（T1） | 纯国际 BGP，无中国方向优化 | 纯海外业务、备份、中转节点 |
| Eyeball（EB） | CMIN2 / 9929 方向的中国优化 | 预算优先、移动联通用户为主 |
| Premium（Pro） | 三网 CN2 GIA 回程 | 大陆访客是主力、晚高峰不能掉速 |

判断方法就一句：用户主要在国内、又舍不得每月几十美元，先看 EB；只跑国际流量，T1 的性价比是压倒性的；对延迟和稳定性有硬要求，再考虑 Pro。买错档位的代价不是多花钱，是花了钱还觉得慢——论坛里不少"DMIT 太慢"的抱怨，最后发现是买成了 T1。

顺带说清 DMIT 的底子。这家 2017 年前后开始做 VPS，美国注册，机房只有洛杉矶、香港、东京三个，全部 KVM 虚拟化 + AMD EPYC 处理器，付款支持支付宝、PayPal 和信用卡，工单可以用中文沟通。口碑集中在两点：不超售、流量用完后限速但不停机。几个测评提到搬瓦工的部分 CN2 GIA 带宽是从 DMIT 采购的，所以它在高端线路上的资源是自己持有的，不是转卖。缺点也很实在：贵，工单响应按小时算，升级宿主机时不一定提前发邮件通知。

## 月付 $20 以内，DMIT 目前能买到这些

这是最核心的一张表。所有价格都是月付单价，年付专款会单独标注。

| 机房 | 线路 / 平台 | 套餐 | 配置（CPU / 内存 / 硬盘） | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- | --- |
| 洛杉矶 | Tier 1 | WEE | 1 核 / 1GB / 20GB | 1TB | $36.90/年 | [查看这台年付特价机](https://www.dmit.io/aff.php?aff=12046) |
| 洛杉矶 | Tier 1 | TINY | 1 核 / 1GB / 20GB | 2TB | $6.90/月 | [查看洛杉矶 T1 月付入门款](https://www.dmit.io/aff.php?aff=12046) |
| 洛杉矶 | Tier 1 | STARTER | 2 核 / 2GB / 40GB | 4TB | $12.90/月 | [查看 T1 STARTER 价格](https://www.dmit.io/aff.php?aff=12046) |
| 洛杉矶 | Tier 1 · AN5 VOLUME | V2C2G | 2 核 / 2GB / 40GB | 5TB | $14.90/月 | [查看 AN5 大流量入门款](https://www.dmit.io/aff.php?aff=12046) |
| 洛杉矶 | Tier 1 · AN5 GENERAL | G2C4G | 2 核 / 4GB / 80GB | 4TB | $16.90/月 | [查看 AN5 GENERAL 系列](https://www.dmit.io/aff.php?aff=12046) |
| 洛杉矶 | Premium · AS3 | TINY | 1 核 / 2GB / 20GB | 1TB | $10.90/月 | [查看 CN2 GIA 最便宜的一台](https://www.dmit.io/aff.php?aff=12046) |
| 洛杉矶 | Premium · AS3 | Pocket | 2 核 / 2GB / 40GB | 1.5TB | $16.90/月 | [查看 Pro Pocket 月付价](https://www.dmit.io/aff.php?aff=12046) |
| 洛杉矶 | Premium · AN5 | TINY | 1 核 / 2GB / 20GB | 1TB | $12.98/月 | [查看新一代平台 Pro TINY](https://www.dmit.io/aff.php?aff=12046) |
| 洛杉矶 | Eyeball · AS3 | TINY | 1 核 / 2GB / 20GB | 1.5TB | $10.90/月 | [查看 EB 入门款月付价](https://www.dmit.io/aff.php?aff=12046) |
| 洛杉矶 | Eyeball · AS3 | Pocket | 2 核 / 2GB / 40GB | 3TB | $16.90/月 | [查看 EB Pocket 配置](https://www.dmit.io/aff.php?aff=12046) |
| 香港 | Tier 1 | TINY | 1 核 / 1GB / 20GB | 2TB | $6.90/月 | [查看香港 T1 月付方案](https://www.dmit.io/aff.php?aff=12046) |
| 东京 | Tier 1 | TINY | 1 核 / 1GB / 20GB | 2TB | $6.90/月 | [查看东京 T1 月付方案](https://www.dmit.io/aff.php?aff=12046) |
| 东京 | Premium | TINY | 1 核 / 1GB / 20GB | 500GB | $21.90/月 | [查看东京 Pro TINY](https://www.dmit.io/aff.php?aff=12046) |

几个值得注意的地方：$6.90 的三台 TINY 在洛杉矶、香港、东京同价，香港和东京能卖到这个价位，靠的是 T1 线路没有做中国优化。同样的 $10.90，Premium 给的是 CN2 GIA + 1TB 流量，Eyeball 给的是 2Gbps 端口 + 1.5TB 流量——选线路质量还是选资源量，这里必须做一次取舍。

## 洛杉矶 LAX 在售机型完整月付价格表

洛杉矶是 DMIT 的主力机房，机型也最多。同一款套餐常有 AS3（AMD EPYC 7003）和新一代 AN5（AMD EPYC 9005）两个平台版本，AN5 更贵但性能更强，两台机器的单核差距不小。

### Premium 系列（三网 CN2 GIA）

| 平台 | 套餐 | 配置 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| AS3 | TINY | 1 核 / 2GB / 20GB | 1TB | $10.90/月 | [查看 Pro TINY 价格](https://www.dmit.io/aff.php?aff=12046) |
| AS3 | Pocket | 2 核 / 2GB / 40GB | 1.5TB | $16.90/月 | [查看 Pro Pocket 价格](https://www.dmit.io/aff.php?aff=12046) |
| AS3 | STARTER | 2 核 / 2GB / 80GB | 3TB | $34.90/月 | [查看 Pro STARTER 价格](https://www.dmit.io/aff.php?aff=12046) |
| AS3 | MINI | 4 核 / 4GB / 80GB | 5TB | $62.90/月 | [查看 Pro MINI 价格](https://www.dmit.io/aff.php?aff=12046) |
| AS3 | MICRO | 4 核 / 4GB / 160GB | 7TB | $87.90/月 | [查看 Pro MICRO 价格](https://www.dmit.io/aff.php?aff=12046) |
| AS3 | MEDIUM | 6 核 / 8GB / 160GB | 14TB | $199.90/月 | [查看 Pro MEDIUM 价格](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | TINY | 1 核 / 2GB / 20GB | 1TB | $12.98/月 | [查看 AN5 Pro TINY](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | Pocket | 2 核 / 2GB / 40GB | 1.5TB | $18.90/月 | [查看 AN5 Pro Pocket](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | STARTER | 2 核 / 2GB / 80GB | 3TB | $38.90/月 | [查看 AN5 Pro STARTER](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | MINI | 4 核 / 4GB / 80GB | 5TB | $76.90/月 | [查看 AN5 Pro MINI](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | MICRO | 4 核 / 4GB / 160GB | 7TB | $99.90/月 | [查看 AN5 Pro MICRO](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | MEDIUM | 6 核 / 8GB / 160GB | 14TB | $219.90/月 | [查看 AN5 Pro MEDIUM](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | LARGE | 8 核 / 16GB / 320GB | 25TB | $459.90/月 | [查看 AN5 Pro LARGE](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | GIANT | 8 核 / 24GB / 640GB | 50TB | $839.90/月 | [查看 AN5 Pro GIANT](https://www.dmit.io/aff.php?aff=12046) |

Pro 系列流量超量后限速在 4Mbps 到 10Mbps 之间，网不会断，但那个速度基本只能跑轻量任务。拿它做中转或大流量转发要提前算清楚。

### Eyeball 系列（CMIN2 / 9929 回程）

EB 的结构跟 Pro 一一对应，同价位流量给得更多，带宽也更宽。

| 平台 | 套餐 | 配置 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| AS3 | TINY | 1 核 / 2GB / 20GB | 1.5TB | $10.90/月 | [查看 EB TINY 价格](https://www.dmit.io/aff.php?aff=12046) |
| AS3 | Pocket | 2 核 / 2GB / 40GB | 3TB | $16.90/月 | [查看 EB Pocket 价格](https://www.dmit.io/aff.php?aff=12046) |
| AS3 | STARTER | 2 核 / 2GB / 80GB | 5TB | $34.90/月 | [查看 EB STARTER 价格](https://www.dmit.io/aff.php?aff=12046) |
| AS3 | MINI | 4 核 / 4GB / 80GB | 10TB | $62.90/月 | [查看 EB MINI 价格](https://www.dmit.io/aff.php?aff=12046) |
| AS3 | MICRO | 4 核 / 4GB / 160GB | 14TB | $87.90/月 | [查看 EB MICRO 价格](https://www.dmit.io/aff.php?aff=12046) |
| AS3 | MEDIUM | 6 核 / 8GB / 160GB | 30TB | $199.90/月 | [查看 EB MEDIUM 价格](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | TINY | 1 核 / 2GB / 20GB | 1.5TB | $12.98/月 | [查看 AN5 EB TINY](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | Pocket | 2 核 / 2GB / 40GB | 3TB | $18.90/月 | [查看 AN5 EB Pocket](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | STARTER | 2 核 / 2GB / 80GB | 5TB | $38.90/月 | [查看 AN5 EB STARTER](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | MINI | 4 核 / 4GB / 80GB | 10TB | $76.90/月 | [查看 AN5 EB MINI](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | MICRO | 4 核 / 4GB / 160GB | 14TB | $99.90/月 | [查看 AN5 EB MICRO](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | MEDIUM | 6 核 / 8GB / 160GB | 30TB | $219.90/月 | [查看 AN5 EB MEDIUM](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | LARGE | 8 核 / 16GB / 320GB | 50TB | $459.90/月 | [查看 AN5 EB LARGE](https://www.dmit.io/aff.php?aff=12046) |
| AN5 | GIANT | 12 核 / 24GB / 640GB | 100TB | $839.90/月 | [查看 AN5 EB GIANT](https://www.dmit.io/aff.php?aff=12046) |

一条需要提前知道的现实：有测评指出 EB 系列（包括那张热门的 $39.9/年 WEE）IPv4 不解锁 Netflix、Disney+ 这类流媒体，ChatGPT、TikTok 倒是没问题。想拿便宜机型当流媒体解锁机，这条线大概率会让你失望。

### Tier 1 系列（国际线路，最容易买到便宜月付的地方）

T1 是全场单价最低的档，AN5 平台全系标配 10Gbps 端口，超量后限速 100Mbps 到 500Mbps 继续跑，比 Pro 的 4Mbps 宽松得多。

| 系列 | 套餐 | 配置 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| T1 | WEE | 1 核 / 1GB / 20GB | 1TB | $36.90/年 | [查看 T1 年付款 WEE](https://www.dmit.io/aff.php?aff=12046) |
| T1 | TINY | 1 核 / 1GB / 20GB | 2TB | $6.90/月 | [查看 T1 TINY 月付](https://www.dmit.io/aff.php?aff=12046) |
| T1 | STARTER | 2 核 / 2GB / 40GB | 4TB | $12.90/月 | [查看 T1 STARTER 月付](https://www.dmit.io/aff.php?aff=12046) |
| T1 | MINI | 2 核 / 4GB / 80GB | 8TB | $21.90/月 | [查看 T1 MINI 月付](https://www.dmit.io/aff.php?aff=12046) |
| T1 | MICRO | 4 核 / 4GB / 120GB | 16TB | $32.90/月 | [查看 T1 MICRO 月付](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 VOLUME | V2C2G | 2 核 / 2GB / 40GB | 5TB | $14.90/月 | [查看 VOLUME 系列价格](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 VOLUME | V2C4G | 2 核 / 4GB / 80GB | 10TB | $23.90/月 | [查看 VOLUME 大流量档](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 VOLUME | V4C4G | 4 核 / 4GB / 120GB | 20TB | $36.90/月 | [查看 VOLUME 中配方案](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 VOLUME | V4C8G | 4 核 / 8GB / 160GB | 40TB | $52.90/月 | [查看 VOLUME 高流量方案](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 VOLUME | V8C16G | 8 核 / 16GB / 240GB | 80TB | $119.90/月 | [查看 VOLUME 大机型](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 VOLUME | V12C24G | 12 核 / 24GB / 320GB | 160TB | $199.90/月 | [查看 VOLUME 顶配](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 GENERAL | G2C4G | 2 核 / 4GB / 80GB | 4TB | $16.90/月 | [查看 GENERAL 系列价格](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 GENERAL | G4C8G | 4 核 / 8GB / 160GB | 8TB | $36.90/月 | [查看 GENERAL 中配](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 GENERAL | G8C16G | 8 核 / 16GB / 320GB | 12TB | $79.90/月 | [查看 GENERAL 高配](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 GENERAL | G12C24G | 12 核 / 24GB / 480GB | 24TB | $119.90/月 | [查看 GENERAL 大机型](https://www.dmit.io/aff.php?aff=12046) |
| T1 · AN5 GENERAL | G16C32G | 16 核 / 32GB / 640GB | 32TB | $199.90/月 | [查看 GENERAL 顶配](https://www.dmit.io/aff.php?aff=12046) |

VOLUME 和 GENERAL 的关系很容易看错：平台和端口完全一样，区别只在内存和流量的配比。像 V4C8G 和 G4C8G 同为 $36.90、同为 4 核 8GB，但流量一个 40TB、一个 8TB。要流量选 V，要均衡选 G，价格一样的情况下别选反。

## 香港和东京：月付价位完全是两个世界

香港 T1 是全场性价比最反直觉的一档——$6.90/月能拿到香港节点，比香港 Pro 的 $39.90/月便宜将近六倍，代价是路由不做中国大陆优化。如果你的用户在新加坡、台湾或者只是需要一个亚太中转点，这个差价省得很值。

香港 T1 月付价格：TINY $6.90（1 核 / 1GB / 20GB / 2TB）、STARTER $12.90（1 核 / 2GB / 40GB / 4TB）、MINI $21.90（2 核 / 2GB / 60GB / 8TB）、MICRO $32.90（4 核 / 4GB / 80GB / 16TB）、MEDIUM $49.90、LARGE $99.90、GIANT $199.90，WEE 依然是 $36.90/年。

东京 T1 的价格和香港 T1 基本一致，同一套档位、同一个起价。东京 Pro 的门槛则是三地 Pro 里最低的，TINY 从 $21.90/月起步，比香港 Pro 的 $39.90/月便宜不少。

需要提醒的是，香港的 Premium 和 Eyeball 各来源记录的价格存在明显出入，Eyeball TINY 有 $29.90/月 和 $39.90/月 两种说法，Pro TINY 从 $39.90/月 起。这类机型的库存和定价调整频繁，[👉 到官网核对香港机房的实时在售机型](https://www.dmit.io/aff.php?aff=12046)比看任何整理表都靠谱。

## 月付还是年付：$36.9 的年付款要不要冲

DMIT 有个很吸引人的设计——年付款 WEE。$36.90 一年，折下来每月约 $3.08，比 TINY 月付的 $6.90 便宜一半以上。这也是为什么论坛里总有人说"活动的时候 1 核 1G 20G 只要 49.9 刀一年"。

但这笔账要算清楚三件事：

- WEE 的配置是真的低配，1 核 1GB 内存 20GB 硬盘，流量通常只有 1TB，超量后限速也更狠（有测评提到会降到 2Mbps）。跑个轻量博客或代理中转够用，挂数据库和 WordPress 完整站会紧。
- WEE 常年缺货，补货靠盯通知，不是想买就能买。
- 部分整理提到 TINY 档年付有额外折扣、其他机型年付大约 9 折，但这类政策会变，结算页上显示的数字才算数。

如果你的用途三个月内可能变，老老实实月付。DMIT 大部分机型支持月付、季付、年付，切换周期不用重买机器。

## 买便宜月付机最容易踩的四个坑

**买成 T1 却期待 CN2 GIA。** 这是最高频的错误。T1 的流量和带宽数字都比 Pro 漂亮，价格还更低，但回国路由是真的没优化。下单前先确认自己需要哪一档。

**忽略超量后的限速档位。** Pro 和 EB 超量后限速 4Mbps 到 10Mbps，T1 是 100Mbps 到 500Mbps。数字看着都是"不限流量"，实际体验完全不是一回事。

**拿 EB 当流媒体解锁机。** 前面说过，有测评实测 EB 的 IPv4 不解锁 Disney+、Netflix。这类需求要先看测评，别只看价格。

**忘了 IP 被墙之后的成本。** Pro 和 EB 产品每 15 天可以免费换一次 IP，其他情况换 IP 收费 $5/次。这个政策比起动辄 8 到 10 美元的同行算便宜，但仍然要算进总成本。

另外，如果预算允许，优先考虑 AN5 平台。有整理提到 AS3 系列在官网定价页带提示，说该系列仍在建设和优化中，期间磁盘性能可能波动、SLA 低于成熟平台。对磁盘 IO 敏感的业务，花那多出来的两三美元换 AN5 是划算的。

## 下单和验机：五步走完

1. [👉 从推广入口进官网](https://www.dmit.io/aff.php?aff=12046)，注册账号。支持支付宝付款，不用折腾外币卡。
2. 选机房（洛杉矶 / 香港 / 东京）、选线路档（T1 / EB / Pro）、选平台（AS3 / AN5）、选计费周期。
3. 结算前把购物车里的价格和本文表格对一遍。DMIT 调价比较频繁，以购物车实际金额为准。
4. 开通后先别急着迁业务。官方提供各机房的测试 IP 和 Looking Glass，先用 ping 和路由追踪确认回程走向符合预期。
5. 有资料提到 DMIT 的退款政策是 3 天内可全额退款（用量控制在 30GB 以内）、30 天内按比例退款。这是第三方整理的版本，具体条款以下单时展示的服务条款为准，别把它当成万能后悔药。

## 结语：便宜月付 VPS 的取舍点只有一个

DMIT 不是最便宜的那一类 VPS。$6.90/月是它的下限，再往上就迅速拉开。它值不值得，取决于你买的到底是不是线路。

如果你只需要一台能跑起来的海外机器，$6.90 的洛杉矶、香港、东京 T1 TINY 随便挑一台，香港和东京物理距离更近，延迟会舒服一些。如果国内访客是核心，$10.90 的洛杉矶 Pro TINY 或者 Eyeball TINY 是 CN2 GIA 和 CMIN2 的入门价，这个价位在同档线路里基本没什么对手。再往上的配置，属于月付价位跳到几十美元之后的事，那时候就该认真考虑年付反而更省了。

[👉 去官网看当前在售的全部月付机型](https://www.dmit.io/aff.php?aff=12046)，库存和价格以页面实时显示为准——DMIT 的便宜档，经常是补货当天就被抢光的那几档。
