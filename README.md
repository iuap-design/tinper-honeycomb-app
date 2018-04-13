# tinper-honeycomb-app 蜂巢小程序

蜂巢小程序还在设想规划阶段。

## 初衷

在面向复杂的企业中后台业务系统的开发中，对端上的挑战越来越来，比较明显而通用的业务诉求是：需要将大量的业务模块或业务子应用快速开发并集成在 portal，而 portal 本身需要具备整个应用的完整基础能力以及对业务子应用或模板的集成能力。

如何能够打破将大而全的业务系统拆分成比较合理、能力遵循业务规划循序渐进的开发和发布，这是对端上的一个考题。

参考目前业内对小程序的模式应用，主要表现为有核心的商业产品作为载体，小程序是打开产品的开放开发能力的一种形式，微信小程序、支付宝小程序、手机百度小程序等。而我们计划要做的蜂巢小程序，不是要做成这些大厂的模式，蜂巢小程序能够将端上的能力收敛并统一对外，能够将小应用和应用平台、diwork等产品对接集成即可。

## 计划


- 应用平台本身是作为运行态产品，需要提供开放的 API 服务和集成的能力
- .honeycomb 目录为蜂巢小程序的公共框架或集成的逻辑，实现本地开发和联调
- app 业务应用的前端代码
- app.json 配置文件，能够提供当前小程序的名称、id、路由信息、依赖情况等，作为一系列 key-value 的方式进行组织。

## 实现

待开发
