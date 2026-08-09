# Interview Prep Coach｜面试准备教练

告诉 AI 你准备的是**中文面试还是英文面试**，再发给它 **简历 + JD**。它会陪你一步步完成岗位分析、经历匹配、STAR 故事、重点问题、模拟面试、速查表和面后复盘。

Use your **resume + job description** for role analysis, evidence mapping, STAR stories, likely questions, mock interviews, cheat sheets, and debriefs.

> 适用于支持 Agent Skills、`SKILL.md` 或文件指令的 AI 工具，不限于 ChatGPT。
>
> Works with AI tools that support Agent Skills, `SKILL.md`, or file-based instructions—not only ChatGPT.

## 最快开始｜Quick Start

### 中文面试版

如果你准备中文面试，选择这个版本。

1. **[下载中文面试版 ZIP](https://github.com/xinyuan-zhao/Interview-Prep-Coach/raw/refs/heads/main/downloads/interview-prep-coach-zh.zip)**
2. 把 ZIP 上传给你的 AI。
3. 输入：

```text
请读取并使用这个 Interview Prep Coach Skill。
如果支持 Agent Skills，请帮我安装；如果不支持安装，请按照 SKILL.md 在当前对话中执行。
```

然后上传简历和 JD：

```text
帮我完整准备这场中文面试。这是我的简历和 JD。
```

### 英文面试版

如果你准备英文面试，选择这个版本。AI 会用英文提问和准备答案，用中文解释与反馈。

1. **[下载英文面试版 ZIP](https://github.com/xinyuan-zhao/Interview-Prep-Coach/raw/refs/heads/main/downloads/interview-prep-coach-en.zip)**
2. 把 ZIP 上传给你的 AI。
3. 输入：

```text
请读取并使用这个英文面试版 Interview Prep Coach Skill。
如果支持 Agent Skills，请帮我安装；如果不支持安装，请按照 SKILL.md 在当前对话中执行。
```

然后上传简历和 JD：

```text
帮我完整准备这场英文面试。请用英文提问和准备答案，用中文解释与反馈。
这是我的简历和 JD。
```

## 如果 AI 不能读取 ZIP｜If ZIP Is Unsupported

1. 解压 ZIP。
2. 上传整个 Skill 文件夹；或至少上传 `SKILL.md`。
3. 告诉 AI：“请按照 `SKILL.md` 执行。”

如果 AI 只能接收文字，打开 `SKILL.md`，复制内容到对话中，再上传简历和 JD。

Unzip the file and upload the Skill folder—or at least `SKILL.md`. If the AI only accepts text, paste the contents of `SKILL.md` into the conversation.

## 选择版本｜Choose a Version

| Version | Best for |
|---|---|
| `interview-prep-coach-zh` | 中文面试：中文提问、中文回答、中文反馈。 |
| `interview-prep-coach-en` | 英文面试：英文提问与答案、中文解释与反馈。 |

只需要告诉 AI 你要准备中文面试还是英文面试，它就会按照对应语言陪你练习。

## 常用指令｜Example Commands

```text
分析这个 JD，告诉我最重要的三个能力。
```

```text
把我的真实经历和岗位要求匹配一下。
```

```text
帮我准备 3 个可复用的 STAR 故事。
```

```text
直接开始英文模拟面试，每次只问一个问题。
```

```text
生成一份面试前 10 分钟可以看完的速查表。
```

```text
我刚面试完，帮我复盘。
```

```text
Analyze this JD and rank the top three capabilities.
```

```text
Start a mock interview and ask one question at a time.
```

## 核心原则｜Core Rule

Skill 不会故意编造或夸大：

- 工作经历、项目或职位。
- Leadership、Ownership 或个人贡献。
- 工具、技术、指标、金额、团队人数或影响。

证据不足时，应标记 **证据缺口** 并追问真实信息，而不是替用户编故事。

The Skill must not invent experience, ownership, tools, metrics, impact, or titles. Missing evidence should be labeled and clarified.

## 文件结构｜Files

```text
Interview-Prep-Coach/
├── downloads/                    # Ready-to-use ZIP files
├── interview-prep-coach-en/      # English Skill
└── interview-prep-coach-zh/      # Chinese Skill
```

每个语言文件夹都是独立 Skill，可以单独下载、安装或交给 AI 阅读。

Each language folder is standalone and can be installed or read independently.
