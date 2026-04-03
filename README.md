# FileSystem Batch Renamer for Godot

A powerful and user-friendly plugin for Godot Engine that allows you to rename folders and files directly within the FileSystem dock.  
Supports batch renaming with customizable casing styles including PascalCase and camelCase for both folders and files.

Ideal for organizing your project assets consistently and efficiently without leaving the editor.

---

## ✨ Features

- ✅ Recursively renames **folders** to **PascalCase** or **camelCase**
- ✅ Recursively renames **files** to **PascalCase** or **camelCase**
- ✅ Provides real-time feedback via UI labels
- ✅ Easy integration and use inside the Godot Editor
- ✅ Streamline your project organization workflow without switching tools

---

### ⚠️ Note about Godot UI refresh

After clicking the **Rename** button and seeing the feedback message, the folders and files **may not appear renamed immediately** in the FileSystem dock.

This is a known limitation of the Godot editor — it doesn't always refresh the file tree in real time.  
To force the UI to refresh and see the changes:

- Click outside of the Godot window (e.g., `Alt + Tab`)
- Minimize and restore the editor window  
These actions will typically cause the editor to reload the file structure and show the correct new names.

---

### 🔹 Ideal for:
- Batch-renaming folders before importing them into Godot
- Fast cleanup of messy asset directories
- Use in non-Godot workflows or to preprocess external asset packs

---

## 📦 Installation (Godot Plugin)

1. Download or clone the repository into your project under `res://addons/Rename/`.
2. Enable the plugin in **Project > Project Settings > Plugins**.
3. Use the UI panel to select a folder and start renaming.

---

## 🧩 Compatibility

- ✔️ Godot Engine 4.x
- ❗ Godot 3.x not officially supported (requires adjustments)

---

## 📄 License

MIT License

---

Contributions, feedback, and suggestions are welcome!
