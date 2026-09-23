# 结构件

**大类：** 承力、连接、盒体、外观骨架。图纸和公差在自己手里，产能在外协。

样机默认 **CNC + 钣金**；型材做 Link；注塑/压铸要外形冻结再开模；3D 打印只当工装和验证件。

## 小类

| 小类 | 干什么 | 入口 |
|---|---|---|
| CNC 机加 | 关节座、法兰、高精度承力件 | [cnc.md](./cnc.md) |
| 钣金 | 盒体、支架、防护 | [sheet-metal.md](./sheet-metal.md) |
| 型材 | Link、机架、快速改长度 | [extrusion.md](./extrusion.md) |
| 压铸 | 小批壳体、复杂腔体 | [die-cast.md](./die-cast.md) |
| 注塑 | 外观件、非承力罩 | [injection.md](./injection.md) |
| 3D 打印 | 工装、手板、走线验证 | [3d-print.md](./3d-print.md) |
| 表面处理 | 阳极、发黑、喷涂、微弧 | [surface/](./surface/README.md)（[阳极](./surface/anodize.md) · [发黑](./surface/black-oxide.md) · [喷涂](./surface/coating.md) · [微弧](./surface/mao.md)） |

## 大类冻结纪律

材料牌号、表面处理、关键尺寸与基准必须写在图纸上。「按惯例」不算 G1 通过。升版后旧 RFQ 作废。
