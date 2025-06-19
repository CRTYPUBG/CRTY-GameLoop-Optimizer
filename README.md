# CRTY GameLoop Optimizer

**CRTY GameLoop Optimizer** is an easy-to-use PowerShell-based optimization tool designed to boost FPS and improve performance for Tencent GameLoop on Windows.

---

![CRTY GameLoop Optimizer Screenshot](https://raw.githubusercontent.com/CRTYPUBG/CRTY-GameLoop-Optimizer/refs/heads/main/screenshot.png)

---

## Features

- Sets CPU power plan to High Performance mode.
- Disables Superfetch (SysMain) service to reduce unnecessary background processes.
- Disables unnecessary system services.
- Increases GameLoop process priority for smoother gameplay.
- Disables TCP autotuning to help reduce network lag.
- Allows easy rollback of applied optimizations.

---

## Usage

1. Open PowerShell **as Administrator**.  
2. Download or copy the `CRTY_GameLoop_Optimizer.ps1` script file.  
3. Run the script:  
   ```powershell
   .\CRTY_GameLoop_Optimizer.ps1
