# VaultWrite ✍️

VaultWrite is an ultra-premium, dark-themed, glassmorphic Markdown Editor and Document Workspace designed to run locally on your computer. It allows you to select a directory on your machine to save, read, and delete markdown files directly, keeping your data private and ready to be pushed to GitHub.

## Features

- 📂 **Local Directory Connection**: Connect directly to your local workspace folder using the modern Web File System Access API.
- 💾 **Automatic Sandbox Fallback**: Automatically falls back to browser `localStorage` if directory access is not granted.
- 👁️ **Realtime Markdown Preview**: Split-pane interface showing compiled HTML output in real time.
- 📊 **Metrics Tracker**: Live word count, character count, and reading time estimation.
- 🛠️ **GitHub Sync Panel**: A custom instructions pane showing the exact Git commands required to stage, commit, and push your data to GitHub.
- 🎨 **Premium Glassmorphic Design**: Curated HSL colors, Outfit and Inter font families, micro-animations, and glow effects.

## Quick Start

1. **Start the local server**:
   ```bash
   npm run dev
   ```
2. **Access the application**: Open [http://localhost:3000](http://localhost:3000) in Chrome, Edge, or any modern web browser.
3. **Connect a directory**:
   - Click **Connect Local Folder** in the top right.
   - Choose a folder on your computer (e.g., you can create a folder named `notes` inside this repository).
   - Click "Allow" on the browser prompt to give read/write permission.

## Uploading Data to GitHub

To sync your saved notes to your GitHub repository ([cairns1105-cyber/Gemini-Demo](https://github.com/cairns1105-cyber/Gemini-Demo)), run these commands in your PowerShell or terminal:

```powershell
# Navigate to the project directory
cd "c:\Users\sukol\OneDrive\Desktop\Gemini Demo"

# Stage all files (including new notes)
git add .

# Commit your changes
git commit -m "Update notes via VaultWrite"

# Push to your GitHub repository
git push origin main
```
