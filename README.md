# GN PC Optimizer v2.0.0 (Standalone Portable)

**GN PC Optimizer** is a fast, standalone desktop utility designed to clean, optimize, and monitor Windows performance. Built using Python and PySide6, this application runs as a **portable `.exe`**, meaning no installer or setup wizard is required—simply download and run.

---

## 🚀 Highlights & Features

* **⚡ Portable / No Installation:** Runs directly as a single executable without writing setup files or modifying registry installation directories.
* **📊 Live System Monitor:** Displays real-time CPU usage, RAM utilization, system drive stats, and running processes.
* **🚀 One-Click RAM Trim:** Instantly releases unused working set memory across background processes.
* **🧹 Junk & Temp Cleaner:** Locates and clears temporary directories, system caches, Direct3D/NVIDIA shader caches, and Windows cache files.
* **🌐 Multi-Browser Cleaner:** Scans and removes web and GPU caches across Chrome, Edge, Brave, Opera, and Firefox.
* **📂 Large File Scanner:** Identifies files exceeding 100 MB across user folders (Downloads, Documents, Desktop) for quick space recovery.
* **🛡️ Built-in Quarantine System:** Files marked for deletion are safely relocated to a quarantine folder first, allowing easy one-click restoration.
* **⚙️ Startup Program Manager:** Inspects and removes unwanted startup programs directly from Windows Registry hives.
* **🎨 Modern UI & Theme Auto-Detection:** Seamless support for Light, Dark, and automatic System Theme modes.

---

## 📥 Download & Usage

### 1. Download
Grab the latest release file (`GN_PC_Optimizer.exe`) directly from the [Releases](../../releases) section or repo root.

### 2. Run Application
Double-click `GN_PC_Optimizer.exe` to launch immediately.

> **💡 Administrator Privileges Note:**  
> Running the `.exe` as **Administrator** enables full access to create Windows System Restore Checkpoints and manage system-wide (`HKLM`) startup items.

---

## 🛠️ Building the Standalone `.exe` from Source

If you wish to modify the Python source code and re-compile the standalone executable yourself using PyInstaller:

### Prerequisites
* Python 3.8+
* Dependencies:
  ```bash
  pip install PySide6 psutil pyinstaller
