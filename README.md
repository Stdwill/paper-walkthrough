# Paper Walkthrough · 15 分钟论文导读

一个面向零基础读者的 Codex skill：用约 15 分钟的学习路线，通过生活例子、术语定义、反例和关键公式，逐步理解一篇论文。

## 讲解方式

- 从论文想解决的问题出发，解释朴素方法为什么不够。
- 用 1—2 个贯穿全文的例子说明机制，重要术语保留英文原文。
- 逐个拆解关键公式的符号，并用具体数字或状态验证。
- 区分背景知识、论文贡献、教学类比与实验或理论证据。
- 保留结论成立的条件，说明局限。
- 提供自测题、参考答案和原文阅读位置。

默认使用简体中文，可指定其他语言、学习基础与时长。15 分钟指预计学习时间，并非助手执行时间。

## 安装

将整个仓库下载或克隆为个人 skills 目录下的 `paper-walkthrough` 文件夹。默认目录为 `~/.codex/skills`；如果设置了 `CODEX_HOME`，则使用其中的 `skills` 目录。

默认路径的安装命令（目标文件夹尚不存在时）：

```sh
git clone https://github.com/Stdwill/paper-walkthrough.git ~/.codex/skills/paper-walkthrough
```

Windows PowerShell：

```powershell
git clone https://github.com/Stdwill/paper-walkthrough.git "$env:USERPROFILE\.codex\skills\paper-walkthrough"
```

安装后的目录包含：

```text
paper-walkthrough/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── README.md
```

## 使用

```text
用 $paper-walkthrough，带我用 15 分钟从零基础读懂这篇论文：[论文链接或文件]
```

也可以调整时长或要求互动教学：

```text
用 $paper-walkthrough，用 30 分钟讲这篇论文。我懂基础概率，但不了解这个研究领域。
```

```text
用 $paper-walkthrough 分段带我读论文，每讲完一个核心概念，先让我回答问题再继续。
```

该 skill 侧重理解论文，不替代逐句翻译、同行评审或系统性文献综述。无法读取全文时，会说明实际读取范围，不补造论文内容。
