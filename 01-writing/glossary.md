# 术语与符号表

> 全仓唯一口径。写正文时以本表为准，新词先入表再使用。

## 一、术语（中英对照）

| 中文（本文统一用） | English | 缩写 | 说明 |
| --- | --- | --- | --- |
| 低地球轨道 | Low Earth Orbit | LEO | 约 500–2000 km |
| 卫星星座 | satellite constellation | — | 多星协同构型 |
| 轨道根数 | orbital elements | — | 经典六根数见第二节 |
| 星间链路 | inter-satellite link | ISL | |
| 星地链路 | satellite-to-ground link | SGL | |
| 地面站 | ground station | GS | |
| 星上处理 | on-board processing | OBP | |
| 路由 | routing | — | 统一用「路由」，不用「路由选择」 |
| 路由算法 | routing algorithm | — | |
| 流量分配 | traffic allocation | — | 统一用「流量分配」，不用「业务分配」 |
| 负载均衡 | load balancing | LB | |
| 链路切换 | link handover | — | 统一用 handover，不用 handoff |
| 传播时延 | propagation delay | — | |
| 端到端时延 | end-to-end delay | E2E | |
| 拓扑快照 | topology snapshot | — | 离散化后的时变拓扑 |
| 虚拟拓扑 | virtual topology | VT | |
| 软件定义网络 | software-defined networking | SDN | |
| 控制器 | controller | — | |
| 姿态控制 | attitude control | — | |
| 轨道控制 | orbit control | — | |
| 摄动 | perturbation | — | J2、大气阻力等 |
| 地面轨迹 | ground track | — | |

## 二、符号约定

| 符号 | 含义 | 单位 |
| --- | --- | --- |
| $a$ | 半长轴 semi-major axis | km |
| $e$ | 偏心率 eccentricity | – |
| $i$ | 轨道倾角 inclination | deg |
| $\Omega$ | 升交点赤经 RAAN | deg |
| $\omega$ | 近地点幅角 argument of perigee | deg |
| $\nu$ | 真近点角 true anomaly | deg |
| $T$ | 轨道周期 orbital period | s |
| $h$ | 轨道高度 altitude | km |
| $N$ | 卫星数 / 节点数 | – |
| $R_s$ | 星间链路容量 | Mbps |

## 三、单位与数值约定

- 长度用 **km**，不用 m；时间用 **s**，不用 min（除叙述性文字）。
- 角度用 **deg**，公式内部用 rad 时需明确标注。
- 数值与单位之间空一格：`500 km`、`12.5 Mbps`。
- 百分数用 `%`，不用「百分之」；范围用「～」连接：`500～2000 km`。
- 缩写首次出现时给全称：「星间链路（inter-satellite link, ISL）」，后文直接用 ISL。
