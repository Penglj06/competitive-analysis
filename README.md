# competitive-analysis

把「竞品分析」从「截图合集 + 功能对比表 + 一句套话结论」升级为**可执行的产品决策输入**。

通过拆流程、反推取舍、借鉴/照抄二分，最终回答的不是「竞品怎么做」，而是**「看完竞品之后，我们该怎么做」**。

## 核心主张

- **流程 > 页面**、**策略 > 功能**、**迁移 > 复述**
- 强制证据分级（一手 / 走查 / 公开 / 推断），不编指标
- 反推取舍而非反推指标，借鉴/照抄必须二分
- 深度走查优先于公开资料（agent-browser 实测竞品页面）

## 目录结构

```
.
├── SKILL.md                        # 主文件：触发词、12 条硬性约束、工作流
├── references/
│   └── analysis-playbook.md        # 七步完整 Prompt 模板、证据分级细则、深度走查操作指引
└── assets/
    └── report-template.md          # 报告结构模板（含证据等级列、我方基线、决策三分类）
```

## 适用场景

- 竞品分析 / 竞品调研 / 对标分析 / 差异化分析
- 技术选型、benchmark 调研、学术工具 / 文献综述
- 对 **AI4S / 学术科研类工具**的竞品分析尤其实用

## 使用方法

这是一个 [WorkBuddy](https://www.workbuddy.cn) / Claude Code 风格的 Agent Skill。

安装到 `~/.workbuddy/skills/competitive-analysis/` 即可被识别，也可在 SkillHub 社区检索安装。

## License

[MIT](./LICENSE)
