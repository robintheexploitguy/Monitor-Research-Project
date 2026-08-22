# 🎯 Executive Summary & Project Minutes

> **Project:** Monitor Upgrade & Workspace Optimization
> **Date Started:** 22nd August 2026
> **Project Status:** COMPLETED

---

## 1. Executive Summary

**The Goal:** Upgrade a 2010 Dell 17-inch monitor to a modern, professional display fitting within a strict **21x21 inch wooden nook**, running on an **AMD Ryzen 5 5600G** system with **2x8GB (16GB) ADATA XPG DDR4** memory, under a hard budget of **₹12,000 INR**.

**The Journey:** 
The project began by evaluating the **LG 27U631A-B** (1440p). Initial assumptions labeled it a "RAM killer" because of its 1440p resolution. Through rigorous research and analysis of the user's actual Task Manager data (showing 2.1GB already reserved), we proved that the monitor does not control RAM allocation (the BIOS UMA setting does). The LG was ultimately disqualified **strictly due to exceeding the budget** and the risk of consuming limited system headroom. 

**The Result:** 
After evaluating the MSI PRO, Lenovo L27, Samsung S3, and Acer, the **BenQ GW2790** emerged as the definitive winner. It perfectly balances the need for a 27" IPS workspace, 100Hz smoothness, built-in speakers, superior eye-care (B.I. Gen2), and VESA support—all within the ₹12,000 cap while providing the lightest possible load on the system's RAM.

---

## 2. Minutes of the Meeting (MoM)

### Key Discussion Points
| Point | Description | Takeaway |
| :--- | :--- | :--- |
| **The "RAM Killer" Myth** | The LG 1440p monitor was thought to mandate 2-4GB of VRAM allocation. | The monitor does not control RAM; the BIOS UMA Frame Buffer does. AMD recommends leaving it on "Auto". |
| **Real System Data** | Task Manager showed 16GB installed, but only 13.9GB usable (2.1GB reserved). | The system was already losing RAM before any new monitor was purchased. The LG would not inherently make this worse. |
| **Resolution vs. Refresh** | To "fix" a perceived RAM issue, one might drop the LG to 1080p/60Hz. | Dropping to 1080p causes non-integer scaling and softness, and 60Hz sacrifices desktop smoothness. It is not a recommended workaround. |
| **Budget vs. Quality** | The LG has superior specs (1440p, higher PPI). | **LG is technically superior, BenQ is the superior purchase under the ₹12,000 constraint.** |
| **Eye Health** | Long coding/security sessions require excellent eye care. | BenQ's Brightness Intelligence (B.I. Gen2), Coding Mode, and TÜV certification beat the LG's standard Reader Mode. |

### Action Items
- [ ] **Buy the BenQ GW2790** (Final Pick)
- [ ] Purchase a flat VESA 100x100 wall mount plate.
- [ ] Purchase a High-Speed HDMI 2.0 cable.
- [ ] Measure the physical nook to accommodate the 27" width (~24.1 inches).
- [ ] **Keep BIOS UMA Frame Buffer on "Auto"** unless there is a specific problem.
- [ ] Confirm the final price is ≤ ₹12,000 before purchasing.
- [ ] After installation, verify Windows reports expected usable memory.

---

## 3. Command Line Reference (Git & PowerShell Learnings)

Here is a comprehensive list of all Git commands utilized throughout the project, along with their purposes.

| Command | Purpose / Usage |
| :--- | :--- |
| `cd <path>` | Navigate to the correct directory (e.g., `cd C:\Users\Administrator\Desktop\Monitor-Research-Project`). |
| `git init` | Initializes a new Git repository in the current folder. |
| `git add .` | Stages all changes (new, modified, deleted files) in the current directory. |
| `git add <filename>` | Stages a specific file (e.g., `git add README.md`). |
| `git commit -m "<message>"` | Records changes to the repository history with a descriptive message. |
| `git branch -M main` | Renames the current local branch to `main` (crucial for GitHub compatibility). |
| `git remote add origin <url>` | Links the local repository to the remote GitHub repository. |
| `git push -u origin main` | Uploads local commits to the remote repository and sets the upstream branch. |
| `git push -u origin main --force` | Overwrites the remote branch with local commits. **Use with caution** (we used this to fix accidental deletions and repository corruption). |
| `git rm <filename>` | Removes a file from the repository and deletes it from the local disk (e.g., `git rm GITHUB_GUIDE.md`). |
| `git pull origin main` | Fetches and integrates changes from the remote repository to the local machine (used to sync after web edits). |

### Common Warnings / Errors Resolved
| Message | Meaning / Resolution |
| :--- | :--- |
| `fatal: not a git repository (or any of the parent directories): .git` | You are in the wrong folder. Use `cd` to navigate to the correct directory, or run `git init` to create a new repo. |
| `LF will be replaced by CRLF` | **Warning only, not an error.** Windows uses different line endings than Linux. Git automatically converts them for you; this is entirely normal. |
| `error: src refspec main does not match any` | Your local branch is called `master`, not `main`. Run `git branch -M main` to rename it before pushing. |
| `fatal: remote origin already exists` | You have already added the remote URL. Ignore this and just run `git push`. |

---

*Project finalized on 23rd August 2026. Successfully moved from a 2010 17" monitor to a modern 27" workspace while preserving system memory, staying within budget, and prioritizing eye health.*
