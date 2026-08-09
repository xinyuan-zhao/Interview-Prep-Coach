# Interview Prep Coach｜面试准备教练

> **第一次使用？从这里开始。No technical experience required.**

这是一个可以安装到 ChatGPT / Codex 的面试准备 Skill。你只需要准备 **简历 + 职位描述（JD）**，它会帮你分析岗位、匹配真实经历、准备 STAR 故事、预测重点问题、进行模拟面试，并生成面试速查表。

This is an interview-preparation Skill for ChatGPT and Codex. Give it your **resume + job description**, and it will analyze the role, map your real evidence, build STAR stories, prioritize likely questions, run mock interviews, and create a concise cheat sheet.

---

## 中文用户：5 分钟上手

### 第 1 步：下载这个仓库

1. 点击 GitHub 页面右上方绿色的 **Code** 按钮。
2. 点击 **Download ZIP**。
3. 下载完成后，双击 ZIP 解压。

你会看到两个文件夹：

| 文件夹 | 适合谁 |
|---|---|
| `interview-prep-coach-zh` | **推荐中文用户使用。** 中文讲解，也可以进行英文面试。 |
| `interview-prep-coach-en` | 全英文讲解和面试练习。 |

> 如果你是中文用户、但面试是英文，仍然选择 `interview-prep-coach-zh`。它会用英文问面试题，用中文给你反馈。

### 第 2 步：只压缩你需要的 Skill 文件夹

不要直接上传整个 GitHub 仓库。

以中文版为例：

1. 找到 `interview-prep-coach-zh` 文件夹。
2. 右键这个文件夹。
3. Mac 选择 **压缩“interview-prep-coach-zh”**；Windows 选择 **发送到 → 压缩(zipped)文件夹**。
4. 最终得到 `interview-prep-coach-zh.zip`。

正确的 ZIP 内容应该是：

```text
interview-prep-coach-zh/
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    ├── interview-methodology.md
    └── mock-interview-rubric.md
```

### 第 3 步：安装 Skill

在支持 Skills 的 ChatGPT 或 Codex 中：

1. 打开左侧栏的 **Plugins（插件）**。
2. 进入 **Skills**。
3. 选择 **Create（创建）**。
4. 选择 **Upload from your computer（从电脑上传）**。
5. 上传刚才生成的 `interview-prep-coach-zh.zip`。
6. 按页面提示完成安装。

不同账号、版本或工作区看到的按钮可能略有不同。如果没有 Skills 或 Upload 选项，请查看下面的“常见问题”。

### 第 4 步：开始第一次面试准备

安装后，新建一个对话，输入：

```text
使用 $interview-prep-coach-zh 帮我准备面试。
这是我的简历和职位描述（JD）。
```

然后上传：

1. 你的简历（PDF、Word 或文本均可）。
2. 完整的 JD（文件、截图、网页内容或复制的文字均可）。

可选信息：

- 公司名称或招聘链接。
- 面试轮次：Recruiter / Hiring Manager / Panel / Final。
- 面试语言：中文或英文。
- 面试日期。
- 已经准备过的答案或笔记。

### 第 5 步：告诉它你现在想做什么

你不需要记复杂命令，直接用自然语言即可：

```text
帮我完整准备这场面试。
```

```text
只分析这个 JD，告诉我最重要的三个能力。
```

```text
把我的经历和岗位要求匹配一下。
```

```text
帮我准备 3 个最值得讲的 STAR 故事。
```

```text
帮我准备英文 Tell me about yourself。
```

```text
直接开始英文模拟面试，每次只问一题。
```

```text
像严格的 Hiring Manager 一样追问我，每题后用中文反馈。
```

```text
生成一份面试前 10 分钟可以看完的速查表。
```

```text
我刚面试完，帮我复盘。
```

### 最简单的完整流程

```text
简历 + JD
→ 岗位真正需要什么
→ 我的真实证据是否匹配
→ 准备 3–5 个核心故事
→ 预测重点问题
→ 准备关键答案
→ 模拟面试
→ 面试速查表
→ 面后复盘
```

你可以一次完成全部流程，也可以只做其中一步。

---

## English Users: 5-Minute Setup

### Step 1: Download this repository

1. Select the green **Code** button on this GitHub page.
2. Select **Download ZIP**.
3. Unzip the downloaded file.

Choose one Skill folder:

| Folder | Best for |
|---|---|
| `interview-prep-coach-en` | English coaching and interview practice. |
| `interview-prep-coach-zh` | Chinese coaching, including English-language interviews. |

### Step 2: Zip only your chosen Skill folder

Do not upload the complete GitHub repository.

For the English version:

1. Locate `interview-prep-coach-en`.
2. Right-click the folder.
3. On macOS, select **Compress**. On Windows, select **Send to → Compressed (zipped) folder**.
4. You should now have `interview-prep-coach-en.zip`.

The ZIP should contain:

```text
interview-prep-coach-en/
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    ├── interview-methodology.md
    └── mock-interview-rubric.md
```

### Step 3: Install the Skill

In a ChatGPT or Codex experience that supports Skills:

1. Open **Plugins** in the sidebar.
2. Open **Skills**.
3. Select **Create**.
4. Select **Upload from your computer**.
5. Upload `interview-prep-coach-en.zip`.
6. Follow the on-screen installation prompt.

Labels may differ slightly by account, product version, or workspace. See Troubleshooting if Skills or uploads are unavailable.

### Step 4: Start your first session

Open a new conversation and enter:

```text
Use $interview-prep-coach-en to prepare me for this interview.
Here are my resume and the job description.
```

Attach:

1. Your resume or CV.
2. The complete job description.

Optional context:

- Company name or job-posting URL.
- Interview stage: recruiter, hiring manager, panel, or final.
- Interview language.
- Interview date.
- Existing answers or notes.

### Step 5: Ask for the module you need

```text
Prepare me completely for this interview.
```

```text
Analyze only the JD and rank the three most important capabilities.
```

```text
Match my real experience to this role.
```

```text
Help me build three reusable STAR stories.
```

```text
Help me answer “Tell me about yourself.”
```

```text
Start a mock interview and ask one question at a time.
```

```text
Act like a tough hiring manager and give feedback after every answer.
```

```text
Create a cheat sheet I can review in ten minutes.
```

```text
I just finished the interview. Help me debrief.
```

---

## What the Skill Produces｜你会得到什么

- Role purpose and competency analysis｜岗位本质与核心能力分析。
- Resume × JD evidence map｜简历与 JD 证据地图。
- Top selling points and honest gap positioning｜核心卖点与真实 Gap 定位。
- Three to five reusable STAR stories｜3–5 个可复用 STAR 故事。
- Prioritized interview questions｜按优先级排序的面试题。
- Critical answer outlines or spoken scripts｜关键答案提纲或口语稿。
- Realistic mock interviews with follow-ups｜带连续追问的模拟面试。
- Interview scorecard and specific feedback｜模拟面试评分与具体改进建议。
- A concise pre-interview cheat sheet｜面试前速查表。
- A structured post-interview debrief｜面后复盘。

## Important Truthfulness Rule｜真实性原则

这个 Skill 不应该为你编造：

- 工作经历、项目或职位。
- “领导过”或“主导过”的虚假职责。
- 不存在的工具、技术或行业经验。
- 虚假的数字、百分比、金额、团队人数或客户影响。

如果证据不足，它会标记 **证据缺口** 并向你追问，而不是替你编故事。

This Skill must not invent experience, leadership, tools, technologies, metrics, team size, customer impact, achievements, or titles. Missing evidence should be labeled and clarified—not fabricated.

## Privacy Reminder｜隐私提醒

- 上传前可以删除简历中的家庭地址、电话、证件号码等不必要的敏感信息。
- 不要上传公司机密、受 NDA 保护的材料或他人的私人信息。
- 使用前请自行核对每一句答案是否准确。

Remove unnecessary personal data before uploading. Do not share confidential employer information, NDA-protected material, or another person's private information. Review all prepared answers for factual accuracy.

## Troubleshooting｜常见问题

### 我找不到 Skills 或 Upload 按钮

Skills 是否可用可能取决于你的套餐、产品版本、工作区设置和管理员权限。可以尝试：

1. 确认使用的是支持 Skills 的 ChatGPT 或 Codex 版本。
2. 查看侧边栏中的 **Plugins → Skills**。
3. 更新桌面应用或重新打开网页。
4. 如果使用公司/学校账号，联系 Workspace Admin 确认是否允许安装和上传 Skills。

### The Skills or Upload option is missing

Availability may depend on your plan, product surface, workspace settings, or role. Check **Plugins → Skills**, update/restart the app, or ask your workspace administrator whether Skill installation and uploading are enabled.

### 上传后没有自动使用 Skill

在新对话中明确写出：

```text
使用 $interview-prep-coach-zh 帮我准备面试。
```

英文版使用：

```text
Use $interview-prep-coach-en to prepare me for this interview.
```

### Skill 要我重新发简历或 JD

确认文件已经成功上传，并且内容可以正常读取。也可以把 JD 直接复制到对话中。

### 我没有任何管理经验，但 JD 要求 Leadership

直接如实说明。Skill 应该帮助你寻找真实的影响力、协作、主动性或 Ownership 证据，并把 Leadership Gap 诚实标出来，而不是编造管理经历。

### 我的故事没有数字怎么办？

不要编数字。使用真实的定性结果，例如：流程被采用、问题得到解决、按时交付、风险降低、获得 Stakeholder 支持或客户反馈改善。

---

## For Repository Maintainers｜给仓库维护者

```text
Interview-Prep-Coach/
├── README.md
├── interview-prep-coach-en/
│   ├── SKILL.md
│   ├── README.md
│   ├── agents/openai.yaml
│   └── references/
│       ├── interview-methodology.md
│       └── mock-interview-rubric.md
└── interview-prep-coach-zh/
    ├── SKILL.md
    ├── README.md
    ├── agents/openai.yaml
    └── references/
        ├── interview-methodology.md
        └── mock-interview-rubric.md
```

Each language folder is a standalone Skill and can be zipped and installed independently.

## Official Skill Help｜官方说明

- [Skills in ChatGPT — OpenAI Help Center](https://help.openai.com/en/articles/20001066)
- [Plugins in ChatGPT and Codex — OpenAI Help Center](https://help.openai.com/en/articles/20001256-plugins-in-codex)
