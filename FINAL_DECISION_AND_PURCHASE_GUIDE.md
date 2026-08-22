# 🏁 Final Decision & Purchase Guide

> [!IMPORTANT]
> **Project Status: COMPLETED.** This is the final, definitive recommendation for the monitor upgrade.
> **System Constraint:** AMD Ryzen 5 5600G | 2x8GB ADATA XPG DDR4 (16GB) | 21x21 inch nook.

## 1. The "Ram Trap" Dealbreaker (LG Excluded)
The Ryzen 5 5600G uses system RAM as VRAM. 
The **LG 27U631A** (1440p) requires a mandatory 2-4GB allocation, leaving insufficient available RAM for your workflow. 
> [!WARNING]
> **LG 27U631A is DISQUALIFIED.** Running it at 1080p to bypass the RAM issue is a waste of money, as it offers no advantage over cheaper 1080p monitors.

---

## 2. The Final Contenders (All 1080p, Safe for RAM)
| Monitor | Price (INR) | Panel | Refresh | Speakers | RAM Impact |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **MSI PRO MP275** | ~₹9,259 | IPS | 100Hz | Yes (2W) | ~1GB (Safe) |
| **Lenovo L27-4C** | ~₹10,999 | IPS | 144Hz | Yes (3W) | ~1GB (Safe) |
| **Samsung Essential S3** | ~₹11,598 | IPS | 100Hz | No | ~1GB (Safe) |
| **BenQ GW2790** | ~₹12,000 | IPS | 100Hz | Yes (2W) | ~1GB (Safe) |
| *Acer Nitro ED270* | ~Sub ₹12k | VA Curved | 200Hz | No | ~1GB (Safe) - *Disqualified* |

---

## 3. Heisener Decision Matrix
*(Scale: 1-10. Weighted for your 21x21 nook, coding focus, and RAM preservation).*

| Criteria | Weight | MSI PRO | Lenovo L27 | Samsung S3 | **BenQ GW2790** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Value for Money** | 25% | 10 | 8 | 7 | **8** |
| **RAM Preservation** | 20% | 10 | 10 | 10 | **10** |
| **Eye Care (Long Hours)** | 15% | 7 | 8 | 7 | **10** |
| **Speakers (Cable-Free)** | 15% | 7 | 8 | 0 | **8** |
| **Refresh Rate (Smoothness)** | 15% | 7 | 10 | 7 | **8** |
| **Fit for Wall Mount** | 10% | 9 | 9 | 9 | **10** |
| **Total Weighted Score** | **100%** | **8.55** | **8.70** | **6.90** | **9.10** |

---

## 4. Cost vs. Sharpness & Value Scatter Plot
*(X-Axis: Price, Y-Axis: Feature Value Score)*

| Monitor | Price (X) | Value Score (Y) | Quadrant |
| :--- | :--- | :--- | :--- |
| **MSI PRO** | ₹9,259 | 8.55 | Bottom-Left (Great budget) |
| **Lenovo L27** | ₹10,999 | 8.70 | Center (Strong all-rounder) |
| **Samsung S3** | ₹11,598 | 6.90 | Bottom-Right (Overpriced) |
| **BenQ GW2790** | **₹12,000** | **9.10** | **Top-Right (Best Value)** |

---

## 5. Decision Flowchart (Picking the Winner)
```mermaid
flowchart TD
    A[Start: Need 1080p Monitor] --> B{Want to save money?}
    B -- Yes, Max ₹9k --> C[Buy MSI PRO MP275]
    B -- No, want best features --> D{Do you need built-in speakers?}
    D -- Yes --> E{Do you want the best eye care?}
    E -- Yes --> F[Buy BenQ GW2790]
    E -- No --> G[Buy Lenovo L27-4C]
    D -- No --> H{Avoid Samsung, no speakers}
    H --> I[Buy Lenovo L27-4C]
