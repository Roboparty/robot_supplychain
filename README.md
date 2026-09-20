# 机器人供应链 Knowhow

人形 / 具身智能机器人早期硬件供应链的**元器件知识库**：每种料是什么、用在哪、怎么选、怎么验。

分类是 **大类 → 小类 → 细分**。例如关节模组 → 减速机 → 谐波 / 行星 / 摆线。

本仓库只放介绍、选型口径与清单模板。  
**不放**合同扫描件、密钥、未脱敏对公账号，以及供应商完整电话 / 个人微信。

姊妹作业仓库（询价、PO、供应商名录）是 `作业仓库`；那里记「这次买了什么」，这里记「这颗料是什么、下次怎么判」。

## 先读这三页

1. [knowhow/README.md](./knowhow/README.md) — 元器件分类树  
2. [knowhow/01-joint-modules/README.md](./knowhow/01-joint-modules/README.md) — 关节模组范例（减速机 / 电机 / 编码 / 驱动）  
3. [docs/gates.md](./docs/gates.md) — 买的时候怎么过 G0–G5  

## 目录

| 路径 | 用途 |
|---|---|
| [knowhow/](./knowhow/) | 元器件介绍：大类 / 小类 / 细分 |
| [docs/](./docs/) | 铁律、Gate、自制 vs 外购、RACI、入库纪律 |
| [playbooks/](./playbooks/) | 询价、准入、首件、来料、不合格闭环 |
| [templates/](./templates/) | 新元器件页、复盘卡片模板 |

## 铁律（一句话）

**无冻结图纸/规格不下正式单；无 IQC 不发料；无 NCR 不私下让步。**

## 适用阶段

研发样机 → 小批量试点。不是大规模量产 MRP，也不替代 ERP。

## 怎么往里写

新元器件用 [templates/component.md](./templates/component.md) 开页，挂进对应大类 README。复盘结论用 [templates/knowhow-card.md](./templates/knowhow-card.md) 追加到该页末尾。不写私人联系方式。
