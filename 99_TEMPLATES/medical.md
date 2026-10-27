---
created: "{{date:YYYY-MM-DDTHH:mm:ssZ}}"
updated: "{{date:YYYY-MM-DDTHH:mm:ssZ}}"
type: medical
date: "{{date:YYYY-MM-DD}}"
patient:
facility:
paid_date:
paid_amount:
reimbursed_amount:
transport_cost:
receipt_location:
deduction_status: 要確認
tags:
  - personal
  - medical
---

# {{title}}

> [!note] 医療費控除の金額そのものは、国税庁のルールで確認するか、税理士に確認してください（ここでの記録と AI の集計は下準備です）。

| 項目 | 内容 |
|---|---|
| 受診日 | {{date:YYYY-MM-DD}} |
| 受診者 | （本人、または [[家族]] の `家族_名前.md` へのリンク） |
| 医療機関 |  |
| 診療科 |  |
| 支払日 |  |
| 支払額（自己負担・円） |  |
| 補填額（保険金・高額療養費など・円） |  |
| 交通費（円・公共交通機関） |  |
| 領収書の保管場所 / 参照 | 例: 紙の箱「医療費2026」、スキャンPDFへのリンク |
| 控除対象の判定 | 対象 / 対象外 / 要確認 |

## 症状・受診理由

-

## 診断・医師の説明

-

## 処方

-

## 次回予定

-

## 関連

- [[医療・健康]]（医療費控除の集計対象）
