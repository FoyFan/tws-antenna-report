# TWS 耳机 2.4G / 5G / 6E 多频段天线仿真 SOP 与工程报告

Ansys AEDT 2025 (HFSS) × Claude Code + PyAEDT 全流程自动化 —— 建模 · 求解 · 后处理 · 报告输出。

在线阅读：**https://foyfan.github.io/tws-antenna-report/**

## 内容

1. 项目概述与技术架构（Claude Code + PyAEDT + AEDT 三层架构）
2. 环境准备（系统 / 软件要求与依赖安装）
3. 仿真 SOP · 四步法（CAD 清理 → 材料设置 → 端口边界 → 网格求解）
4. PyAEDT 自动化脚本（建模、求解、导出与天线长度扫参）
5. 仿真结果与评估（S11 / 效率曲线 / 效率矩阵 / 量产结论）
6. 常见问题排查（COM 连接错误与 6GHz 网格收敛）

## 关键结果

| 指标 | 数值 |
| --- | --- |
| S11 峰值 @ 2.45 GHz | −18.5 dB |
| −10 dB 带宽（2.4G） | 2.38–2.52 GHz |
| 5G / 6E 频段 S11 | 带内 &lt; −10 dB，频点 &lt; −12 dB |
| 2.4G 辐射效率 / 总效率 | 69.4% / 68.4% |
| 最优天线长度 | L = 10.5 mm |

## 技术栈

- **Ansys AEDT 2025.1 · HFSS** — 三维全波电磁求解
- **PyAEDT** — Python API 脚本化全流程
- **Claude Code** — 终端自动化任务编排

纯静态单页站点（HTML + CSS，无构建步骤），部署于 GitHub Pages。
