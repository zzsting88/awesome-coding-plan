# awesome-coding-plan


> 信息整理时间：2026-05。套餐价格、模型列表、限购状态和计费规则变化很快，购买前请以平台官网为准。

## 选型原则

- 高频日常开发：优先选 Coding Plan。
- 低频零散使用：优先走 API 按量付费，或使用免费额度, 或者看中转站. 可以去 [hvoy.ai](https://hvoy.ai)上找合适的中转站

- 需要顶级代码质量：看GPT系列, 和 Claude系列
- 预算敏感(会翻墙)：GPT系列, 不二之选. 同等价格最强
- 预算敏感(不翻墙)：阿里云百炼和GLM

## 简单推荐

| 使用场景 | 推荐 |
| --- | --- |
| 只要最好的码质量 | Claude系列|
| 要求代码质量, 但是不想太折腾 | GPT系列|
| 追求国产模型代码质量 | 智谱 AI Pro / Lite；抢不到看阿里云百炼 |
| 预算有限但高频使用 | MiniMax Starter / Plus |
| 需要多模型切换 | 阿里云百炼 Pro、OpenCode GO |
| 不想抢购 | MiniMax、Kimi、讯飞星辰、OpenCode GO |
| 学生开发者 | GitHub Copilot Student；预算备用选 MiniMax Starter |
| 低频偶尔使用 | 不建议订阅，优先 API 按量付费或免费额度 |
| 政企 / 信创 / 合规 | 电信天翼云、腾讯云、联通云等国内云厂商套餐 |

## Coding Plan 套餐对比

| 平台 / 套餐 | 价格 | 提供模型 | 优点 | 缺点 | 备注 |
| --- | --- | --- | --- | --- | --- |
| GPT Plus | 土区约 ¥80/月 | GPT-5.5、GPT-5.4、gpt-image-2 | 写代码能力略逊于 Claude，但也足够强；综合能力全面；还能使用图像生成 | 需要翻墙 | 有一定封号风险 |
| GPT Pro 5x | 美区约 ¥700/月 | GPT-5.5、gpt-image-2 | 个人基本用不完，可以使劲用；基本不会限速；3-5 个人共用问题不大，平摊后不算贵 | 需要翻墙 | 无 |
| Claude Pro | 尼区约 ¥80/月 | Opus 4.7 | 目前最强模型，代码能力和复杂推理很强 | 额度不如 GPT 多，不小心就用完；有封号风险；需要翻墙 | 折腾挺费劲 |
| Claude Code Max 5x | 尼区约 ¥500/月 | Opus 4.7 | 约 8 倍 Pro 额度；适合高频 Claude Code 用户 | 封号, 翻墙 | 重度 Claude Code 用户考虑 |
| [智谱 AI Lite](https://www.bigmodel.cn/glm-coding) | 首月 ¥46.55；连续包月 ¥49/月 | GLM-5.1、GLM-5-Turbo 等 | 国产代码能力第一梯队；Lite 每月约 24,000 次请求；适合日常高频开发 | 全面限购，通常每日 10:00 抢购，热门时段很快售罄 | 不好抢 |
| [阿里云百炼 Pro](https://cn.aliyun.com/benefit/scene/codingplan) | ¥200/月 | GLM-5.1、Kimi-K2.6、Qwen3.7-Max、MiniMax-M2.5、DeepSeek-V4-Pro 等 | 模型很全；千问生态强；Qwen 长上下文和中文项目理解能力突出 | 配置复杂；Lite 已停售；Pro 每日 9:30 限量，基本上线秒光 | 模型多, 值得试下 |
| [智谱 AI Pro](https://www.bigmodel.cn/glm-coding) | 首月 ¥141.55；连续包月 ¥149/月 | GLM-5.1、GLM-5-Turbo 等 | 代码生成、调试、重构能力强；每月约 120,000 次请求 | 很难抢；国际版价格上涨后性价比下降 | 专业开发者首选之一 |
| [智谱 AI Max](https://www.bigmodel.cn/glm-coding) | 首月 ¥445.55；连续包月 ¥469/月 | GLM-5.1、GLM-5-Turbo 等 | 额度很大，每月约 480,000 次请求；适合团队或企业高频使用 | 价格高，也需要抢购 | 企业级或重度 Agent 用户考虑 |
| [MiniMax Starter](https://platform.minimaxi.com/subscribe/token-plan) | 首月 ¥26.10；连续包月 ¥29/月 | MiniMax-M2.7 等 | 价格低；不限购；每月约 24,000 次请求；响应速度快 | 模型智力和代码质量通常弱于 GLM、Kimi | 预算有限、学生、日常轻中度开发可选 |
| [MiniMax Plus](https://platform.minimaxi.com/subscribe/token-plan) | 首月 ¥44.10；连续包月 ¥49/月 | MiniMax-M2.7 等 | 每月约 60,000 次请求；性价比高；购买门槛低 | 复杂工程任务表现不如第一梯队模型 | 高频但预算敏感时可选 |
| [MiniMax Plus 极速](https://platform.minimaxi.com/subscribe/token-plan) | 首月 ¥88.20；连续包月 ¥98/月 | MiniMax-M2.7 等 | TPS 更高，适合并发和快速响应场景 | 核心模型能力仍不是最强 | 更看重速度和稳定吞吐时考虑 |
| [Kimi Andante](https://www.kimi.com/code) | ¥49/月 | Kimi-K2.6 等 | 多模态和 Agent 能力突出；支持图像输入；Agent 运行更快 | 官方未公开具体请求额度；低档位可能不够真实开发使用 | 适合轻量 Agent、多模态前端生成 |
| [Kimi Moderato](https://www.kimi.com/code) | ¥99/月 | Kimi-K2.6 等 | 额度比低档更充足；支持 Agent 多任务并行 | 价格高于 MiniMax、讯飞等低价方案 | 中度开发可考虑 |
| [Kimi Allegretto](https://www.kimi.com/code) | ¥199/月 | Kimi-K2.6 等 | 智力接近 GLM；比 MiniMax 更适合真实开发；含免费 Kimi-Claw | 价格较高；额度规则不够透明 | 不想抢 GLM 时的强替代 |
| [Kimi Allegro](https://www.kimi.com/code) | ¥699/月 | Kimi-K2.6 等 | 高额度；适合复杂 Agent 和团队级任务 | 价格很高 | 重度团队或企业场景考虑 |
| [火山方舟 Lite](https://volcengine.com/L/crEuY2bBw3I/) | 首月约 ¥36；连续包月约 ¥40/月 | GLM-5.1、Kimi-K2.6、DeepSeek-V4-Flash/Pro、MiniMax-M2.7、Doubao-Seed 等 | 多模型生态完善；配置相对简单；每月约 18,000 次请求 | 已限购；社区反馈 429、响应慢、超售等问题较多 | 能买到且能接受稳定性风险再考虑 |
| [火山方舟 Pro](https://volcengine.com/L/crEuY2bBw3I/) | 首月约 ¥160；连续包月约 ¥200/月 | GLM-5.1、Kimi-K2.6、DeepSeek-V4-Flash/Pro、MiniMax-M2.7、Doubao-Seed 等 | 每月约 90,000 次请求；支持 ArkClaw 等复杂 Agent 场景 | 已限购；实际体验争议较大 | 需要多模型切换时可关注，但不建议盲入 |
| [腾讯云 Lite](https://console.cloud.tencent.com/tokenhub/codingplan) | ¥40/月 | GLM-5、Kimi-K2.5、MiniMax-M2.5、腾讯混元 HY 2.0 等 | 价格低；与腾讯云、企业微信生态打通 | 不支持 DeepSeek V4 和 Qwen 3.7 Max；需要抢购；社区实测少 | 已在腾讯生态内的团队可看 |
| [腾讯云 Standard](https://console.cloud.tencent.com/tokenhub/codingplan) | ¥100/月 | GLM-5、Kimi-K2.5、MiniMax-M2.5、腾讯混元 HY 2.0 等 | 档位居中，适合腾讯云用户试水 | 成熟度和口碑仍待验证 | 每日 0 点刷新库存的说法较多 |
| [腾讯云 Pro](https://console.cloud.tencent.com/tokenhub/codingplan) | ¥200/月 | GLM-5、Kimi-K2.5、MiniMax-M2.5、腾讯混元 HY 2.0 等 | 额度更高；生态集成方便 | 模型覆盖不如百炼、方舟；限购 | 企业微信 / 腾讯云深度用户可考虑 |
| [腾讯云 Max](https://console.cloud.tencent.com/tokenhub/codingplan) | ¥600/月 | GLM-5、Kimi-K2.5、MiniMax-M2.5、腾讯混元 HY 2.0 等 | 高额度，适合企业内部工具链 | 价格高；第三方反馈较少 | 非腾讯生态用户建议观望 |
| 电信天翼云 Lite | ¥49/月 | GLM-5-Turbo、GLM-5.1、GLM-4.5、GLM-4.5-Air、GLM-4.6、GLM-4.7 等 | 国产化和合规属性强；适合政务、金融、能源等信创场景 | 额度偏少，Lite 每月约 1,600 prompts；高峰期可能多倍扣额；不支持子账号和 API 调用 | 个人开发者性价比一般 |
| 电信天翼云 Pro | ¥149/月 | GLM-5-Turbo、GLM-5.1、GLM-4.x 系列等 | 合规和国产化优势明显；免费提供部分 MCP 服务 | 模型选择相对集中在 GLM；使用限制较多 | 信创刚需可选 |
| 电信天翼云 Max | ¥469/月 | GLM-5-Turbo、GLM-5.1、GLM-4.x 系列等 | 高档位更适合组织使用 | 对个人不友好；价格高 | 政企场景优先 |
| 讯飞星辰 di 无忧版 | 首购约 ¥3.9/月 | 低价档模型以平台实际展示为准 | 入门成本极低，适合试用 | 计费口径容易混淆；不适合重度开发 | 适合先体验平台，不建议作为主力 |
| 讯飞星辰专业版 | ¥39/月 | GLM-5.1、Kimi-K2.5、MiniMax-M2.5、DeepSeek-V3.2 等 | 不限购；可用 GLM-5.1；价格低；每月约 18,000 次请求 | 无 Kimi-K2.6、DeepSeek-V4、Qwen 3.7 Max；高峰期可能限流 | 抢不到智谱时的平替之一 |
| 讯飞星辰高效版 | ¥199/月 | GLM-5.1、Kimi-K2.5、MiniMax-M2.5、DeepSeek-V3.2 等 | 每月约 90,000 次请求；多模型切换灵活 | 相比智谱 Pro 性价比一般；品牌讨论度较低 | 需要稳定购买 GLM 但不想抢购时考虑 |
| 联通云 Lite | ¥40/月 | DeepSeek-V4-Flash、GLM-5.1 等 | 价格透明；不限购；每月约 18,000 次请求 | 不同云区域可用模型可能不同；模型多样性一般 | 预算有限、需求简单时可选 |
| 联通云 Pro | ¥200/月 | DeepSeek-V4-Flash、GLM-5.1 等 | 每月约 90,000 次请求；稳定性反馈较好 | 生态和模型选择不如头部聚合平台 | 需要稳定国内云服务时考虑 |
| 优云智算 Mini 迷你版 | ¥49/月 | DeepSeek-V3.2、GLM-5.1 等，按模型倍率扣费 | 费率透明；支持并发；无隐藏消费 | 每月约 1,900 次请求，单次成本偏高 | 适合低频但重视扣费透明的用户 |
| 优云智算 Lite 入门版 | ¥99/月 | DeepSeek-V3.2、GLM-5.1 等，按模型倍率扣费 | 约 3,800 次请求；支持 5 并发 | 同请求量价格高于主流平台 | 小团队轻量并发可看 |
| 优云智算 Basic 基础版 | ¥199/月 | DeepSeek-V3.2、GLM-5.1 等，按模型倍率扣费 | 约 7,600 次请求；支持 10 并发 | 请求数相对少 | 更适合看重并发和透明度的小团队 |
| 优云智算 Pro 增强版 | ¥499/月 | DeepSeek-V3.2、GLM-5.1 等，按模型倍率扣费 | 约 19,000 次请求；支持 10 并发 | 价格高，个人性价比一般 | 企业或团队按需选择 |
| [GitHub Copilot Student](https://github.com/copilot) | $0/月 | GitHub Copilot 高级模型，具体模型以 GitHub 展示为准 | 学生认证后免费；IDE 集成体验最好；每月约 300 次高级模型调用 | 需要学生认证；高级额度有限 | 学生开发者首选 |
| [GitHub Copilot Pro](https://github.com/copilot) | $10/月 | GitHub Copilot 高级模型，具体模型以 GitHub 展示为准 | VS Code 等 IDE 集成成熟；代码补全体验强 | 高级模型约 300 次/月；后续计费可能转向 Token 口径 | 偏 IDE 辅助，不一定适合重度 Agent |
| [GitHub Copilot Pro+](https://github.com/copilot) | $39/月 | GPT、Claude 等高级模型，具体以 GitHub 展示为准 | 高级模型额度更高，约 1,500 次/月；IDE 工作流好 | 国际订阅，价格较高；计费规则变化需关注 | 已习惯 Copilot 的用户可选 |
| [OpenCode GO](https://opencode.ai/zh/go) | 首月 $5；之后 $10/月 | GLM-5.1、Kimi-K2.6、DeepSeek-V4-Pro、MiMo-V2.5-Pro、MiniMax-M2.7、Qwen3.6 Plus 等 | 价格便宜；模型覆盖广；可在 Claude Code、Codex、OpenCode、Hermes 等 Agent 中使用；据反馈约可支持 880 次 GLM-5.1 或 3,450 次 DeepSeek-V4-Pro 请求 | 速度反馈略慢；请求次数不是固定公开口径 | 想低价体验多模型聚合时很香 |


