# 🎯 AI 做 PPT 三件套工作流 Skill

> NotebookLM + Gemini + Gamma，从乱资料到高质量汇报的完整流程
http://xhslink.com/o/20J1E1g4i01 复制后打开【小红书】查看笔记！

---

## 这是什么？

这是一个专为职场人设计的 **Claude Skill**，封装了"AI 三件套"制作 PPT 的完整工作流——

**三个工具，各司其职：**

| 工具 | 做什么 | 为什么用它 |
|------|--------|-----------|
| **NotebookLM** | 从乱资料提炼结构 | 最擅长"消化"多来源信息，找出主线 |
| **Gemini** | 升级表达，去 AI 味 | 让内容听起来像"企业里的人说的话" |
| **Gamma** | 一键生成可交付 PPT | 视觉呈现，无需手动排版 |

---

## 快速开始

[点击在线体验](https://socialistic.ai/ai-ppt-toolkit-b14cc6?utm_source=github_readme&utm_campaign=koc_skill_creator&utm_content=hyperlink)

### 安装 Skill（Claude Desktop / Claude Web 用户）

1. 下载 `ai-ppt-toolkit.skill` 文件
2. 在 Claude 的 Skill 设置中上传安装
3. 开始对话时提到"做 PPT"、"汇报"、"三件套"等关键词，Skill 会自动触发

### 直接使用 Prompt 模板

如果你不使用 Skill 系统，可以直接复制 `SKILL.md` 中的两个 Prompt 模板：
- **NotebookLM Prompt**：用于结构设计
- **Gemini Prompt**：用于表达升级

---

## 适用场景

- 📊 老板临时交办的管理层汇报
- 🏢 部门工作总结/年度汇报
- 📈 行业分析演示
- 🎓 培训/分享课件制作
- 💡 任何"资料很杂、时间很紧"的 PPT 任务

---

## 文件结构

```
ai-ppt-toolkit/
├── SKILL.md                    # 主 Skill 文件（包含完整 Prompt 模板）
├── .claude/
│   └── commands/
│       └── ppt-workflow.md     # Claude Code 自定义命令（内容同 SKILL.md）
├── references/
│   └── example-hr-ai-case.md  # 完整案例参考（HR+AI 汇报示例）
└── README.md                   # 本文件
```

---

## 核心理念

> 真正难的从来不是 PPT 做不出来，而是你了解每个 AI 工具都擅长什么，以及你到底该怎么问 AI，它才会真的帮到你。

AI 做 PPT 的关键，从来不是"哪个工具更强"，而是**有没有擅用每个 AI 所长，然后把 Prompt 用在正确的位置**。

---

## 🤖 Claude Code 用户使用指南

本 Skill 原为 Claude Desktop / Claude Web 的 Skills 功能设计。
Claude Code 目前没有内置 Skills 面板，以下是两种调用方式。

### 方式一：CLAUDE.md 引用（推荐新手）

**适合：** 想在某个项目里长期使用这套流程

```bash
# 第 1 步：克隆仓库
git clone https://github.com/你的用户名/你的仓库名.git

# 第 2 步：进入你的工作目录
cd 你的项目文件夹

# 第 3 步：把 SKILL.md 复制为 CLAUDE.md
cp /克隆仓库的路径/SKILL.md ./CLAUDE.md

# 第 4 步：启动 Claude Code
claude
```

✅ Claude Code 会自动读取当前目录的 `CLAUDE.md`，三件套流程直接生效。

---

### 方式二：自定义命令（推荐进阶用户）

**适合：** 想随时在任意项目里一条命令调用，不想每次复制文件

如果你直接 clone 本仓库，`.claude/commands/ppt-workflow.md` 已经内置，**无需任何额外操作**，直接启动 Claude Code 输入命令即可：

```
/project:ppt-workflow
```

如果你想在自己的其他项目里使用：

```bash
mkdir -p .claude/commands
cp /克隆仓库的路径/SKILL.md .claude/commands/ppt-workflow.md
```

✅ 输入 `/project:ppt-workflow` 后，Claude Code 立刻进入三件套工作流。

---

### 两种方式对比

| | 方式一（CLAUDE.md） | 方式二（自定义命令） |
|---|---|---|
| 适合人群 | 新手 | 进阶用户 |
| 作用范围 | 单个项目目录 | 任意项目 |
| 调用方式 | 自动加载 | `/project:ppt-workflow` |
| 灵活度 | ⭐⭐ | ⭐⭐⭐⭐ |

---

### 使用时，把你的资料告诉 Claude

启动后，把以下内容发给 Claude Code：

```
我需要做一个PPT汇报，资料如下：

【老板需求】：...
【会议纪要】：...
【我的想法】：...
【参考文章】：...

请按三件套流程帮我处理。
```

Claude Code 会按照 NotebookLM → Gemini → Gamma 的逻辑，引导整个操作过程包括prompt的建议，输出可以直接用的结构大纲和 Markdown 格式内容。

---

## 常见问题

**Q：不是 HR，这套流程适用吗？**
A：完全适用。只需替换 Prompt 中的角色描述（"HR 战略顾问" → 你的领域专家）即可。

**Q：必须三个工具都用吗？**
A：不是。NotebookLM 是最核心的，Gemini 是锦上添花，Gamma 可以替换为其他 PPT 工具。

**Q：Gemini 哪个版本？**
A：推荐 Gemini 2.5 Pro，在去 AI 味和场景化扩写上效果最佳。

**Q：Claude Code 和 Claude Desktop 的 Skills 是一样的吗？**
A：不一样。Claude Desktop/Web 有内置 Skills 面板可以直接安装。Claude Code 目前没有这个系统，需要用上面两种方式手动加载。

**Q：用 Claude Code 跑，还需要真的打开 NotebookLM / Gemini / Gamma 吗？**
A：需要。这套流程的核心是 Prompt 逻辑，Claude Code 帮你生成每一步的输入内容，但你还是要把内容粘贴到对应工具里操作。

**Q：可以全自动跑完三步吗？**
A：目前不行，因为 NotebookLM、Gemini、Gamma 都没有公开 API。Claude Code 负责帮你"想清楚每步该输入什么"，执行还是在你手上。

---

## License

MIT — 欢迎自由使用、修改、分发

---

*如果这个 Skill 对你有帮助，欢迎 ⭐ Star 支持！*
