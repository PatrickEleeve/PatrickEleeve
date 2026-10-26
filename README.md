## Hi, I'm Patrick Pan 👋

**MS in Financial Engineering @ UIUC** · Looking for **Infra / Quant Developer / Quant Researcher / Quant Trader** roles

I build systems where correctness has to be provable or at least checkable: consensus and audit protocols, formally specified runtimes, and trading engines with hard safety rails.

`Rust` · `Python` · `TypeScript` · `TLA+` · `Substrate` · `gRPC` · `SQLite` · `Docker`

📫 lp29@illinois.edu

---

### Featured projects

**FLChain** — Decentralized compute network for federated-learning training *(Rust · Substrate · Python · gRPC)* 🔒
- Substrate chain (Aura + GRANDPA over DPoS-elected authorities) with a separate FL proof-of-work path: contribution commitments, sampled committee audits (PASS / FAIL / INCONCLUSIVE), escrow-backed reward settlement
- Verifiable secret sharing over rings with integer commitments in RSA groups, implemented in Rust and exposed to Python via PyO3
- Python worker / aggregator services run end-to-end against a live dev node; masked vector aggregation with threshold unmasking for dropout recovery

**loxeon-runtime** — Rust runtime that refines a formally verified TLA+ specification *(Rust · TLA+ · gRPC · SQLite)* 🔒
- Kernel transition steps as pure functions; single sequencer with an SQLite WAL log and hash-checked replay
- Runtime traces are checked against the spec's Init / Next / invariants; mutant campaign verifies the checks actually catch injected bugs

**Fleetroom** — One control plane for coding agents across laptop, Mac mini and cloud VMs *(TypeScript · Node · Tauri · tmux)* 🔒
- Daemon drives native terminal sessions through tmux; web, desktop (Tauri) and phone clients
- Multi-host networking over Tailscale with one-time QR pairing, automatic TLS certificates and encrypted web-push notifications; Windows support through WSL2

**[MAPEval](https://github.com/PatrickEleeve/mapeval)** — LLM-driven crypto futures trading research engine *(Python · Binance Futures · Docker)*
- Simulation → paper → live execution modes sharing one execution path
- Live-path safety: explicit opt-in and confirmation phrases, kill switch, read-only guard, position reconciliation loop, audit logging, token-protected monitoring API
- Deterministic offline backtest replay; CI on Python 3.10–3.12 with coverage gating

<sub>🔒 Private repository — code walkthrough or demo available on request.</sub>

### Also building

- **SpawnUI / aide** — developer tools whose UI is generated from the task context
- **LocalWhisper** — native macOS (Swift) on-device speech recognition and transcription
- **ResearchBT** — point-in-time research and daily backtesting framework (UIUC MSFE × Context Analytics practicum)

---

<details>
<summary><b>中文简介</b></summary>

UIUC 金融工程硕士在读，求职方向：**Infra / 量化开发（QD）/ 量化研究（QR）/ 量化交易（QT）**。

关注需要可验证正确性的系统：共识与审计协议、形式化规约驱动的运行时、带严格风控的交易引擎。

**代表项目**

- **FLChain**：面向联邦学习训练的去中心化算力网络。基于 Substrate（Aura + GRANDPA，DPoS 选举验证人），独立的 FL-PoW 路径负责贡献承诺、抽样委员会审计和托管奖励结算；Rust 实现环上可验证秘密共享与 RSA 群整数承诺，经 PyO3 供 Python 服务调用。🔒
- **loxeon-runtime**：对已形式化验证的 TLA+ 规约做精化实现的 Rust 运行时。内核步骤为纯函数，单序列器 + SQLite WAL 日志与哈希校验回放，运行轨迹逐条对照规约检查，并用变异测试验证检查本身有效。🔒
- **Fleetroom**：统一管理本机、Mac mini、云主机上的 coding agent。tmux 驱动原生终端，支持网页、桌面（Tauri）和手机；基于 Tailscale 的多主机互联、扫码配对、自动 TLS 证书与加密推送。🔒
- **[MAPEval](https://github.com/PatrickEleeve/mapeval)**：LLM 驱动的加密货币期货交易研究引擎。模拟 / 纸面 / 实盘三种模式共用同一执行路径；实盘有确认短语、熔断开关、只读保护、持仓对账和审计日志。

<sub>🔒 私有仓库，可应邀演示或讲解代码。</sub>

</details>
