# Amygdala Protocol

> "These scripts pulse beneath the OS. They do not wait for permission."

**Amygdala** is a diagnostic suite forged for precision, silence, and system clarity. Designed to run autonomously, these scripts scan, restore, clean, and upgrade your environment—Intel and NVIDIA variants included.

Each script is optimized for:
- 🧼 **File system integrity repair** via `sfc /scannow`
- 🩺 **OS image restoration** using `DISM /RestoreHealth`
- 🔒 **Custom restore point creation** before cleanup actions
- 📦 **App upgrades and system audits** through Winget
- 🌐 **Driver environment verification** for Intel or NVIDIA stacks
- 🔄 **Scheduled execution** through Task Scheduler automation

Inspired by mythic archetypes and forged for hands-off system stewardship, the Amygdala Protocol operates like a silent guardian—present, persistent, pulsing.

## 📁 Included Scripts
- `Amygdala_Intel.ps1` — Targets Intel-based diagnostics and cleanup
- `Amygdala_NVIDIA.ps1` — Tailored for NVIDIA GPU environments
- `README.md` — You're reading it
- *(Optional)* `Logs/` — Output history, useful for audit trails

## 📅 Recommended Scheduling
Automate using Windows Task Scheduler:
- Run at logon or daily/weekly cycle
- Execute with highest privileges
- Logs can be redirected for tracking purposes

---

## 🧪 Example Usage (PowerShell)
```powershell
cd "C:\Workspace\Amygdala"
Unblock-File -Path .\Amygdala_Intel.ps1
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\Amygdala_Intel.ps1

## 🎥 Demo: Amygdala Protocol Run: https://youtu.be/3exjn3efiZ4

## 🛡️ Amygdala Protocol System Event – July 14, 2025

**Summary:**  
On July 14, 2025, following a system reboot intended to resolve a hardware issue (printer connectivity), Amygdala Protocol executed a deferred maintenance cycle. During this process, the system displayed a black screen for approximately 30 minutes before requiring a manual power-down and BIOS inspection. Upon restart, the BIOS reflected the latest firmware version, and Windows booted successfully.

**Details:**  
- **Protocol**: Amygdala Protocol  
- **Trigger**: Manual reboot  
- **Actions Executed**:
  - BIOS-level update (confirmed post-reboot)
  - Custom drivers (`ipf_cpu`, `ipf_acpi`, `ipf_lf`) loaded via demand-start behavior
  - No persistent system errors post-execution  
- **Observed Anomaly**:
  - Extended black screen duration during protocol execution
  - Event ID 56 registered by `Application Popup`, referencing `ipf_cpu` with incomplete message metadata
- **Outcome**:  
  System integrity preserved; BIOS updated successfully; no recurring errors detected across logs or runtime.

**Conclusion:**  
Amygdala Protocol completed its cycle and executed low-level actions as intended. The temporary screen blackout aligns with BIOS-level operations and no further anomalies have been detected. This event is documented for transparency and future reference.


