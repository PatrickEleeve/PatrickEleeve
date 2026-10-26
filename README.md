<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f2027,50:203a43,100:2c5364&text=Patrick%20Pan&fontColor=ffffff&fontSize=56&fontAlignY=36&desc=MSFE%20%40%20UIUC&descAlignY=58&descSize=20&section=header&animation=fadeIn" alt="Patrick Pan" />
</p>

<p align="center">
  <a href="https://github.com/PatrickEleeve">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=3A9BC9&center=true&vCenter=true&width=600&lines=Infra+%C2%B7+Quant+Dev+%C2%B7+Quant+Research+%C2%B7+Quant+Trading;Consensus+%26+audit+protocols+in+Rust;Runtimes+checked+against+TLA%2B+specs;Trading+engines+with+hard+safety+rails" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/UIUC-MS_Financial_Engineering-13294B?style=flat-square&labelColor=E84A27" alt="UIUC MSFE" />
  <img src="https://img.shields.io/badge/Open_to-Infra_%7C_QD_%7C_QR_%7C_QT-2c5364?style=flat-square" alt="Open to Infra, QD, QR, QT" />
  <a href="mailto:lp29@illinois.edu"><img src="https://img.shields.io/badge/lp29@illinois.edu-0f2027?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 🧭 About

I build systems where correctness has to be provable, or at least checkable: consensus and audit protocols, formally specified runtimes, and trading engines with hard safety rails.

### 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,python,ts,cpp,swift,nodejs,tauri,docker,linux,sqlite,git,githubactions&perline=12" alt="Tech stack" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/TLA%2B-formal_specs-4B5563?style=flat-square" />
  <img src="https://img.shields.io/badge/Substrate-blockchain-4B5563?style=flat-square" />
  <img src="https://img.shields.io/badge/gRPC-services-4B5563?style=flat-square" />
  <img src="https://img.shields.io/badge/PyO3-Rust%E2%86%94Python-4B5563?style=flat-square" />
</p>

---

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### ⛓️ FLChain
**Decentralized compute network for federated-learning training**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Substrate](https://img.shields.io/badge/Substrate-4B5563?style=flat-square) ![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square)

- Substrate chain (Aura + GRANDPA, DPoS-elected authorities) with a separate FL proof-of-work path
- Contribution commitments, sampled committee audits, escrow-backed reward settlement
- Verifiable secret sharing over rings + RSA-group integer commitments in Rust, exposed to Python via PyO3
- Masked vector aggregation with threshold unmasking for dropout recovery

</td>
<td width="50%" valign="top">

#### 📐 loxeon-runtime
**Rust runtime that refines a formally verified TLA+ spec**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![TLA+](https://img.shields.io/badge/TLA%2B-4B5563?style=flat-square) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square)

- Kernel transition steps as pure functions
- Single sequencer with an SQLite WAL log and hash-checked replay
- Runtime traces checked against the spec's Init / Next / invariants
- Mutant campaign proves the checks actually catch injected bugs

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🛰️ Fleetroom
**One control plane for coding agents across laptop, Mac mini and cloud VMs**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white) ![tmux](https://img.shields.io/badge/tmux-1BB91F?style=flat-square&logo=tmux&logoColor=white)

- Daemon drives native terminal sessions through tmux
- Web, desktop (Tauri) and phone clients
- Multi-host over Tailscale: QR pairing, automatic TLS, encrypted web push
- Windows support through WSL2

</td>
<td width="50%" valign="top">

#### 📈 [MAPEval](https://github.com/PatrickEleeve/mapeval)
**LLM-driven crypto futures trading research engine**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Binance](https://img.shields.io/badge/Binance_Futures-F0B90B?style=flat-square&logo=binance&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

- Simulation → paper → live modes sharing one execution path
- Kill switch, read-only guard, confirmation phrases, position reconciliation, audit log
- Token-protected monitoring API
- Deterministic offline backtest replay; CI on Python 3.10–3.12 with coverage gating

</td>
</tr>
</table>

<p align="center"><sub>🔒 FLChain, loxeon-runtime and Fleetroom are private — code walkthrough or demo available on request.</sub></p>

#### 🧪 Also building

| Project | What it is |
|---|---|
| **SpawnUI / aide** | Developer tools whose UI is generated from the task context |
| **LocalWhisper** | Native macOS (Swift) on-device speech recognition and transcription |
| **ResearchBT** | Point-in-time research and daily backtesting framework (UIUC MSFE × Context Analytics practicum) |

---

### 📊 Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=PatrickEleeve&theme=dark&hide_border=true&background=0D1117&ring=3A9BC9&fire=3A9BC9&currStreakLabel=3A9BC9" />
    <img src="https://streak-stats.demolab.com?user=PatrickEleeve&hide_border=true&ring=2c5364&fire=2c5364&currStreakLabel=2c5364" alt="GitHub streak" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PatrickEleeve/PatrickEleeve/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/PatrickEleeve/PatrickEleeve/output/github-snake.svg" alt="Contribution snake" />
  </picture>
</p>

---

<details>
<summary><b>🇨🇳 中文简介</b></summary>

<br/>

UIUC 金融工程硕士在读，求职方向：**Infra / 量化开发（QD）/ 量化研究（QR）/ 量化交易（QT）**。

关注需要可验证正确性的系统：共识与审计协议、形式化规约驱动的运行时、带严格风控的交易引擎。

| 项目 | 简介 |
|---|---|
| ⛓️ **FLChain** 🔒 | 面向联邦学习训练的去中心化算力网络。Substrate（Aura + GRANDPA，DPoS 选举验证人）+ 独立 FL-PoW 路径：贡献承诺、抽样委员会审计、托管奖励结算；Rust 实现环上可验证秘密共享与 RSA 群整数承诺，经 PyO3 供 Python 调用 |
| 📐 **loxeon-runtime** 🔒 | 对已形式化验证的 TLA+ 规约做精化实现的 Rust 运行时。纯函数内核、单序列器 + SQLite WAL 日志与哈希校验回放、运行轨迹逐条对照规约检查、变异测试验证检查有效 |
| 🛰️ **Fleetroom** 🔒 | 统一管理本机、Mac mini、云主机上的 coding agent。tmux 驱动原生终端，网页 / 桌面（Tauri）/ 手机三端；Tailscale 多主机互联、扫码配对、自动 TLS 与加密推送 |
| 📈 **[MAPEval](https://github.com/PatrickEleeve/mapeval)** | LLM 驱动的加密货币期货交易研究引擎。模拟 / 纸面 / 实盘共用同一执行路径；熔断开关、只读保护、确认短语、持仓对账、审计日志 |

<sub>🔒 私有仓库，可应邀演示或讲解代码。</sub>

</details>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:0f2027,50:203a43,100:2c5364&section=footer" alt="" />
</p>
