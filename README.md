# Homelab

---

## 硬體

| 角色 | 型號 | 規格 | 價格 |
|---|---|---|---|
| **Prod 節點** | HP ProDesk 600 G4 Mini | i5-8500T (35W / 6C) · 16GB DDR4 · 512GB NVMe | 5,680 |
| **交換器** | Cisco WS-C2960CG-8TC-L | 8×1000BASE-T + 2 dual-purpose · LAN Base · 無風扇 | 3,340 |
| **工作站** | 自組桌機 | i5-13400F · 32GB DDR4 · RTX 3060 Ti · 954GB SSD | 既有 |
| **網路線** | POLYWELL Cat6 ×7 | 七色各 1m · 福祿克認證 · 依網段區分顏色 | 490 |
| **Console 線** | USB 轉 RJ45 | 300cm · 用於交換器初始設定與頻外管理 | 150 |
| | | **合計** | **9,660** |

---

## 架構

```
            家用路由器
                │
          Cisco 2960CG
             交換器
                │
        ┌───────┴───────┐
        │               │
     ProDesk          桌機
    Prod 節點        工作站
```

---

## 紀錄

- [工作日誌](docs/worklog.md)
