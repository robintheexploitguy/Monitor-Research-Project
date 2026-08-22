
**RESEARCH_REPORT.md**
```markdown
# 📊 Detailed Research Report

## 1. Display Technologies (Priority Ranked)
| Technology | Pros | Cons | Verdict |
| :--- | :--- | :--- | :--- |
| **IPS** | Great colors, wide angles (best for walls) | Slower response (fine for 100Hz) | 🥇 **Winner** |
| **VA** | Deep blacks, fast refresh | Poor angles (colors shift below) | 🥈 **Runner-up** |
| **TN** | Fastest, cheapest | Terrible colors and angles | ❌ **Avoid** |
| **OLED** | Perfect blacks, instant response | Burn-in risk, way over budget | ❌ **Out of scope** |

## 2. Priority Hierarchy Matrix
*(Scale: 1-10. Weight reflects your specific 5600G & 21x21 space.)*

| Criteria | Weight | LG 27U631A | BenQ GW2790 | Acer ED270 |
| :--- | :--- | :--- | :--- | :--- |
| Resolution (Text Sharpness) | 25% | 10 (1440p) | 6 (1080p) | 6 (1080p) |
| Fit for Space (Borderless) | 20% | 10 | 9 | 6 (Curved) |
| Color Accuracy (IPS) | 20% | 10 (IPS) | 9 (IPS) | 5 (VA) |
| Refresh Rate (UI Smoothness) | 15% | 7 (60Hz cap) | 8 (100Hz) | 10 (200Hz) |
| Ergonomics / Eye Care | 10% | 7 | 10 (B.I. Gen2) | 5 |
| Price (Lower is Better) | 10% | 8 (₹11,599) | 7 (₹12,000) | 10 (Sub 10k) |
| **Total Score** | **100%** | **8.95** | **7.75** | **6.30** |

## 3. Energy & Performance Model
**Energy Formula:** `Power (Watts) ≈ (Area (m²) x Nits) / 30`
* 27" Area: ~0.22m² | Brightness: 250 nits
* **Backlight:** 1.83W | **Real World:** ~28-32W
* **Cost:** ~₹90/month (8hrs/day)

> [!WARNING]
> **⚠️ THE RAM TRAP (Crucial for 5600G):**
> The Ryzen 5600G uses your system RAM as VRAM. 
> * **1080p:** Uses 1GB. 
> * **1440p (LG):** You MUST set `UMA Frame Buffer Size` to **2GB or 4GB** in BIOS. This drops your usable RAM from 16GB to 12-14GB.
> * CPU Load increases 5-10% when driving 100Hz vs 60Hz.

## 4. Future Upgrade Path (The ₹25k+ Route)
```mermaid
flowchart LR
    A[Current: 5600G + 16GB RAM] --> B{Buy 1440p 144Hz Monitor (₹25k)}
    B --> C[Need Dedicated GPU: RTX 4060 (₹26k)]
    C --> D[Need Better CPU: 5700X3D (₹15k)]
    D --> E[Total Future Cost: ₹66k]