<div align="center">

# AGENTS.md-Best-Practices

[![Version](https://img.shields.io/badge/Version-0.1.0-green)](https://github.com/JularDepick/AGENTS.md-Best-Practices/releases/tag/v0.1.0)
[![Copyright](https://img.shields.io/badge/Copyright-JularDepick-0066AA)](./COPYRIGHT)
[![MIT](https://img.shields.io/badge/License-MIT-yellow)](./LICENSE)

[[English]](./README.md)
[[简体中文]](./README_zh-CN.md)

</div>

一个遵守 [AGENTS.md 开放规范](https://github.com/agentsmd/agents.md) 的通用提示词工程最佳实践。


# 项目规范

- 分文件夹放置适用不同分类和作者的 `AGENTS.md` 文档最佳实践
- `skill/agents-md-best-practices/` 封装所有 `AGENTS.md`，通过工作流生成SKILL实现渐进式披露


# 项目结构

```plaintext
AGENTS.md-Best-Practices/
├── src/
│   ├── develop/                    # 一级分类
│   │   └── web-frontend-design/    # 二级分类
│   │       └── {author}/           # 作者
│   │           ├── AGENTS.md             # 主文件（不限语言）
│   │           └── AGENTS_{xx-YY}.md     # 可选的主文件多语言版本（如zh-CN版本）
│   └── life/
└── skill/
    └── agents-md-best-practices/   # 完整封装（通过工作流生成）
        ├── SKILL.md                # 技能入口
        ├── index.yaml              # md 文档索引
        └── md/                     # 所有 AGENTS.md
            └── {primary-category}_{secondary-category}_{author}_AGENTS.md  # AGENTS.md 副本
```


# 快速开始

## 一、作为 AGENTS.md

根据需求和项目描述选择合适的 `AGENTS.md` 文件下载到项目目录，运行本地 Agent 后提示加载即可

## 二、作为 SKILL.md

下载安装 `skill/agents-md-best-practices/` 技能包到 Agent 对应目录后运行本地 Agent 后提示加载技能即可


# 收录列表

暂无收录，欢迎贡献。


# 贡献指南

欢迎通过以下方式参与贡献：

1. **提交收录**：按照项目结构要求，在 `src/` 目录下创建对应的 `AGENTS.md` 文件
2. **报告问题**：提交 Issue 反馈 bug 或提出改进建议
3. **完善文档**：优化现有文档或翻译多语言版本
4. **功能开发**：实现新功能或优化工作流

请确保遵循项目规范，并保持代码风格一致。


# 许可证

本项目采用 [MIT 许可证](./LICENSE)

版权所有 &copy; 2026 [JularDepick](https://github.com/JularDepick/)，详见 [COPYRIGHT](./COPYRIGHT)
