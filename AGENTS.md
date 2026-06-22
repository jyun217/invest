# Invest Agent Instructions

本仓库是一个通用 AI 投资研究助手，可在 Codex、Claude 或其他支持读取仓库说明的智能体中使用。

- 先阅读 `SKILL.md`，按其中的意图识别、分析流程、输出格式和风控规则执行。
- 结构化金融数据优先通过脚本获取：`python3 scripts/run.py <market> <code> <data_type>`。
- 运行脚本前请切换到仓库根目录；脚本会在 `scripts/.venv` 自动创建虚拟环境并安装依赖。
- 若脚本返回错误，再按 `SKILL.md` 的降级策略使用搜索补充，并明确标注数据来源和局限。
- 所有分析仅供研究参考，不构成投资建议。
