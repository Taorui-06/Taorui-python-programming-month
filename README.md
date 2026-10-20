# Taorui-python-programming-month

> 大一新生 · 一个月编程基础学习（Python 路线）
> 周期：2026-10-20 ~ 2026-11-19

这个仓库记录我这一个月的 Python 学习全过程：每周的练习代码、遇到的问题、复盘总结，以及使用 AI 工具的情况。

## 目录结构

```text
Taorui-python-programming-month/
├── week1/            第 1 周练习与代码
├── week2/            第 2 周练习与代码
├── week3/            第 3 周练习与代码
├── week4_review/     第 4 周综合复习与总结
├── README.md         仓库说明（本文件）
├── LEARNING_LOG.md   学习日志
├── PROBLEM_LOG.md    问题日志（踩坑与解决）
└── AI_USAGE.md       AI 使用记录
```

## 学习进度

| 周次 | 时间 | 主题 | 状态 |
| --- | --- | --- | --- |
| week1 | 10-20 ~ 10-26 | 环境搭建、变量与数据类型、输入输出、条件分支 | 进行中 |
| week2 | 10-27 ~ 11-02 | 循环、列表与字典、字符串处理 | 未开始 |
| week3 | 11-03 ~ 11-09 | 函数、模块、文件读写、异常处理 | 未开始 |
| week4_review | 11-10 ~ 11-19 | 综合练习、错题回顾、月度总结 | 未开始 |

## 运行环境

- Python 3.13
- Git 2.56
- 编辑器：VS Code / PyCharm

## 代码约定

- 每周练习放在对应 `weekN/` 目录下，文件名用 `主题_序号.py`，例如 `week1/datatype_01.py`
- 每个 `.py` 文件顶部用注释写清楚：这是第几周的什么练习、题目要求是什么
- 不提交 `__pycache__/`、虚拟环境目录等自动生成的文件（见 `.gitignore`）

## 提交信息规范

| 前缀 | 用途 | 例子 |
| --- | --- | --- |
| `feat` | 新增练习代码 | `feat(week1): 完成温度转换练习` |
| `fix` | 修正出错代码 | `fix(week2): 修正循环边界越界` |
| `docs` | 更新日志/文档 | `docs: 补充第 3 周学习日志` |
| `chore` | 配置类改动 | `chore: 添加 .gitignore` |

## 相关文档

- 每天学了什么、卡在哪 → [LEARNING_LOG.md](LEARNING_LOG.md)
- 每次报错怎么解决的 → [PROBLEM_LOG.md](PROBLEM_LOG.md)
- 哪些地方用了 AI 辅助 → [AI_USAGE.md](AI_USAGE.md)
