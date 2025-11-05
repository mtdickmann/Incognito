<p align="left">
  <img src="MD_Logo.png" alt="Incognito Theme Logo" width="200"/>
</p>

# Incognito Theme  
**“VS Code in Notepad++ disguise.”**

A light, high-contrast theme designed for shell scripts, system editing, and anyone who wants VS Code to *look* like a classic text editor but *feel* like a modern IDE.

---

### 🌟 Features
- Notepad++-inspired layout with modern clarity  
- Subtle color coding for readability without eye strain  
- Ideal for Bash, Shell, and lightweight scripting  
- Designed for developers who miss simplicity  

---

### 🧩 Installation Options

You can install **Incognito Theme** in a few different ways — pick what fits you best.

---

#### ⚡ Option 1 – Install directly from GitHub (Recommended)

**🪟 Windows (PowerShell in VS Code):**
```powershell
Invoke-WebRequest -Uri "https://github.com/mtdickmann/Incognito/releases/download/v1.0.8/incognito-1.0.8.vsix" -OutFile "$env:TEMP\incognito.vsix"
code --install-extension "$env:TEMP\incognito.vsix"
```

**🐧 Linux / 🧠 macOS:**
```bash
curl -L -o /tmp/incognito.vsix https://github.com/mtdickmann/Incognito/releases/download/v1.0.8/incognito-1.0.8.vsix
code --install-extension /tmp/incognito.vsix
```

This downloads and installs the latest release directly — no manual download needed.

---

#### 🪟 Option 2 – Manual local install

If you prefer to download manually:

1. Go to the releases page:  
   [https://github.com/mtdickmann/Incognito/releases](https://github.com/mtdickmann/Incognito/releases)
2. Download the `.vsix` file (e.g. `incognito-1.0.8.vsix`)
3. Open **VS Code**
4. Use the menu: **View → Terminal** (or the Terminal tab at the bottom)
5. Run:
   ```bash
   code --install-extension "C:\Users\<YOUR_USERNAME>\Downloads\incognito-1.0.8.vsix"
   ```
6. Restart VS Code  
7. Open **Command Palette → Preferences: Color Theme → Incognito**

---

#### ☁️ Option 3 – Marketplace (Coming Soon)

Once published, you’ll be able to install it with a single command:
```bash
code --install-extension mtdickmann.incognito
```
Check the repo’s README or Marketplace listing for updates.

---

### 🔄 Updating the Theme
To update manually:
```bash
code --uninstall-extension mtdickmann.incognito
```
Then reinstall the latest `.vsix` using one of the methods above.

---

### ⚖️ License

This theme is provided under a **custom license** — you’re free to use, modify, and enjoy it personally or internally, but redistribution or resale without permission is prohibited.  

See [LICENSE.txt](./LICENSE.txt) for full details.

---

**© 2025 Michael Dickmann**  
*Play with it, improve it, enjoy it — but don’t sell it or claim it’s yours.*
