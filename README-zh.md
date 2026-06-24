# Hi，我是 Adrian 👋

[![English](https://img.shields.io/badge/Lang-English-2b7489?style=flat-square)](README.md)&nbsp;[![中文](https://img.shields.io/badge/语言-简体中文-d54a35?style=flat-square)](README-zh.md)

我在做一些偏实用的 AI 工具。比起跑一次就结束的 demo，我更关注那些能真正用起来、也能用得长久的东西——可以反复运行，出问题时能够恢复，上下文中断后还能接续。

## 公开项目

- **[challenge-plans](https://github.com/hiadrianchen/challenge-plans)**：一个多 Agent 工具。在你正式执行一份 plan 或 spec 之前，先让多个 Agent 对它做一轮对抗式评审，提前找出其中站不住的假设、缺乏证据的结论，以及容易出问题的交接环节。它直接调用你本机已登录的编码 CLI（Claude Code、Codex），无需额外配置 API key。我对“多 Agent 系统如何才能可靠”的许多思考，都是在这个项目里沉淀成可运行的代码的。

## 我关注的方向

- **Multi-agent systems that don't fool themselves**：让不同厂商的模型相互验证，以证据而非票数为准，避免几个 Agent 彼此附和就当作达成了共识。
- **Personal AI operating systems**：把笔记、任务、内容，以及那些长期推进的事务，沉淀为能够留存的文件、待办与记忆，而不是随着一轮对话结束而消失。
- **Durable agent context**：用 Git 管理 memory 与 context，让 Agent 在更换设备、间隔一段时间后重新接手时，无需从头交代。
- **Knowledge ingestion**：把文章、视频、仓库、零散笔记汇入其中，产出可检索、可复用的内容。

有些项目暂时没有公开，因为它们与我的个人事务绑定在一起。等它们足够通用、不再依赖我的私人上下文时，我会把其中可复用的部分提取出来开源——challenge-plans 就是这样产生的第一个。

## 我的工作方式

我比较看重那些决定“一个系统能否被反复使用”的细节：信息来源要清晰，长任务中断后要能续接，隐私边界要守得住，关键环节要有人把关。大致的分工是：

- 抽取、清洗、校验这类确定性工作交给脚本；
- 判断、取舍、综合与补救交给 Agent；
- 最终的决策权留给人。

## 联系

- GitHub：[@hiadrianchen](https://github.com/hiadrianchen)
- 欢迎围绕 challenge-plans 交流、提 issue，或展开小范围协作。
