<p align="right">
  <a href="README_FA.md"> <strong>فارسی</strong></a>
</p>

---

# Hide or Show "Learn about this picture" Desktop Icon

Windows Spotlight automatically delivers high-quality daily wallpapers to your desktop. However, modern Windows 10 and Windows 11 updates force an unmovable **"Learn about this picture"** icon directly onto the desktop.

This repository provides simple, one-click Windows Registry (`.reg`) files to remove or restore this icon while keeping dynamic Windows Spotlight wallpapers fully functioning.

---

## 📁 Repository Contents

| File | Registry Value | Action |
| :--- | :--- | :--- |
| **`Hide Learn about this picture.reg`** | `dword:00000001` | Hides the icon from the desktop. |
| **`Show Learn about this picture.reg`** | `dword:00000000` | Restores the icon to default visibility. |

---

## ✨ Features

- **🖼️ Keeps Spotlight Wallpapers Active:** Only the unnecessary desktop shortcut icon is hidden; your daily rotating wallpapers remain completely untouched.
- **⚡ Instant & Native:** Uses native Windows Registry settings (`HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel`).
- **🚫 Zero Background Processes:** No third-party software, utilities, or background scripts required.
- **🔄 Fully Reversible:** Easily restore the icon at any time using the companion `.reg` file.
- **👤 Per-User Scope:** Targets `HKEY_CURRENT_USER`, meaning it doesn't modify system-wide files or break system integrity.

---

## 🚀 How to Use

1. Clone or download this repository.
2. Choose your desired action:
   - To **hide** the icon: Double-click **`Hide Learn about this picture.reg`**.
   - To **show** the icon: Double-click **`Show Learn about this picture.reg`**.
3. Click **Yes** when prompted by the Windows Registry Editor confirmation dialog.
4. Right-click on an empty spot on your desktop and select **Refresh** (or press **F5**) to apply the changes immediately.

---

## 💻 System Requirements

- **OS:** Windows 10 or Windows 11 (with Windows Spotlight enabled).
