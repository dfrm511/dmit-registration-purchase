# DMIT注册与购买全流程：需要实名认证吗？验证邮件收不到怎么办？注册完怎么挑套餐、用支付宝付款？（附洛杉矶/香港/东京套餐价格表）

DMIT 注册不需要实名认证。一个能收信的邮箱、一个 +86 手机号、姓名拼音、密码，填完提交，去邮箱点一下验证链接，账号就开好了，前后两三分钟。真正卡人的是后面几步：注册完后台提示“个人信息不完整”、买服务器时不知道要勾自动生成 SSH 密钥、付完款找不到登录信息。这篇按注册到开机的顺序讲清楚，套餐和价格放在中间，注册完可以直接对着选。

> **注册完买什么**：个人自用，洛杉矶 Premium 的 TINY 够用，1 核 2GB、20GB SSD、1TB 月流量，年付 $88.88。只需要一个能连的境外节点、预算优先，香港 Tier 1 年付 $36.90 起。拿不定主意先看文末的按需求选择。
> 👉 用支付宝开通洛杉矶 Premium TINY 年付

## DMIT 注册要准备什么

五样东西，都是注册表单上的必填项：

- **邮箱**：填真实能收信的。登录凭证、账单、密码重置、SSH 私钥下载通知都发到这里。
- **姓名**：拼音即可，建议和后面付款用的信息一致，能少一次人工审核。
- **手机号**：国家代码选 +86，后面填 11 位号码。DMIT 不强制验证手机号，格式对就能过。
- **国家/地区**：选 China。
- **密码**：至少 12 位，字母加数字加符号。

DMIT 是海外服务商，注册时不需要上传身份证，也不需要人脸识别。S1 和 S2 两份指南在这一点上说法一致。

## 注册步骤

1. 打开 DMIT 官网，右上角点 **Register**（注册）。页面右上角有地球图标，点开可以切简体中文，填表会顺很多。
2. 填 First Name、Last Name、邮箱、手机号、国家、密码，勾选服务条款和隐私政策。
3. 提交后会收到一封验证邮件，标题类似“Verify your email address”。点邮件里的链接完成验证。
4. 验证完成，账号创建成功，可以直接登录后台。

验证邮件没收到，先翻垃圾邮件文件夹，Gmail 和 QQ 邮箱有时候会误判。还没有就回登录页重新触发一次发送。换过邮箱的用户注意，要用当初注册的那个邮箱收信。

## 注册后提示“个人信息不完整”是怎么回事

这是注册完最容易懵的一步。后台弹出一段英文：

> Your personal information is not complete. Since PayPal and credit cards require customers to provide personal information to prevent fraud...

意思是 PayPal 和信用卡通道有防欺诈要求，客户资料必须补齐。去个人信息页面把姓名、地址、电话填完整就能消除提示。姓名建议用真实拼音，不要填“abc”“test”这类，否则付款环节可能被风控拦下来。这个提示不影响支付宝付款，但资料空着总归是个隐患。

## 注册完在哪买：当前在售套餐与价格

DMIT 的套餐按机房和线路分三档：**Premium** 走中国电信 CN2 GIA 加高端 Transit，国内三网优化最好；**Eyeball** 电信联通走 AS9929、移动走 CMIN2，性价比高一些；**Tier 1** 是标准国际线路，没有专门针对大陆优化。

套餐和价格调整比较频繁，下表按官网公开信息整理，下单前请在购物车核对最终价。所有价格均为税前美元价。

### 洛杉矶（LAX）

| 套餐 | 线路 | CPU / 内存 / 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| TINY | Premium（CN2 GIA） | 1核 / 2GB / 20GB SSD | 1000GB | $88.88/年 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| Pocket | Premium（CN2 GIA） | 2核 / 2GB / 40GB SSD | 1500GB | $159.98/年 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | Premium（CN2 GIA） | 2核 / 2GB / 80GB SSD | 3000GB | $29.90/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| MINI | Premium（CN2 GIA） | 4核 / 4GB / 80GB SSD | 5000GB | $58.88/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | Premium（CN2 GIA） | 4核 / 4GB / 160GB SSD | 7000GB | $74.99/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| TINY | Eyeball（AS9929+CMIN2） | 1核 / 2GB / 20GB SSD | 1500GB | $88.88/年 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| Pocket | Eyeball（AS9929+CMIN2） | 2核 / 2GB / 40GB SSD | 3000GB | $159.98/年 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | Eyeball（AS9929+CMIN2） | 2核 / 2GB / 80GB SSD | 5000GB | $29.90/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| MINI | Eyeball（AS9929+CMIN2） | 4核 / 4GB / 80GB SSD | 10000GB | $58.88/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| V2C2G | Tier 1 | 2核 / 2GB / 40GB SSD | 5000GB | $14.90/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| V2C4G | Tier 1 | 2核 / 4GB / 80GB SSD | 10000GB | $23.90/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| V4C4G | Tier 1 | 4核 / 4GB / 120GB SSD | 20000GB | $36.90/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |

### 香港与东京

| 套餐 | 机房 / 线路 | CPU / 内存 / 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| HKG.T1.TINY | 香港 Tier 1 | 1核 / 0.5GB / 10GB | 400GB | $36.90/年 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| HKG.T1.STARTER | 香港 Tier 1 | 1核 / 1GB / 15GB | 800GB | $58.88/年 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| HKG.T1.MINI | 香港 Tier 1 | 1核 / 1.5GB / 20GB | 1.5TB | $98.88/年 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| HKG.PRO.MICRO | 香港 Premium | 1核 / 0.75GB / 10GB | 300GB | $39.90/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| HKG.PRO.MINI | 香港 Premium | 1核 / 1GB / 15GB | 500GB | $49.90/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| TYO.PRO.POCKET | 东京 Premium | 1核 / 0.75GB / 10GB | 200GB | $14.90/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |
| TYO.PRO.STARTER | 东京 Premium | 1核 / 1.5GB / 20GB | 400GB | $28.88/月 | [ 选购](https://www.dmit.io/aff.php?aff=9081) |

洛杉矶 Premium 和 Eyeball 同价不同量，Eyeball 的月流量给得更多（TINY 是 1500GB 对 1000GB），线路档次低一档。同一个预算下这是个明确的取舍：流量用得多、对晚高峰延迟不敏感，选 Eyeball；三网都要稳，选 Premium。

## 怎么选：四类需求对应四种买法

**自己用，搭个面板、偶尔看看视频。** 洛杉矶 Premium TINY，$88.88/年。1 核 2GB 跑 3X-UI 这类面板绰绰有余，CN2 GIA 在晚高峰的稳定性是它比 Eyeball 贵的那部分钱换来的。

**预算优先，能接受香港线路。** 香港 Tier 1 TINY，$36.90/年，是全场最便宜的入门价。但内存只有 0.5GB，跑面板可以，建站或装数据库会紧张，买之前想清楚用途。

**访客主要在国内，要建站。** 香港 Premium 延迟最低，国内连接通常在 20–50ms，但月付 $39.90 起，价格是洛杉矶的几倍。流量不大、又在意首屏速度，才值得上这个档。

**跑海外业务、流量消耗大。** 洛杉矶 Tier 1 的 V2C2G，$14.90/月给 5TB 流量和 10Gbps 带宽，是这批套餐里单位流量最便宜的。代价是没有大陆优化，国内访问速度一般。

## 支付：支付宝在哪选

结账页的付款方式里有 Credit Card、Alipay、Crypto、Manual Bank Transfer、PayPal。选 **Alipay**，点 Complete Order，页面跳转到支付宝扫码，付完即开通。美元标价按当天汇率换算，没有额外手续费。

计费周期在同一页选。月付没有折扣，季付约 -3.6%，半年付约 -18%，年付约 -26%，两年付和三年付折扣更高。首次购买选年付是常见做法，TINY 年付 $88.88 折下来每月约 $7.4。

👉 到 DMIT 结账页选支付宝付款

## SSH 密钥只能下载一次

DMIT 默认不开密码登录，只能用 SSH 私钥连服务器。下单时 SSH 密钥那一栏要选 **Generate SSH Key after order**（下单后自动生成）。这一步漏了，后面连不上服务器，得回后台重新生成。

服务器开通后，进 **Access** 页面，点 **Change Key**，选 **Auto-generate New Key**，再点 **Download Key**。页面会有一条黄色警告：新密钥只能下载一次，系统不保存。

下载下来是一个 zip，解压后包含 `id_rsa.pem`（私钥）、`id_rsa.ppk`（PuTTY 用）和公钥信息。生成密钥后需要重启实例才会生效，勾选同意关机，点确认，等一两分钟。

macOS 和 Linux 本地设置权限再连接：

bash
chmod 400 id_rsa.pem
ssh -i ~/密钥目录/id_rsa.pem root@服务器IP


权限必须是 400 或 600，644、777 会被 SSH 直接拒绝，报“Permissions too open”。Windows 用 PuTTY 导入 `.ppk` 文件即可。

👉 注册账号并下单开通服务器

## 退款和换 IP 的规则

**退款**：购买后 72 小时内可以申请退款，条件是流量使用不超过 30GB。超过 3 天、30 天以内，按剩余时间和剩余流量比例退。退到原支付方式可能扣手续费，退到账户余额免手续费。提交工单申请。

**换 IP**：IP 确认被墙的情况下，非月付套餐每 15 天可以免费换一次；月付套餐换一次 $5。这条写在官方 TOS 里，不是“看客服心情”。

## 优惠码

目前流传较广的两个循环折扣码：

| 优惠码 | 适用范围 | 折扣 |
| --- | --- | --- |
| `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF` | 洛杉矶 Eyeball，季付及以上 | 终身 8 折 |
| `HKG-T1-ANNUALLY-45OFF-RECUR` | 香港 Tier 1，年付 | 终身 5.5 折 |

在购物车右侧的促销代码框里填入，点验证，价格变了才算生效。月付基本不参与这类折扣。优惠码会轮换，失效时购物车会提示无效，以验证结果为准。

## 常见问题

**注册要实名吗？**
不要。邮箱、姓名、手机号、国家、密码填完即可，不上传证件。

**注册时姓名可以随便填吗？**
技术上可以，但建议用真实拼音。资料不完整或明显虚假时，付款环节可能触发防欺诈审核。

**注册完能马上买吗？**
可以，邮箱验证完就能下单。DMIT 没有试用期，第一次买建议从年付入门套餐开始，风险可控。

**忘记密码怎么办？**
登录页点“忘记密码”，输入注册邮箱，收重置邮件，点链接设新密码，全程不超过 5 分钟。

**能改注册邮箱吗？**
可以，在客户中心个人资料页操作。改完有 10 天冷却期，期间不能再改，需要新旧邮箱都完成验证。

**流量用超了会关机吗？**
不会直接断网，超额后限速，具体速率按套餐而定，下个月流量重置后恢复正常。

## 最后：按你的情况对号入座

只需要一个稳定的自用节点，选洛杉矶 Premium TINY，年付 $88.88，别在配置上多花钱。预算压到最低、能接受 0.5GB 内存，香港 Tier 1 TINY 年付 $36.90。要建站且访客在国内，香港 Premium 的低延迟值这个价。流量消耗大、主要跑海外，洛杉矶 Tier 1 的 V2C2G 最划算。

下单前确认两件事：SSH 密钥那一栏选了自动生成，优惠码在购物车里验证过。密钥只给一次下载机会，付完款先去 Access 页面把它拿到手。

👉 查看 DMIT 全部在售套餐并用支付宝下单
