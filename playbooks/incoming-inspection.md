# 来料 IQC

```text
到货签收（数量/包装外观）
  → 隔离待检区（未检品不得上线）
    → IQC（对照 PO + 图纸）
      → Pass：入库、可发料
      → Conditional：书面让步（谁签、用在哪、是否扣款）
      → Fail：隔离 + NCR + 通知供应商
```

| Field | Value |
|---|---|
| IQC # | `IQC-<PO号>` |
| 到货日 | |
| 判定 | Pass / Fail / Conditional |

## Checks

- [ ] 数量与 PO 一致  
- [ ] 包装完好、无进水/压损  
- [ ] 型号 / 批次标识可追溯  
- [ ] 关键尺寸 / 接口抽检通过  
- [ ] 电气/功能抽检（如适用）  
- [ ] 不合格品隔离并通知供应商  

Fail 须开 NCR 并隔离实物。  
Conditional 须供应链主责 + 使用方会签。
