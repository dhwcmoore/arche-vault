---
zettel_id: 20250611VS
tags: [#index, #setup, #infrastructure]
title: Vault State and Configuration
---

# 📦 Vault State — 2025-06-11

This note records the canonical configuration and expected operating environment for the ARCHE Vault.

---

## ✅ Canonical Vault Path

```
C:\ARCHETYPE\ARCHE_Vault
```

- This location is intentionally outside OneDrive
- Avoid storing the vault in `Documents`, `Desktop`, or any synced folder
- This reduces sync conflicts and preserves local integrity

---

## 🔁 Drop Integration Workflow

1. Download future drops (zip files)
2. Extract directly into `C:\ARCHETYPE\ARCHE_Vault`
3. Choose **Replace files** if prompted
4. Obsidian will auto-refresh content

---

## 🧠 Vault Philosophy

- Uses **Zettelkasten-style atomic notes**
- Organized by folders: `Modules`, `Concepts`, `Contracts`, `Zones`, etc.
- Interlinked through [[20250610M - ARCHE Master Log Index]] and tag backlinks

---

## 🗃 Git/GitHub (optional)

If version controlled:
- Init from `C:\ARCHETYPE\ARCHE_Vault`
- GitHub repo: `https://github.com/dhwcmoore/arche-vault.git`

---

## 📌 Last Verified State

- Current as of: 2025-06-11
- Vault version: [[Drop_20250611_Summary]]
- Graph view validated
- Vault integrated into offline clean path
