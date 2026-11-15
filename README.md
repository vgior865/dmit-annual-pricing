# dmit年付优惠：最低多少钱？哪个码能用？续费会不会涨？洛杉矶香港东京怎么选（全套餐年付价格表）

dmit年付优惠落到具体数字上就三句话：最低年付门槛是 $36.9/年的 WEE 入门款，折算约 $3.07/月；带大陆优化的年付起点是洛杉矶 LAX.AN4.Pro TINY，$88.88/年，不到 $7.5/月；折扣码基本都是循环折扣（Recurring），续费按同一折扣价走，不存在首年便宜、第二年涨回原价。

下面把三地全部年付套餐的价格、目前能用的码、码的触发条件，以及下单前该知道的限制讲清楚。价格取自公开整理，官网标价随库存和活动调整，结算页显示为准。

> **按需求直接选**
> - 只跑国际业务、预算优先：WEE 入门款，$36.9/年
> - 电信宽带、要国内访问优化：LAX.AN4.Pro TINY，$88.88/年
> - 联通或移动：LAX.EB 系列，季付及以上叠 8 折循环码
> - 要 20–50ms 延迟：香港 HKG.Pro；日本节点：TYO.T1
>
> 👉 [对比 DMIT 全部年付套餐与当前库存](https://www.dmit.io/aff.php?aff=9081)

## 年付套餐价格表

DMIT 有三个机房：洛杉矶、香港、东京。每个机房下又分三条线，线路等级直接决定价格：

- **Premium（Pro）**：三网 CN2 GIA 回程，国内访问优化最完整
- **Eyeball（EB）**：电信联通走 AS9929、移动走 CMIN2 回程，价格低一档
- **Tier 1（T1）**：国际骨干接入，不做大陆优化，流量给得最多

另有一条 Premium Secure（LAX.sPro），CN2 GIA 回程配 Cloudflare Magic Transit 高防去程，面向需要 DDoS 防护的建站用户。

### 洛杉矶 LAX.Pro：三网 CN2 GIA 回程

| 套餐 | 配置 | 月流量 | 年付价 | 购买 |
| --- | --- | --- | --- | --- |
| LAX.AN4.Pro TINY | 1核 / 2G / 20G SSD | 1000G | $88.88/年 | [ 选 AN4 Pro TINY 年付](https://www.dmit.io/aff.php?aff=9081&pid=237) |
| LAX.AN4.Pro Pocket | 2核 / 2G / 40G SSD | 1500G | $159.98/年 | [ 选 AN4 Pro Pocket 年付](https://www.dmit.io/aff.php?aff=9081&pid=238) |
| LAX.AN5.Pro TINY | 1核 / 2G / 20G SSD | 1000G | $119.99/年 | [ 选 AN5 Pro TINY 年付](https://www.dmit.io/aff.php?aff=9081&pid=100) |
| LAX.AN5.Pro Pocket | 2核 / 2G / 40G SSD | 1500G | $203.90/年 | [ 选 AN5 Pro Pocket 年付](https://www.dmit.io/aff.php?aff=9081&pid=137) |
| LAX.Pro.MALIBU | 1核 / 1G / 20G SSD | 1TB | $49.90/年 | [ 查看 MALIBU 年付方案](https://www.dmit.io/aff.php?aff=9081) |

AN4 和 AN5 是两代硬件平台，AN5 用 AMD EPYC 9005 系列。同配置下 AN5 比 AN4 贵 31–44 美元/年，回程线路完全一样。有第三方 Geekbench 记录显示 AN5 单核 2770、多核 11829，跑分高出老款 Intel Xeon E5 一个量级。除非你要跑编译、转码这类吃 CPU 的活，Pro 线选 AN4 更划算。

另外，$36.9 的 WEE 入门款在不同整理文章里的归属有分歧：有的把它算进 Pro 线，有的归到 T1 线。价格本身各来源一致，但它没有大陆优化，按 T1 口径理解更稳妥。这里不放 Pro 表里，免得误导。

### 洛杉矶 LAX.EB：AS9929 + CMIN2

| 套餐 | 配置 | 月流量 | 年付价 | 购买 |
| --- | --- | --- | --- | --- |
| LAX.AN4.EB.CORONA | 1核 / 1G / 20G SSD | 2T | $49.00/年 | [ 选 CORONA 年付](https://www.dmit.io/aff.php?aff=9081&pid=218) |
| LAX.AN4.EB TINY | 1核 / 2G / 20G SSD | 1500G | $88.88/年 | [ 选 AN4 EB TINY 年付](https://www.dmit.io/aff.php?aff=9081&pid=245) |
| LAX.AN4.EB Pocket | 2核 / 2G / 40G SSD | 3000G | $159.98/年 | [ 选 AN4 EB Pocket 年付](https://www.dmit.io/aff.php?aff=9081&pid=246) |
| LAX.AN5.EB TINY | 1核 / 2G / 20G SSD | 1500G | $119.99/年 | [ 选 AN5 EB TINY 年付](https://www.dmit.io/aff.php?aff=9081&pid=189) |

不同来源对 EB TINY 的月流量有 1500G 和 1.2T 两种写法，EB Pocket 的核数也有 1 核和 2 核两种说法。上表只列了两源一致的部分，具体规格以购买页标注为准。

### 洛杉矶 LAX.T1：国际线路，大流量

| 套餐 | 配置 | 月流量 | 年付价 | 购买 |
| --- | --- | --- | --- | --- |
| LAX.T1.WEE | 1核 / 1G / 20G SSD / 1Gbps | 1000G | $36.90/年 | [ 查看 LAX T1 WEE](https://www.dmit.io/aff.php?aff=9081) |
| LAX.AN5.T1 V2C2G | 2核 / 2G / 40G SSD | 5TB | $143.00/年 | [ 查看 T1 V2C2G 年付](https://www.dmit.io/aff.php?aff=9081) |
| LAX.AN5.T1 G2C4G | 2核 / 4G / 80G SSD | 4TB | $162.00/年 | [ 查看 T1 G2C4G 年付](https://www.dmit.io/aff.php?aff=9081) |
| LAX.AN5.T1 V2C4G | 2核 / 4G / 80G SSD | 10TB | $229.00/年 | [ 查看 T1 V2C4G 年付](https://www.dmit.io/aff.php?aff=9081) |

LAX.T1.WEE 这条只有单一来源的搜索摘要，未能交叉验证，下单前请自己在官网确认。

### 香港 HKG 与东京 TYO

| 套餐 | 配置 | 线路 | 年付价 | 购买 |
| --- | --- | --- | --- | --- |
| HKG.T1.WEE | 1核 / 1G / 20G SSD / 1000G | 国际 Tier 1 | $36.90/年 | [ 选香港 T1 WEE](https://www.dmit.io/aff.php?aff=9081&pid=48) |
| HKG.Pro.VICTORIA | 1核 / 1G / 20G SSD / 800G / 300Mbps | CN2 GIA + AS9929 + CMI | $298.88/年 | [ 查看香港 Pro 年付](https://www.dmit.io/aff.php?aff=9081) |
| TYO.T1.WEE | 1核 / 1G / 20G SSD / 1000G | 国际 Tier 1 | $36.90/年 | [ 选东京 T1 WEE](https://www.dmit.io/aff.php?aff=9081&pid=101) |
| TYO.Pro.Shinagawa | 1核 / 1G / 20G SSD / 800G / 100Mbps | CN2 GIA + AS9929 + CMI | $199.99/年 | [ 查看东京 Pro 年付](https://www.dmit.io/aff.php?aff=9081) |

香港 Pro 的入门价在两份整理资料里对不上：一份给的是 VICTORIA 的 $298.88/年，另一份写“$259.9/年上下”。这两个数不能取平均，只能说香港 Pro 的年付门槛在 260–300 美元区间，具体看你选的套餐。东京的 TYO.EB 系列目前基本下架或缺货，只剩 Pro 和 T1 两个方向。

### 官网以月付、季付为主的套餐

| 套餐 | 起步价 | 计费周期 | 购买 |
| --- | --- | --- | --- |
| LAX.EB.TINY | $28.88 | 季付 | [ 查看 EB TINY 季付](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.Pocket | $14.90 | 月付 | [ 查看 EB Pocket](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.STARTER | $29.90 | 月付 | [ 查看 EB STARTER](https://www.dmit.io/aff.php?aff=9081) |
| HKG.EB 系列 | $29.90 起 | 月付 | [ 查看香港 EB 系列](https://www.dmit.io/aff.php?aff=9081) |
| TYO.Pro 系列 | $21.90 起 | 月付 | [ 查看东京 Pro 系列](https://www.dmit.io/aff.php?aff=9081) |

洛杉矶月付整体起步价是 EB 系列 $9.9 起、Pro 系列 $9.99 起，上面列的是几个常见配置。

## 年付优惠码：现在能用的是哪几个

码的有效性差别很大，下面按验证强度分三档。填之前都要在结算页点 Validate Code 看实际减免，码区分大小写，建议直接复制。

**三源交叉验证，可信度最高**

| 优惠码 | 适用范围 | 折扣 |
| --- | --- | --- |
| `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF` | LAX Eyeball 全系，季付/半年付/年付 | 8 折循环，续费同价 |

**双源一致，带附加条件**

| 优惠码 | 适用范围 | 折扣 |
| --- | --- | --- |
| `202510_HKG_TYO_PRO_20OFF_RECURRING` | 香港 Pro、东京 Pro，季付及以上 | 8 折循环 |
| `202510_HKG_TYO_T1_30OFF_RECURRING` | 香港 T1、东京 T1，季付及以上，不含 WEE | 7 折循环 |
| `2025-TYO-T1-HI-GSL-NON-MONTHLY-30OFF` | 东京 T1，季付及以上 | 7 折循环 |

**单一来源，需自行验证**

| 优惠码 | 适用范围 | 折扣 |
| --- | --- | --- |
| `HKG-T1-ANNUALLY-45OFF-RECUR` | 香港 T1 年付 | 45% 循环折扣，并赠更多 vCPU、硬盘翻倍、内存升级 |
| `LAX-T1-ANNUALLY-RECUR-30-OFF` | LAX T1 年付，TINY 及以上 | 7 折循环 |
| `2025-TYO-T1-HI-GSL-MONTHLY-10OFF` | 东京 T1，月付 | 9 折循环 |

`HKG-T1-ANNUALLY-45OFF-RECUR` 是这批码里力度最大的一个，如果它真的给到配置升级，等于买到的是一台升配版。但只有一份资料提到它，也没说 WEE 款能不能用，所以别拿 $36.9 去乘 0.55 算价格，那个数不成立。

节假日前后 DMIT 通常会放新码，力度和适用范围每次都不一样。手上没有确定能用的码，也不用硬等，日常这几组循环码已经把价格压得比较低了。

👉 [带着优惠码去 DMIT 结算页试算](https://www.dmit.io/aff.php?aff=9081)

## 用码规则：四条，踩错一条就白填

**一单只能填一个码，不能叠加。** 选对再用。同时有两个码想用，只能二选一。

**大多数码要求季付及以上。** 这是最常见的踩坑点：拿着 8 折码按月付下单，Validate 之后价格纹丝不动，不是码失效，是周期不对。上面表格里除了明确标月付的那条，其余都要求季付或年付。

**循环折扣是真循环。** Recurring 的意思是续费时折扣照旧，你第一年付多少，第二年还是多少。DMIT 没有“首年特价、次年恢复原价”这种结构。

**填写位置在结算页。** 购物车或结账页找 “Apply Promo Code” 或 “Promo Code” 输入框，粘贴后点 “Validate Code”，价格实时刷新，确认减免金额对得上再付款。

顺带说一句年付本身的价值：在 DMIT 的定价结构里，年付比月付乘 12 便宜，差额大致相当于 1–2 个月的月付。就算一个码都没有，选年付也已经省了一笔。

## 用码之后的真实成本：季付加 8 折 vs 直接年付

以洛杉矶 EB TINY 为例，两个路径的开销差得不多：

- **季付 $28.88，不用码**：一年 $115.52
- **季付 $28.88，叠 8 折循环码**：每季约 $23.10，一年约 $92.40
- **直接年付 $88.88**：一年 $88.88

季付加码比直接年付贵约 3.5 美元，但换来的是每三个月可以重新决定一次，中途不满意随时停。如果你还没用过 DMIT 的线路，这 3.5 美元买的是灵活性。这个算术按公开报价推算，实际金额以结算页为准，另外 EB TINY 的月流量在不同资料里有差异，只能作数量级参考。

香港 T1 和东京 T1 的 7 折码不含 WEE 款，$36.9 的入门套餐叠不上，别指望折到 20 多美元。

## 买之前必须知道的四件事

**退款政策。** 购买 3 天内且流量使用不超过 30GB，可以全额退款，扣支付手续费；超过 3 天但在 30 天内，按剩余价值退款。这条对第一次买的人很关键，先季付试一个月，线路不合适还能退。

👉 [用季付先试一个月，3 天内不满意可全额退](https://www.dmit.io/aff.php?aff=9081)

**IP 被墙。** 每 15 天可以免费更换一次被封 IP，其他情况 $5/次。洛杉矶 Pro 和 EB 满足条件时还能申请免费换。对面向国内的项目来说，这个频率够用。

**流量超量不停机。** T1 系列流量跑完后限速继续运行，香港和东京限速 50Mbps，洛杉矶 100Mbps，下月流量重置后恢复正常。Pro 系列的部分套餐也支持超量限速不断网。流量波动大的用户，这比直接断网友好得多。

**热门套餐经常缺货。** 不超售的代价就是库存紧张，洛杉矶 Pro 的 WEE 和 TINY 款、香港 Pro 系列补货后几小时就没了。看到有货别拖。

## 按运营商和场景选

**电信宽带**：洛杉矶 Pro 或香港 Pro。三网回程 CN2 GIA，晚高峰延迟按第三方实测口径在 155–165ms，丢包控制得比较稳。预算紧就 LAX.AN4.Pro TINY。

**联通、移动**：LAX.EB 系列。电信联通走 AS9929、移动走 CMIN2，价格比 Pro 低一档，季付以上叠 8 折码之后性价比更明显。

**只跑国际业务、外贸站、落地节点**：T1 的 WEE 款，$36.9/年就够。没有大陆优化，但国际骨干接入质量不差。

**对延迟敏感**：香港机房，国内延迟普遍 20–50ms，这个数字洛杉矶给不了。代价是年付 260 美元起步。

**需要日本节点**：TYO.T1，$36.9/年入场。

**要 DDoS 防护**：LAX.sPro，去程走 Cloudflare Magic Transit，回程 CN2 GIA，面向企业站和外贸独立站。

## FAQ

**年付最低多少钱？**

T1 系列的 WEE 款，洛杉矶、香港、东京都是 $36.9/年，折算每$3.07。纯国际线路，没有大陆优化。要 CN2 GIA 的话，最低是洛杉矶 LAX.AN4.Pro TINY 的 $88.88/年。

**优惠码第二年续费还有效吗？**

标注 Recurring 的码续费同价，这是 DMIT 折扣码的常态。下单前在购物车确认折扣类型是 Recurring 还是首期专用。

**月付能用这些码吗？**

大部分不能。上面列的码基本都要求季付及以上，月付只有 `2025-TYO-T1-HI-GSL-MONTHLY-10OFF` 这一条明确适用。

**流量用完了会停机吗？**

T1 系列不会，限速继续跑，香港和东京 50Mbps、洛杉矶 100Mbps，下月重置。Pro 系列部分套餐同样支持。

**支持支付宝吗？**

支持支付宝、微信、PayPal 和信用卡，国内付款没障碍。客服工单有中文渠道，回复是英文。

## 最后

只做国际业务、把成本压到最低，选 WEE 的 $36.9/年。要国内访问优化又不想花太多，洛杉矶 LAX.AN4.Pro TINY 的 $88.88/年是有大陆优化的实际起点。联通移动用户走 EB 线，季付起叠 `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF`，年化成本和直接年付差不多，还多一份灵活。

下单前做两件事：在结算页点一次 Validate Code 确认减免真的生效；核对所选计费周期是季付或年付，月付触发不了大部分码。

👉 [查看 DMIT 当前年付库存与最新标价](https://www.dmit.io/aff.php?aff=9081)
