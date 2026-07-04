---
{"dg-publish":true,"permalink":"/02-projects/petroleum-engineering/drafts/2026-07-04-conventional-recovery-methods/","tags":["type/project-note","status/learning","area/oil-and-gas","project/petroleum-engineering","source/coursera"],"dg-note-properties":{"type":"project-note","status":"learning","area":["oil-and-gas"],"project":["petroleum-engineering"],"source":["coursera"],"tags":["type/project-note","status/learning","area/oil-and-gas","project/petroleum-engineering","source/coursera"],"aliases":["Oil Recovery Methods Conventional Methods","常规采收方法"],"created":"2026-07-04","updated":"2026-07-04"}}
---


# Draft — 常规采收方法（Conventional Methods）

> [[02_Projects/Petroleum-Engineering/Drafts/PE Drafts Home\|PE Drafts Home]] · 由 inbox 整理 · 维护见 [[02_Projects/Petroleum-Engineering/PE Learning Ops\|PE Learning Ops]]

## Source

- Coursera：*Hydrocarbon Exploration and Production*
- [Oil Recovery Methods - Conventional Methods](https://www.coursera.org/learn/hydrocarbon-exploration-and-production/lecture/mrXoF/oil-recovery-methods-conventional-methods)
- 接在 [[02_Projects/Petroleum-Engineering/Drafts/2026-07-04-intro-oil-recovery\|2026-07-04-intro-oil-recovery]] 之后

## Module

- [[02_Projects/Petroleum-Engineering/Course Maps/PE-M1-Reservoir-and-Waterflood\|PE-M1-Reservoir-and-Waterflood]]（M1.1–M1.2：为什么要注水、驱替与效率）

## In My Own Words

### 1. 常规 vs 非常规（这节的主线）

**常规（conventional）**：多用于渗透性较好、有一定天然压力的油藏；靠维持压力或改变流体性质来驱油（一次 / 二次 / 三次都可算在「常规手段谱系」里讲）。

**非常规（unconventional）**：针对低渗透地层（页岩、油砂等）；往往要**造缝**或**加热**才能让油动起来。

课里强调：常规 / 非常规的划界会因地区和油藏而异，技术发展后分类也可能变。

### 2. 三档采收（补细节）

| 档 | 做法 | 本课补充 |
|---|---|---|
| 一次 | 天然压力推油到井筒 | 压力下降后产量跟着掉 |
| 二次 | 注水或注气，维持/提高压力并驱油 | **注水 + 注气（CO₂ / 天然气）** 都算常见二次手段 |
| 三次 / EOR | 改变油藏条件再多采 | 本课把 **tertiary recovery 与 EOR 当作同一档**；热采、化学驱、注气提高波及 |

上一节问过「EOR 是不是三次采油」→ **按本课：是同一档的两种叫法。**

### 3. 非常规手段（点名四种）

1. **水力压裂**：高压流体（水 + 化学剂 + 砂）压开低渗岩层裂缝  
2. **SAGD（蒸汽辅助重力泄油）**：油砂沥青；一口水平井注蒸汽降黏，平行井采出  
3. **火烧油层（in-situ combustion）**：稠油；点燃一部分油，燃烧前缘加热降黏  
4. **CO₂ 注入**：降黏、使油膨胀、提供压力支持（非常规语境下也谈）

### 4. 常规方法的局限（和 InjectWatch 最相关的几条）

1. **产量递减**：天然压力掉 → 必须上二次 / 三次  
2. **采出比例有限**（本课用 **OOIP** 口径）：  
   - 一次大约 **10%–30% OOIP**  
   - 二次大约再采 **10%–20% OOIP**  
   - 地下仍剩很多油  
   - ⚠️ 与导论视频「一次约 5%–15%」数字不一致，先并存，以 OOIP 定义为准，以后教材再校准  
1. **高含水**：注水驱油时，水会和油一起采出，**水油比（WOR）** 升高，水处理成本高  
2. **波及效率有限（sweep efficiency）**：油藏非均质、渗透率差异、注入流体窜流 → 有的区域驱到了，有的绕过去了，油剩在地下  
3. 环境、投资、油价、常规储量枯竭等（了解即可）

→ 对 InjectWatch：**注水是二次采油主力，但工程上天然就有「注了水却驱不匀、出水多」等问题**；日报异常检测是在这个背景下盯注水井行为。

### 5. 量化术语与公式精讲（本课后半）

课里字幕把公式念得很乱。下面按行业标准体积法重写。

**参考（2026-07-04 已 HTTP + 主题复查；命名链接，无裸 URL）：**

| 链接                                                                                                      | 用途                         |
| ------------------------------------------------------------------------------------------------------- | -------------------------- |
| [Wikipedia · Oil in place](https://en.wikipedia.org/wiki/Oil_in_place)                                  | OOIP / STOIIP、体积法思路、地面校正   |
| [EIA · OOIP 定义](https://www.eia.gov/tools/glossary/index.php?id=O#orig_oil_in_place)                    | 官方一句话定义                    |
| [EIA · Oil FVF](https://www.eia.gov/tools/glossary/index.php?id=F#oil_form_vol_fac)                     | $B_o$（地层体积 / 地面体积）         |
| [Discovery Geo · 体积估算 PDF](https://www.discoverygeo.com/resources/Papers/Reservoir-Eng-for-Geos-03.pdf) | OOIP 体积公式（公制写法）短文          |
| [Wikipedia · Oil reserves](https://en.wikipedia.org/wiki/Oil_reserves)                                  | reserves（可采）与 in-place 的区分 |

#### 5.1 先搞清在算什么

工程师要回答两件不同的事：

| 问题 | 国际常见说法 | 国内常见说法 | 白话 |
|---|---|---|---|
| 地下**原来有多少油**？ | OOIP / STOIIP / PIIP（in-place） | **（原始）地质储量**（容积法算出） | 「油罐」里一开始装了多少油 |
| 其中**技术上能采多少**？ | recoverable resource（还不是 reserves） | **技术可采储量** | 技术上预计能采出多少 |
| 其中**经济上能采多少**？ | **reserves**（PRMS/SEC 核心） | **经济可采储量** / 剩余经济可采 | 在现行经济条件下能采、能报的 |

Coursera 说的「一次采出约 10%–30% OOIP」= 相对**原地量 / 地质储量**的比例。  
**处境盲点：** 英文论文里的 *reserves* **不等于**中文口头里常说的「储量」——国内「储量」常先指**地质储量**（in-place），国际 *reserves* 多指**经济可采**。混用会把「地下有多少」和「能卖多少」搅在一起。

#### 5.2 为什么不能直接量「地下有多少桶」？

油藏不是空罐子，而是**多孔石头**：

1. 石头总体积里，只有一部分是**孔隙**（能装流体）→ **孔隙度 $\phi$**
2. 孔隙里不全是油，还有**束缚水** → **含水饱和度 $S_w$**；油（烃）占的是 $1 - S_w$
3. 地下又热又高压，油里溶着气；采到地面后气跑出来，**油体积会缩小** → 要用 **原油体积系数 $B_o$** 把「地下体积」换成「地面油罐体积」

所以体积法是**四步乘法/除法**，不是一个神秘黑箱。

#### 5.3 物理一样，包装不同：英美教材 vs 国内容积法

**物理核心（中外一致）：**

$$
\text{地面油量} \propto \frac{\text{岩石体积} \times \phi \times S_o}{B_{oi}}, \quad S_o = 1 - S_w \quad (\text{无自由气时})
$$

差别在：**单位制、换算常数、饱和度怎么写、结果报体积还是质量、以及「储量」一词指哪一层。**

##### A. 英美教材常见写法（本课 / SPE 教材路线）

$$
N = \frac{7758 \, A \, h \, \phi \, (1 - S_w)}{B_{oi}}
$$

| 符号 | 含义 | 典型单位 |
|---|---|---|
| $N$ | OOIP / STOIIP | **STB**（地面油罐桶） |
| $7758$ | acre·ft → barrel | 纯单位换算 |
| $A$ | 含油面积 | **acre** |
| $h$ | 有效厚度（net pay） | **ft** |
| $\phi$, $S_w$ | 孔隙度、含水饱和度 | **小数**（0.2 = 20%） |
| $B_{oi}$ | 初始原油体积系数 | rb/STB，无量纲比 |

##### B. 国内一般用法（容积法，行业规范思路）

国内把这套方法叫 **容积法**（不是「体积法」口头乱叫时也有人混用，规范用语是容积法）。思路与 OOIP 相同，但教材/储量报告里常见：

$$
N = 100 \, A \, h \, \phi \, S_o / B_{oi}
$$

（常数、百分数/小数约定以现行规范附录为准；见行业标准 **DZ/T 0217**《石油天然气储量估算规范》容积法条款。）

| 符号 | 国内常见说法 | 典型单位（与英美对照） |
|---|---|---|
| $N$ | **原油地质储量** | 常报 **$10^4\,\mathrm{m}^3$**，或乘地面密度 $\rho_o$ 报 **$10^4\,\mathrm{t}$（万吨）** |
| $100$ | 单位换算系数 | 对应 $A$ 用 $\mathrm{km}^2$、$h$ 用 m、$\phi$/$S_o$ 用**百分数**等组合时的系数（**不是** 7758） |
| $A$ | 含油面积 | **$\mathrm{km}^2$**（不是 acre） |
| $h$ | 有效厚度 | **m**（不是 ft） |
| $\phi$ | 有效孔隙度 | 报告里常写 **%**，公式里要注意是百分数还是小数 |
| $S_o$ | **原始含油饱和度** | 国内公式更常直接写 $S_o$，而不是 $(1-S_w)$ |
| $B_{oi}$ | 原始原油体积系数 | 无因次，含义与国际一致（地层体积/地面体积） |
| $\rho_o$ | 地面原油密度 | 要把体积地质储量换成**质量**万吨时用 |

**一致处：** 都是「孔隙里的油 → 除以 $B_o$ → 地面量」。  
**不一致处（处境，不是翻译）：**

| 维度 | 国际课/论文常见 | 国内现场/储量报告常见 |
|---|---|---|
| 单位 | STB, acre, ft, psi, bbl/d | $\mathrm{m}^3$, $\mathrm{km}^2$, m, MPa, $\mathrm{m}^3/\mathrm{d}$ 或 t |
| 饱和度写法 | 常写 $(1-S_w)$ | 常写 $S_o$（含油饱和度） |
| 「储量」指什么 | *reserves* ≈ 经济可采 | 「地质储量」= in-place；另有技术可采、经济可采 |
| 分类体系 | PRMS / SEC（项目、商业性） | 国标资源/储量分类（探明/控制/预测 × 地质→技术可采→经济可采） |
| 你读的课 | Coursera 英制公式 | 国内报告、InjectWatch 日报：**公制现场量** |

**对 InjectWatch：** 日报里的注水量、压力应按**国内现场单位**理解（如 $\mathrm{m}^3$、MPa），不要默认 STB/psi；地质储量公式本身很少直接进异常检测，但「欠注 / 配注」讨论的是公制配产语境。

用「海绵」类比：

- $A \times h$：整块海绵有多大  
- $\times \phi$：海绵里空隙有多少  
- $\times (1-S_w)$：空隙里有多少是油（不是水）  
- $\div B_{oi}$：油拿到地面缩小后，相当于多少罐装油  
- $\times 7758$：只是单位从 acre·ft 换成 barrel  

#### 5.4 一个最小数字例子

假设：$A = 100$ acre，$h = 20$ ft，$\phi = 0.20$，$S_w = 0.30$，$B_{oi} = 1.25$。

1. 岩石体积 $A h = 2000$ acre·ft  
2. 孔隙体积 $= 2000 \times 0.20 = 400$ acre·ft  
3. 含油孔隙 $= 400 \times (1-0.30) = 280$ acre·ft（地下油体积）  
4. 换成桶：$280 \times 7758 = 2{,}172{,}240$ 地下桶当量  
5. 换成地面油罐桶：$N = 2{,}172{,}240 / 1.25 \approx 1{,}737{,}792$ **STB**

若一次采收率按 20% OOIP，大约能采 $0.2 \times N \approx 35$ 万 STB——这就是「一次只能采一小部分」的量化说法。

#### 5.5 $B_o$ 为什么要除？（最容易懵的一点）

地下：高压高温，天然气**溶解在油里**，油体积偏大。  
地面：压力降下来，气从油里跑出来，**油体积变小**。

定义（直观版）：

$$
B_o = \frac{\text{地层条件下的油体积}}{\text{地面标准条件下的油体积}} \quad (\text{rb/STB})
$$

所以 $B_o = 1.25$ 表示：地下 1.25 桶「胖油」→ 地面只剩 1 桶稳定原油。  
算 OOIP（地面口径）时必须 **除以 $B_o$**，否则会把地下的「虚胖」当成能卖的油。

$B_o$ 来自 PVT 化验或相关图版，不是现场随便估的；课里提到的经验式只是粗算，不必死记。

#### 5.6 饱和度：$S_w$、$S_o$、$S_g$

孔隙里的流体比例加起来为 1：

$$
S_o + S_w + S_g = 1
$$

- 只有油+水、没有自由气时：$S_g = 0$，含油饱和度 $S_o = 1 - S_w$（课里的 $S_h$ 在这种情况下就是 $S_o$）  
- 有**气顶**时，孔隙里还有自由气 $S_g$，公式要改成用 $S_o$，不能简单写 $1-S_w$ 就完事  

课里字幕把 $S_h = S_o + S_g$ 说得很乱：**有自由气时，OOIP 只算油相 $S_o$，不算气**；气另外用 OGIP（original gas in place）算。

#### 5.7 气藏公式（了解即可）

气在地面会**膨胀**（和油缩小相反），所以用气体体积系数 $B_g$，思路平行：

$$
\text{OGIP} \propto \frac{V \, \phi \, S_g}{B_g}
$$

英制里 1 acre·ft = **43,560 ft³**（课里这个数是对的）。气的结果常报 scf（标准立方英尺），不是 STB。

#### 5.8 溶解气油比 $R_s$

$$
R_s = \frac{\text{溶解在油里的气量}}{\text{地面油量}} \quad (\text{常见单位 scf/STB})
$$

回答的是：「每采出 1 桶地面油，原来油里溶了多少气？」  
它出现在物质平衡、气油比分析里；**算静态 OOIP 体积法时，主公式用的是 $B_o$ 和 $S_w$，不是 $R_s$。** 课里顺带提 $R_s$，容易让人以为 OOIP 公式里也有它——没有。

#### 5.9 水驱后还剩多少油？（$S_{or}$）

天然水驱（边水 / 底水）或人工注水之后，岩石孔隙里仍会剩一层油，叫 **残余油饱和度 $S_{or}$**。

课里大意是：水驱结束时，剩余油量仍可用体积法估算，只是把含油饱和度换成 $S_{or}$（并注意用当时的 $B_o$）。直觉：

$$
\text{水驱后剩余油（地面口径）} \propto \frac{V \, \phi \, S_{or}}{B_o}
$$

这解释了为什么二次采油之后地下还有很多油——**不是驱不干净就没油了，而是物理上会剩 $S_{or}$**，后面才上 EOR。

#### 5.10 和本课「采收比例」怎么接上

| 说法 | 公式语言 |
|---|---|
| 一次采出约 10%–30% OOIP | 采出量 $\approx (0.10\sim 0.30)\, N$ |
| 二次再采约 10%–20% OOIP | 在一次基础上再采 $(0.10\sim 0.20)\, N$ |
| 仍剩大量油 | 与波及效率、$S_{or}$、经济极限有关 |

**InjectWatch 不直接算 OOIP**；但「注水是为了多采出 OOIP 里那一部分」是整个项目的工程背景。

#### 5.11 课里字幕容易误导的点（对照表）

| 字幕听感 | 标准理解 |
|---|---|
| 「quantity of poor sizes」 | **porosity**（孔隙度），不是 poor |
| 「$V \phi S_h$ 就是最终答案」 | 那是**地下**含油体积；地面 STB 还要 **$/ B_{oi}$** |
| 「BBL STO / STB」 | 同一类东西：地面油罐桶 |
| 溶解气公式和 OOIP 搅在一起 | $R_s$ 是另一条线；体积法 OOIP 主式不含 $R_s$ |
| 气顶时 $S_h$ 说法混乱 | 算油用 $S_o$；气另算 OGIP |

## Key Terms

| 术语（中/英） | 我现在的理解 | 仍不确定？ |
|---|---|---|
| conventional recovery | 常规油藏上的采收手段谱系 | 与「仅指一次+二次」是否严格等同 |
| tertiary recovery | 本课 = EOR | 行业是否总这样用 |
| OOIP / 地质储量 | 原地有多少油；英美 STB 公式 vs 国内容积法公制 | 国内报告具体常数与百分数约定 |
| porosity $\phi$ | 孔隙占岩石体积比例（小数） | 有效孔隙度 vs 总孔隙度 |
| $S_w$ / $S_o$ / $S_g$ | 水/油/气饱和度，三者之和为 1 | — |
| $B_o$ | 地下油体积 / 地面油体积（>1，要除） | PVT 怎么做（以后） |
| STB | 地面油罐桶 | 与 sm³ 换算（以后） |
| $R_s$ | 每桶地面油对应的溶解气量 | 物质平衡里怎么用 |
| sweep efficiency | 注入流体扫过油藏的均匀程度 | 如何从日报间接反映 |
| WOR | 产出液中水油比 | 现场指标名 |
| $S_{or}$ | 水驱后残余油饱和度 | |
| SAGD | 蒸汽辅助重力泄油（油砂） | 本项目暂不优先 |
| in-situ combustion | 火烧油层 | 本项目暂不优先 |
| gas injection | 注气；二次手段之一 | 与 EOR 注气如何划界 |
| water drive | 天然水驱（边水/底水） | 与人工注水的关系 |

> 已写入 [[04_Resources/Oil-and-Gas/PE Glossary\|PE Glossary]]。

## Open Questions

- [x] OOIP 与 reserves 怎么区分？→ OOIP = 原来有多少；reserves ≈ 能采多少（OOIP × 采收率等）
- [x] 7758、$B_o$ 标准写法？→ 见 §5.3；参考 Wikipedia / EIA / Discovery Geo PDF（链接已实测）
- [ ] 二次注气 vs EOR 注气的行业划界
- [ ] 波及效率差时，注水井日报上可能出现什么模式？（接到 InjectWatch，仅作问题，不下结论）
- [ ] 有效厚度 $h$、含油面积 $A$ 在实际油田怎么圈定

## InjectWatch Link（可选）

- 相关？**是**
- 备注：高含水、波及不均是注水开发的固有难点；检测「注水井行为异常」是在二次采油工程背景下的问题。→ [[02_Projects/InjectWatch/InjectWatch Home\|InjectWatch Home]]

## Promote Checklist

- [x] **词典** → [[04_Resources/Oil-and-Gas/PE Glossary\|PE Glossary]]
- [x] 公式精讲写入本草稿 §5（参考链接已实测可打开）
- [ ] 概念 / 公式 → 原子笔记（可选；§5 已够用可暂不拆）
- [x] 挂到 Course Map → [[02_Projects/Petroleum-Engineering/Course Maps/PE-M1-Reservoir-and-Waterflood\|PE-M1-Reservoir-and-Waterflood]]
- [x] InjectWatch 领域链接

已升级到：

- [[04_Resources/Oil-and-Gas/PE Glossary\|PE Glossary]]
- 本草稿 §5 公式精讲

## Raw Capture

- 课程页：[Coursera · Conventional Methods](https://www.coursera.org/learn/hydrocarbon-exploration-and-production/lecture/mrXoF/oil-recovery-methods-conventional-methods)
- 含：conventional vs unconventional 对比表、常规局限列表、OOIP 体积公式口述
<details>
<summary>课程转录原文</summary>




Hello, learners. Welcome to ​this topic on Oil Recovery Methods. ​The conventional methods first. ​At the end of this topic, ​you will be able to discuss ​various conventional recovery mechanisms and ​their effects on overall performance of oil reservoirs, ​explain the drawbacks of conventional methods of ​oil recovery against ​unconventional or enhanced recovery methods. ​Each oil and gas source is represented by ​a common feature of a particular structure arrangement, ​rock properties, different liquids, ​and some drive it already ​has yet no two deposits of oil are ​precisely similar all around and they can be ​classified in the view of ​essential recovery method used for the production. ​Each drive mechanism has been found to have ​some standard performance characteristics ​like ultimate recovery factor, ​pressure decline rate, gas-oil ratio, ​and water for production that can ​be measured using the three methods. ​In primary recovery, the method relies on ​the natural pressure within ​the reservoir to drive oil to the well bore. 

​As the reservoir pressure decreases over time, ​the oil flow diminishes, ​making primary recovery less efficient. ​In secondary recovery, ​techniques involve injecting fluids, water, ​or gas into the reservoir to maintain or increase ​reservoir pressure and ​displace oil towards production wells. ​The most common secondary recovery methods ​include water flooding and gas injection, ​it can be carbon dioxide or natural gas ​whereas in tertiary recovery or enhanced oil recovery, ​the method aims to extract ​additional oil by altering the reservoir conditions. ​The most common enhanced oil recovery techniques ​include thermal methods or ​the steam injection to reduce oil viscosity, ​chemical methods such as polymer or ​surfactant injection to improve oil displacement, ​and gas injection for enhanced reservoir sweep. ​Moving on to unconventional methods of oil recovery, ​the various methods are hydraulic fracturing, ​steam-assisted gravity drainage or SAGD, ​in-situ combustion, and CO_2 injection. ​Let us discuss them in detail here. ​The first method is hydraulic fracturing or fracking, ​which is used to extract oil from ​low-permeability rock formations, such as shale. 

​It involves injecting a high-pressure fluid, ​usually water mixed with chemicals and ​sand to create fractures in the rock, ​allowing oil and gas to flow more freely. ​The next method is steam-assisted gravity drainage, ​which is commonly used for ​extracting bitumen from oil sands. ​It involves injecting steam ​into a horizontal well to heat ​the bitumen reducing its viscosity and allowing ​it to flow towards a parallel production well. ​In in-situ combustion, ​this method is used for heavy oil recovery. ​It involves igniting a portion ​of the oil itself in the reservoir, ​creating a combustion front that heats ​the oil and reduces its viscosity, ​enabling it to flow to the production wells. ​Finally, carbon dioxide injection. ​CO_2 can be injected into ​unconventional reservoirs to enhance ​oil recovery by reducing oil viscosity, ​swelling the oil, ​and providing pressure support. 

​Unconventional methods may use ​a combination of different methods ​to enhance the recovery. ​Conventional and unconventional methods ​of oil recovery differ in ​terms of the technique used and ​the type of reservoir they are targeted. ​Scroll the table to learn more about it. ​It is important to note that ​classification of methods as conventional ​or unconventional can vary depending on ​the region and the specific characteristics ​of the reservoir. ​Additionally, advancements in ​technology and ongoing research may lead to ​the development of new techniques and the ​re-classification of certain methods ​over the period of time. ​Conventional methods of oil recovery ​have certain drawbacks and limitations. ​To address these limitations, ​the industry continues to explore ​and develop innovative techniques and technologies like ​unconventional oil recovery methods and ​advanced UR techniques to maximize ​oil extraction from conventional reservoirs. 

​Moving on to the terminologies commonly used in ​oil recovery methods along ​with mathematical expressions related to it. ​With that knowledge, we are going ​to solve a problem later. ​Here are the terminologies ​and equations used to represent ​the quantification of oil and gas in place as well as ​recovery efficiency which is ​the volumetric equation for ​original oil in place that is OOIP. ​The capacity of original oil in place ​OOIP in a particular section ​can be given by this formula, ​which is volume of oil is equal ​to quantity of poor sizes, ​multiplied by quantity of ​hydrocarbon minus quantity of water present there. ​This expression can be re-written as OOIP, ​which is equal to V_o, ​equal to V phi multiplied by S_h, ​where V is specified ​volume of reservoir measured in acre feet. ​Phi is the porosity percentage ​of void spaces in that volume V. ​S_h is nothing but ​hydrocarbon saturation as a percent of fluid content, ​which is also equal to 1-S_w, ​where S_w is the water saturation ​as a percent of fluid content, ​which is equal to S_o+S_g ​if there is a free gas cap present there. 

​In practical use, the equation is as shown here. ​BBL STO is also written as STB here. ​Here, the value of 7,758 is nothing ​but a factor considered to ​convert from acre feet to barrels, ​and BO is a factor to convert ​the fluid volume at reservoir pressure and ​temperature to stock tank barrels. ​Also, BBL STO or STB is nothing but ​barrels of stock tank oil ​or stock tank barrel respectively. ​In the gas reservoir, ​it can be free gas or gas gap. ​We can write the volume of gas in place, ​similar to oil in place as follows, ​where one acre feet is equal to 43,560 cubic feet. ​The gas formation volume factor, ​BG might be assessed ​for different situations of pressure, ​temperature, and gas gravity ​from data that is already been published. 

​Dissolved gas content in ​any oil reservoir can ​also be calculated using the equation, ​where RS, which is we have seen ​previously is the quantity of entrained gas. ​Please note that this is calculated at ​the reservoir conditions and not the surface conditions. ​For volumetrically control oil reservoirs, ​there is no water influx. ​The formed oil must be exchanged by ​gas mixtures whose saturation ​rises as the saturation of oil declines, ​where SG is the gas saturation and BO is ​the oil formation volume factor at abandoned pressure. ​The oil in place at ​abandoned pressure is given by this formula. ​V is equal to the factor 7758 multiplied by ​V phi multiplied by 1-S_w-S_g /B_oi. ​In general, there can be ​water influx as drive mechanism for oil recovery. 

​This water drive can be ​the edge water drive or bottom water drive. ​This drives in oil reservoirs under ​hydraulic control where reservoir pressure ​does not significantly drop, ​which is close to initial reservoir pressure. ​In the bottom water drive, ​the water flood is upside. ​The produced oil region is triggered by water here. ​Now the oil quantities present ​are calculated using this formula, ​which is V is equal to the factor ​7758 multiplied by V phi multiplied by ​S_or divided by B_oi where S_or ​is the residual oil saturation after the water flood. ​Now, let us summarize all that you have learned so far. ​Various unconventional methods ​which are hydraulic fracturing, ​steam assisted gravity drainage in ​C_2 combustion and carbon dioxide injection. 

​Various conventional and unconventional methods ​of oil recovery that differ ​in terms of techniques which are used ​and the types of reservoir they are really targeted. ​The terminologies and equations used to ​represent the quantification of oil and gas in place, ​as well as recovery efficiency is ​the volumetric equation for ​original oil in place that is OOIP that we have seen, ​dissolved gas content, et cetera. ​Hope you have understood this session. ​Let us meet again for another interesting session. ​Thank you and take care.
</details>

---

## Template Index

- [[00_Home/Template Map\|Template Map]]
- [[04_Resources/Oil-and-Gas/PE Glossary\|PE Glossary]]
- [[02_Projects/Petroleum-Engineering/Drafts/PE Drafts Home\|PE Drafts Home]]
- [[02_Projects/Petroleum-Engineering/Petroleum Engineering Home\|Petroleum Engineering Home]]
- [[00_Home/Study Map\|Study Map]]
