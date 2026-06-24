# Hi，我是 Adrian 👋

[![English](https://img.shields.io/badge/Lang-English-2b7489?style=flat-square)](README.md)&nbsp;[![中文](https://img.shields.io/badge/语言-简体中文-d54a35?style=flat-square)](README-zh.md)

我在做一些比较实用的 AI 工具，关注的不是那种跑一次就完的 demo，而是真能用起来、还能用得久的东西——能反复跑、出岔子能回退、上下文断了能接上。

## 公开项目

- **[challenge-plans](https://github.com/hiadrianchen/challenge-plans)**：一个多 Agent 工具。在你真正动手执行一份 plan 或 spec 之前，先让几个 Agent 对它做一轮“找茬”式评审，把那些站不住的假设、缺证据的结论、容易出问题的交接点提前挑出来。它直接调你本机已经登录的编码 CLI（Claude Code、Codex），不用另配 API key。我对“多 Agent 怎么才靠谱”的不少想法，都是在这个项目里落成能跑的代码的。

## 我在琢磨的几件事

- **不会自己骗自己的多 Agent 系统**：让不同厂商的模型互相验证，认证据而不是认谁票多，别几个 Agent 一附和就当成了共识。
- **个人的 AI 操作系统**：把笔记、任务、内容、那些一直拖着的事，攒成能留下来的东西——文件、待办、记忆，而不是聊完这一轮就没了。
- **能接得住的 Agent 上下文**：记忆和上下文都用 Git 管起来，换台设备、隔几天再接手，不用从头再交代一遍。
- **把信息变成知识**：文章、视频、仓库、零碎笔记丢进来，出来的是能搜、能复用的东西。

有些项目暂时没公开，因为它们跟我个人的东西绑在一起。等哪天它足够通用、不靠我那点私人上下文也能用了，我会把能复用的部分拆出来开源——challenge-plans 就是这么出来的第一个。

## 我做事的方式

我比较在意那些决定“一个系统能不能用第二回”的细节：东西从哪来得清楚、长任务断了得能续、隐私的边界得守住、关键的地方得有人把关。大致是这么分的：

- 抽取、清洗、校验这些固定活儿交给脚本；
- 判断、取舍、综合、补救交给 Agent；
- 真正拍板的事留给人。

## 联系

- GitHub：[@hiadrianchen](https://github.com/hiadrianchen)
- 想聊 challenge-plans、提 issue，或者一起鼓捣点小东西，都欢迎。
