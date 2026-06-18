<div align="center">

# AGENTS.md-Best-Practices

[![Version](https://img.shields.io/badge/Version-0.1.0-green)](https://github.com/JularDepick/AGENTS.md-Best-Practices/releases/tag/v0.1.0)
[![Copyright](https://img.shields.io/badge/Copyright-JularDepick-0066AA)](./COPYRIGHT)
[![MIT](https://img.shields.io/badge/License-MIT-yellow)](./LICENSE)

[[English]](./README.md)
[[简体中文]](./README_zh-CN.md)

</div>

A best practice for universal prompt engineering that complies with the [AGENTS.md open specification](https://github.com/agentsmd/agents.md).


# Project Guidelines

- Organize `AGENTS.md` best practices for different domains in separate folders
- `skill/agents-md-best-practices/` encapsulates all `AGENTS.md` and uses workflow-generated SKILL for progressive disclosure


# Project Structure

```plaintext
AGENTS.md-Best-Practices/
├── src/
│   ├── develop/                    # Primary category
│   │   └── web-frontend-design/    # Secondary category
│   │       └── {author}/           # Author
│   │           ├── AGENTS.md             # Main file (language-agnostic)
│   │           └── AGENTS_{xx-YY}.md     # Optional multilingual version (e.g., zh-CN)
│   └── life/
└── skill/
    └── agents-md-best-practices/   # Complete encapsulation (generated via workflow)
        ├── SKILL.md                # Skill entry point
        ├── index.yaml              # MD document index
        └── md/                     # All AGENTS.md
            └── {primary-category}_{secondary-category}_{author}_AGENTS.md  # AGENTS.md copy
```


# Quick Start

## 1. As AGENTS.md

Select the appropriate `AGENTS.md` file based on your needs and project description, download it to your project directory, and prompt the local Agent to load it after running.

## 2. As SKILL.md

Download and install the `skill/agents-md-best-practices/` skill pack to the Agent's corresponding directory, then prompt the local Agent to load the skill after running.


# Collection List

No entries yet. Contributions are welcome.

# Contribution Guidelines

Welcome to contribute in the following ways:

1. **Submit entries**: Create corresponding `AGENTS.md` files in the `src/` directory according to the project structure requirements
2. **Report issues**: Submit Issues to report bugs or suggest improvements
3. **Improve documentation**: Optimize existing documents or translate multilingual versions
4. **Develop features**: Implement new features or optimize workflows

Please ensure you follow the project guidelines and maintain consistent code style.

# License

This project is licensed under the [MIT License](./LICENSE)

Copyright &copy; 2026 [JularDepick](https://github.com/JularDepick/), see [COPYRIGHT](./COPYRIGHT) for details.