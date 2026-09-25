# 民航动态安全间隔研究项目

先研究航路上前后两架飞机的纵向动态安全间隔，再根据独立研究价值扩展侧向和垂直方向，最终形成硕士论文。基础模型为经典 EVENT，具体来源与公式尚待核验。

## 从这里开始

1. 看 `PROJECT_STATE.md`：现在做到了哪里、下一步是什么。
2. 看 `PROJECT_PLAN.md` 和 `AGENTS.md`：研究范围、质量标准、周期和协作规则。
3. 看 `TOOL_REGISTRY.md`：哪些工具能用于哪些任务，哪些还没确认。
4. 看 `00_project/roadmap/P01_CHARTER.md`：首篇范围草案与缺失信息。
5. 看 `00_project/FILE_ORGANIZATION.md`：文件分类与这次整理记录。

## 目录导航

| 目录 | 放什么 |
|---|---|
| 00_project | 进度、路线、决策及工作日志 |
| 01_literature | 文献台账、原件、笔记和证据位置 |
| 02_theory | 基准模型、推导和符号 |
| 03_data | 原始、外部、仿真和处理后数据 |
| 04_code | 模型代码、必要测试、脚本及环境说明 |
| 05_experiments | 实验方案、配置、运行记录及汇总 |
| 06_figures | 图表制作说明和导出文件 |
| 07_manuscripts | 首篇稿件与硕士论文整体结构 |
| 08_submission | 投稿要求、提交包及修回记录 |
| 09_archive | 旧版计划和整理前备份 |

当前只完成项目基础部署，文献、模型、数据和实验均不能因已有目录而视作完成。CSV 表中的空字段表示尚未取得信息，不能擅自补值。

## 在 VS Code 中使用

打开 `Safe-interval.code-workspace`，或在 VS Code 中打开本目录。使用“终端 → 运行任务”可查看 Git 状态与远程地址，任务均只读。本次未启动 VS Code 窗口，未安装扩展。

## GitHub

远程为 https://github.com/lin123912/Safe-interval 。本地 origin 已关联。用户已授权在 Public 状态下将审查过的候选文件首次上传；上传结果以项目状态页及远程读回为准。
文件同步须遵循 `00_project/SYNC_POLICY.md`；.gitignore 仅降低误加入的概率，不能代替上传前审阅。

本地初始提交与上传范围见 00_project/FIRST_UPLOAD.md；文献原文、数据和审稿材料默认只留本地。
