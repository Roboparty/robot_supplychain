<p align="center">
  <img src="./site/banner.svg" alt="机器人供应链知识库" width="100%">
</p>

<h1 align="center">机器人供应链</h1>

<p align="center">
  每种料是什么、用在哪一轴、选型冻什么、怎么验收、踩过什么坑
</p>

<p align="center">
  分类是 <b>大类 → 小类 → 细分</b> · 这里记判断口径，不记这一次买了谁
</p>

<p align="center">
  <a href="./knowhow/README.md"><img src="https://img.shields.io/badge/Knowhow-分类树-283F90?style=for-the-badge" alt="Knowhow"></a>
  <a href="./docs/gates.md"><img src="https://img.shields.io/badge/Gates-G0–G5-4C6FD4?style=for-the-badge" alt="Gates"></a>
  <a href="./playbooks/README.md"><img src="https://img.shields.io/badge/Playbooks-作业手册-121A33?style=for-the-badge" alt="Playbooks"></a>
  <a href="./knowhow.html"><img src="https://img.shields.io/badge/Docs-点开即看-A5B8F5?style=for-the-badge&labelColor=283F90" alt="Docs"></a>
</p>

---

## 这是什么

早期硬件供应链的**元器件知识库**：关节、结构、电子、传感、能源、末端、标准件。

| 放这里 | 不放这里 |
|---|---|
| 选型口径、冻结清单、验收与坑 | 合同扫描件、密钥、`.env` |
| Gate、作业手册、模板 | 未脱敏对公账号、身份证等 PII |
| 可公开协作的工艺与牌号知识 | 供应商完整电话 / 个人微信 |

询价、PO、供应商名录放在作业仓库；这里只记「这颗料是什么、下次怎么判」。

## 先读这三页

1. [knowhow/README.md](./knowhow/README.md) — 元器件分类树  
2. [knowhow/01-joint-modules/README.md](./knowhow/01-joint-modules/README.md) — 关节模组（减速机 / 电机 / 编码 / 驱动）  
3. [docs/gates.md](./docs/gates.md) — 买的时候怎么过 G0–G5  

## 七个大类

| # | 大类 | 入口 | 这一类在整机里干什么 |
|---|---|---|---|
| 01 | 关节模组 | [knowhow/01-joint-modules](./knowhow/01-joint-modules/README.md) | 谐波 / 行星 / RV、无框电机、编码、驱动 |
| 02 | 结构件 | [knowhow/02-structure](./knowhow/02-structure/README.md) | 机加材料、钣金、压铸、表面处理 |
| 03 | 电子器件 | [knowhow/03-electronics](./knowhow/03-electronics/README.md) | 线材 AWG、涂层、XT30（2+2） |
| 04 | 传感器 | [knowhow/04-sensors](./knowhow/04-sensors/README.md) | 力、触觉、IMU、视觉 |
| 05 | 能源 | [knowhow/05-energy](./knowhow/05-energy/README.md) | 电芯到 PACK / BMS |
| 06 | 末端 | [knowhow/06-end-effector](./knowhow/06-end-effector/README.md) | 灵巧手与作业接口 |
| 07 | 标准件 | [knowhow/07-standard-parts](./knowhow/07-standard-parts/README.md) | 轴承、紧固件 |

## 仓库结构

| 路径 | 用途 |
|---|---|
| [knowhow/](./knowhow/) | 元器件介绍：大类 / 小类 / 细分 |
| [docs/](./docs/) | 铁律、Gate、自制 vs 外购、RACI、入库纪律 |
| [playbooks/](./playbooks/) | 询价、准入、首件、来料、不合格闭环 |
| [templates/](./templates/) | 新元器件页、复盘卡片模板 |
| [site/](./site/) | 本地文档站生成器（冷色工业风） |
| [index.md](./index.md) | 文档站首页文案 |

## 铁律

> **无冻结图纸/规格不下正式单 · 无 IQC 不发料 · 无 NCR 不私下让步。**

适用阶段：研发样机 → 小批量试点。不是大规模量产 MRP，也不替代 ERP。

## 点开即看

用资源管理器双击 [knowhow.html](./knowhow.html)（不要用 Cursor 里的链接打开）。不需要安装、不需要启动服务器。Ctrl+K 搜索。

改完 Markdown 后重新生成：

```bash
python -m pip install markdown
python site/build.py
```

## 怎么往里写

1. 用 [templates/component.md](./templates/component.md) 开一页  
2. 挂进对应大类 README  
3. 复盘用 [templates/knowhow-card.md](./templates/knowhow-card.md) 追加到该页末尾  
4. 不写私人联系方式；敏感内容见 [docs/security.md](./docs/security.md)
