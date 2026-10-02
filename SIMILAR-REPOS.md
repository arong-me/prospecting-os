# 同类仓库追踪（Similar Repos）

目的：GitHub 上与挖矿系统需求相近的仓库清单。每次复扫（search API，多角度关键词）后更新本文件。
元结论（2026-09-25 / 2026-10-02 两轮确认）：**没有完整闭环仓库**（扫描→信号→深挖→浅钻→矿区档案）。赛道是荒漠——没轮子可抄，也没人做出 production 验证。

## 扫描 + 信号层

- **dcrjodle/idea-scanner** (0★, 最后提交 2026-06-29，已停滞)
  https://github.com/dcrjodle/idea-scanner
  CLI：Reddit / HN / Product Hunt / GitHub Trending / YC 抓 trending problems，自带 LLM 打分，输出 ranked Markdown 报告。41 秒跑 229 个信号。支持 Ollama 本地跑。
  对标：扫描层 + 信号打分。可借鉴管线设计。

## 深挖 + 研究层

- **DevChiniwala/CortexOS** (2★, 最后提交 2026-07-02，已停滞)
  https://github.com/DevChiniwala/CortexOS
  自称 AI-native 情报 OS：多 agent 研究公司、分析 market signals、verify insights，强调 verification-first pipeline。
  对标：深挖 + Verifier。可借鉴验证管线思路。
- **SumithShet18/startup-investment-feasibility** (0★)
  https://github.com/SumithShet18/startup-investment-feasibility
  EIPR-Agent：5 个专用 agent 做机会发现、IP 策略、商业计划、财务可行性。
  对标：深挖报告自动化。
- **anubhavdogra1/AgenticAIMarketResearchTeam** (1★)
  https://github.com/anubhavdogra1/AgenticAIMarketResearchTeam
  多 agent 管线：raw market signals → exec-ready 报告。
  对标：深挖管线。
- **ethanstreetsystems/contradictory-intelligence** (1★)
  https://github.com/ethanstreetsystems/contradictory-intelligence
  吞 newsletters / transcripts，抽叙事和结构化信号。
  对标：跨社区信号提取。

## 选矿层（2026-10-02 新发现）

- **ki-sum/evoradar** (2★, 2026-10-02 首次发现)
  https://github.com/ki-sum/evoradar
  Self-evolving AI idea engine：每跑一次生成 ~50 个想法，杀掉 ~40 个并写明杀的理由；杀的过程中提炼 "genes"（结构化本能），下次跑更准。"We're still waiting for the first idea to cross the HOT threshold. The bar is that high."
  对标：选矿层 + 废石区回测（kill with reasons + genes 进化），概念同构。
  ⚠️ All Rights Reserved 协议（非开源），完整分析 VIP 付费——GitHub 只是引流页。思路可借鉴，代码借不到。

## 浅钻验证层

- **dr7034/validation-engine** (0★, 最后提交 2025-06-17，已死）
  https://github.com/dr7034/validation-engine
  结构化验证框架：persona 打分、高信号增长循环、build/exit 标准。
  对标：浅钻探针。概念接近"用低成本探针代替商业计划书"。
- **tokenanki/idea-validator** (0★)
  https://github.com/tokenanki/idea-validator
  React 玩具：Lean Startup 六问打分。玩具级别，仅记录。

## 扫描记录

- 2026-09-25：8 个角度关键词搜索，见 side chat 记录。
- 2026-10-02：复扫，新增 evoradar；其余仓库 star/提交均无实质变化。
