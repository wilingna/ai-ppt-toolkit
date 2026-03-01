# 🎯 AI 做 PPT 三件套工作流 Skill

> NotebookLM + Gemini + Gamma，从乱资料到高质量汇报的完整流程

[![Views](https://img.shields.io/badge/视频观看-25万%2B-blue)](https://github.com)
[![Likes](https://img.shields.io/badge/点赞收藏-1万%2B-red)](https://github.com)

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

### 安装 Skill

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
├── references/
│   └── example-hr-ai-case.md  # 完整案例参考（HR+AI 汇报示例）
└── README.md                   # 本文件
```

---

## 核心理念

> 真正难的从来不是 PPT 做不出来，而是你了解每个 AI 工具都擅长什么，以及你到底该怎么问 AI，它才会真的帮到你。

AI 做 PPT 的关键，从来不是"哪个工具更强"，而是**有没有擅用每个 AI 所长，然后把 Prompt 用在正确的位置**。

---

## 常见问题

**Q：不是 HR，这套流程适用吗？**  
A：完全适用。只需替换 Prompt 中的角色描述（"HR 战略顾问" → 你的领域专家）即可。

**Q：必须三个工具都用吗？**  
A：不是。NotebookLM 是最核心的，Gemini 是锦上添花，Gamma 可以替换为其他 PPT 工具。

**Q：Gemini 哪个版本？**  
A：推荐 Gemini 2.5 Pro，在去 AI 味和场景化扩写上效果最佳。

---

## License

MIT — 欢迎自由使用、修改、分发

---

*如果这个 Skill 对你有帮助，欢迎 ⭐ Star 支持！*
