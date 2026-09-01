<p align="center">
  <img src="assets/brand/51taoli-logo-horizontal.jpg" alt="51taoli" width="560">
</p>

<p align="center"><strong>把分散在不同市场里的价差、资金费和交易条件，放到同一条研究路径里。</strong></p>

<p align="center">
  <a href="https://51taoli.com/opportunities"><strong>打开官网</strong></a> ·
  <a href="https://t.me/taoli51"><strong>加入官方社群</strong></a> ·
  <a href="https://t.me/news_51taoli"><strong>查看公告</strong></a> ·
  <a href="https://t.me/taoli51_bot"><strong>询问官方小助手</strong></a>
</p>

## 51taoli 是做什么的

51taoli 是一个**只读的全市场套利信息平台**。它把加密货币现货、衍生品和 TradFi/RWA 产品的报价方向、资金费、指数、公告、充提、借贷等信息放在一起，帮助你回答三个问题：

1. 两条腿分别是什么，应该多哪边、空哪边？
2. 页面上的价差只是理论距离，还是具备进一步研究的市场条件？
3. 缺少哪些证据，下一步应该去哪个页面核对？

51taoli **不替你下单，也不连接你的交易所账户执行交易、划转或提现**。

![当前机会总览：同时查看加密货币与 TradFi 路线](assets/interface/opportunities-overview.png)

> 截图用于说明界面结构；资产、报价、数量和状态会随官网实时变化。

## 一条路线怎么读

![从理论价差到可执行价差，再到风险调整净边际](assets/read-route.svg)

- **理论价差**：先用方向正确的 `ask` / `bid` 看两条腿之间的距离；
- **可执行价差**：再看深度、滑点、费率、借贷和可用市场；
- **风险调整净边际**：最后把资金费、退出条件、身份可比性和市场变化纳入自己的判断。

页面上的正数不是收益承诺；证据不足时，页面宁可显示「暂无」。

## 七类路线

![FF、SF、FS、SS、TF、FT、TT 七类路线](assets/route-types.svg)

字母表示两条腿的市场类型，**第一位是做多腿，第二位是做空腿**：

| 代码 | 做多腿 | 做空腿 |
| --- | --- | --- |
| `FF` | 衍生品 F | 衍生品 F |
| `SF` | 加密现货 S | 衍生品 F |
| `FS` | 衍生品 F | 加密现货 S |
| `SS` | 加密现货 S | 加密现货 S |
| `TF` | TradFi/RWA T | 衍生品 F |
| `FT` | 衍生品 F | TradFi/RWA T |
| `TT` | TradFi/RWA T | TradFi/RWA T |

[查看完整概念与公式 →](docs/CONCEPTS.md)

## 现在可以看什么

| 入口 | 适合解决的问题 |
| --- | --- |
| [机会总览](https://51taoli.com/opportunities) | 先按资产和七类路线发现值得继续研究的对象 |
| [交易看板](https://51taoli.com/trade) | 按市场类别、路线、做多所和做空所筛选，并比较报价、资金费和辅助字段 |
| [资金费](https://51taoli.com/opportunities?tab=funding) | 核对原始费率、周期和结算信息 |
| [公告](https://51taoli.com/announcements) · [冲提](https://51taoli.com/deposit-withdraw) · [借贷](https://51taoli.com/lending) | 补充影响进入、持有和退出的市场事实 |
| [指数](https://51taoli.com/indices) | 查看指数、标记价、历史区间和双币种相对关系 |
| [监控](https://51taoli.com/monitor) | 管理套利开差、资金费率、公告、充提、借贷、指数和双币种比率提醒 |
| [策略](https://51taoli.com/playbook) | 浏览 S01–S50 策略目录、开放状态、规则和真实样本 |

![交易看板：按路线和市场筛选后比较两条腿及辅助证据](assets/interface/trade-board.png)

当前只读行情来源包括 **Binance、OKX、Bybit、Bitget、Gate、Hyperliquid、Aster**。这不代表每个交易所的全部产品和辅助字段都已覆盖，实际范围以官网当前页面为准。

## 监控与策略

监控用于盯住一个明确对象和条件；策略用于描述一套可复核的筛选规则。两者都只是信息工具，不会触发交易。

当前策略目录包含 50 条规则：S01、S02 已开放；其余策略会按真实样本积累情况显示「验证中」或「开发中」。状态以官网为准。

![策略目录：区分已开放、验证中和开发中的规则](assets/interface/strategy-catalog.png)

[了解监控与策略 →](docs/MONITORING-AND-STRATEGIES.md)

## 第一次使用

1. 打开 [机会总览](https://51taoli.com/opportunities)，选一个熟悉的资产；
2. 确认路线代码和两条腿的方向；
3. 看开差与清差，再进入交易、资金费、指数或其他证据页；
4. 对照深度、费用、借贷、充提和退出条件，形成自己的判断。

[按步骤读一条路线 →](docs/USE-51TAOLI.md)

## 资料导航

| 想了解什么 | 直接阅读 |
| --- | --- |
| 产品定位、覆盖范围和使用边界 | [产品介绍](docs/PRODUCT.md) |
| FF、SF、FS、SS、TF、FT、TT 与价差公式 | [核心概念](docs/CONCEPTS.md) |
| 官网每个入口解决什么问题 | [产品页面地图](docs/PRODUCT-MAP.md) |
| 当前界面和主要区域怎么读 | [界面导览](docs/INTERFACE.md) |
| 数据来源、时间、身份与「暂无」 | [数据说明](docs/DATA-PRINCIPLES.md) |
| 七类监控和 50 条策略的关系 | [监控与策略](docs/MONITORING-AND-STRATEGIES.md) |
| 登录、权限、机器人与问题反馈 | [常见问题](docs/FAQ.md) |

## 官方入口

- 官网：[51taoli.com](https://51taoli.com/opportunities)
- 社群：[@taoli51](https://t.me/taoli51)
- 公告：[@news_51taoli](https://t.me/news_51taoli)
- 官方小助手：[@taoli51_bot](https://t.me/taoli51_bot)
- 问题反馈：[GitHub Issues](https://github.com/yangshu2087/51taoli/issues/new/choose)

提交反馈前，请先阅读 [安全说明](SECURITY.md)，不要发送密码、私钥、API Key、验证码或 Token。
