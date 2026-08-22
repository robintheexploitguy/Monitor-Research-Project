# 📝 Implementation Handbook, Handover & Asset Register

## 🛠️ Setup & Configuration Guide
1. **Mounting:** Use a flat VESA 100x100 plate to reclaim desk depth.
2. **Cables:** Use a High-Speed HDMI 2.0 cable. Note: 5600G uses HDMI 1.4, limiting LG to 60Hz.

### 🧠 BIOS Guide for QHD (Only for LG)
```mermaid
flowchart TD
    A[Restart PC] --> B[Press Del or F2]
    B --> C[Go to Advanced]
    C --> D[NB Configuration]
    D --> E[Find UMA Frame Buffer Size]
    E --> F[Set to 2GB or 4GB]
    F --> G[Save and Exit F10]
