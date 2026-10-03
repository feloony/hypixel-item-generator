# ⚔️ SkyBlock Item Studio

A fast, browser-only editor for designing **Hypixel SkyBlock-style custom items** with a live tooltip preview and multiple export formats.

> **Unofficial community project.** Not affiliated with, sponsored by, or endorsed by Hypixel or Mojang.

## ✨ What you can do

- 🎨 Build items with name, rarity, category, SkyBlock ID, and Minecraft material
- 👀 See a **live in-game-style tooltip preview** while editing
- 📊 Configure Strength, Crit Chance, Crit Damage, Intelligence, Health, Defense, Speed, Ferocity, Magic Find, and Attack Speed
- 📖 Add multi-line lore and source/flavor text
- ✨ Add enchantments and custom abilities with mana costs
- 💾 Automatically save drafts to `localStorage`
- 🎲 Generate a randomized starter item
- 📦 Export as Java, JSON, or a Minecraft `/give` command
- ⬇️ Download generated Java directly
- 📋 Copy generated output or tooltip text
- 📱 Responsive layout for desktop and mobile
- 🔒 No account, backend, database, or server required

## 🚀 Run locally

```bash
git clone https://github.com/feloony/hypixel-item-generator.git
cd hypixel-item-generator
```

Open `index.html` in a modern browser. There are no build steps or dependencies.

## 🧩 Workflow

1. Enter the item identity.
2. Choose rarity and category.
3. Add lore, stats, enchantments, and an optional ability.
4. Watch the tooltip update instantly.
5. Generate Java, JSON, or a Minecraft command.
6. Copy the result or download the Java output.

## 🛠️ Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- Browser `localStorage` and Clipboard APIs

## 📁 Structure

```text
hypixel-item-generator/
├── index.html
├── script.js
├── style.css
├── screenshot1.png
└── README.md
```

## 🌐 Deploy

Because this is a static browser application, it works with GitHub Pages, Cloudflare Pages, Netlify, Vercel, or any static web host.

## 🤝 Contributing

Ideas, UI improvements, new export formats, item properties, and bug fixes are welcome. Keep the project dependency-free where practical.

## 📜 Disclaimer

Hypixel SkyBlock, Hypixel, Minecraft, and related names/assets belong to their respective owners. This project is an independent community tool for experimentation and education.

## 📄 License

MIT License. See [`LICENSE`](LICENSE).

⭐ If this tool helps you, consider starring the repository.
