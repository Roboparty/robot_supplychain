# 机器人供应链 Knowhow

人形 / 具身智能机器人早期硬件供应链的**可复用知识库**：怎么选型、怎么询价、怎么验收、怎么避坑。

本仓库只放框架、原则、门类 knowhow 与清单模板。  
**不放**合同扫描件、密钥、未脱敏对公账号，以及供应商完整电话 / 个人微信。

姊妹作业仓库（询价、PO、供应商名录）是 `作业仓库`；那里记「这次买了什么」，这里记「为什么这样买、下次怎么更快判」。

## 先读这三页

1. [docs/principles.md](./docs/principles.md) — 铁律与决策原则  
2. [docs/gates.md](./docs/gates.md) — G0–G5 放行门  
3. [knowhow/README.md](./knowhow/README.md) — 按物料门类查规格、坑和验收  

## 目录

| 路径 | 用途 |
|---|---|
| [docs/](./docs/) | 总原则、Gate、自制 vs 外购、RACI、入库纪律 |
| [knowhow/](./knowhow/) | 按门类：规格怎么冻、询价看什么、IQC 抽什么 |
| [playbooks/](./playbooks/) | 询价、准入、首件、来料、不合格闭环 |
| [templates/](./templates/) | 新增一条 knowhow 的卡片模板 |

## 铁律（一句话）

**无冻结图纸/规格不下正式单；无 IQC 不发料；无 NCR 不私下让步。**

## 适用阶段

研发样机 → 小批量试点。不是大规模量产 MRP，也不替代 ERP。

## 怎么往里写

每学到一条可复用结论，用 [templates/knowhow-card.md](./templates/knowhow-card.md) 开一张卡片，挂到对应门类页。卡片里只写口径与判据，不写私人联系方式。
