# 🎨 synCodx_vsCode_Theme 💻✨

Welcome to my **Custom VS Code Theme**! 🚀 This theme is designed to give you a fresh and modern coding experience with a sleek, professional touch. Prefer dark mode, this theme has you covered for an optimal coding environment. 🌟

---

## ⚡ Features
- 🎨 **Custom color scheme** for a vibrant, yet balanced feel.
- 🖥️ **Syntax highlighting** for all major programming languages.
- 🌗 **Dark mode** support – perfect for any time of day!
- 🔧 Optimized for popular extensions like **Prettier**, **ESLint**, and more.
- 👁️‍🗨️ Tailored to enhance focus and reduce eye strain.

---

![enter image description here](synCodx.png?raw=true)

---

## ⚙️ Instructions

 1. Give this repo a star and also [outrun-meets-synthwave-repo](https://marketplace.visualstudio.com/items?itemName=codevars.outrun-meets-synthwave) + [synthwave-x-fluoromachine-epic-animations-repo](https://github.com/thecodemonkey/synthwave-x-fluoromachine-epic-animations) (If Not This Won't Work For You LOL Come On Guys it's free)
 2. Install vs code extension [Outrun Meets Synthwave](https://marketplace.visualstudio.com/items?itemName=codevars.outrun-meets-synthwave)
 3. Install vs code extension [Bearded Icons](https://marketplace.visualstudio.com/items?itemName=BeardedBear.beardedicons) 
 4. Install vs code extension [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) 
 5. Download MonoLisa Nerd Font Mono (monolisa it's the one I use super clean).
 6. on vs code open up the user settings cmd + p then search for user settings and copy the settings on the settings.json file from this repo ( if you want it exactly like mines paste it at the bottom if you don't want to override your own settings then paste it at the top of file)
 7. Replace the `vscode_custom_css.imports` depending your operative system, and add your user or file location in your VS Code `settings.json` 
```js
On Mac:

{
  "vscode_custom_css.imports": [
    "file:///Users/{your username}/.vscode/extensions/codevars.outrun-meets-synthwave-0.0.1/synthWaveStyles.css"
    ]
}

Windows:

{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{your username}/.vscode/extensions/codevars.outrun-meets-synthwave-0.0.1/synthWaveStyles.css"
    ]
}

Linux:
{
    "vscode_custom_css.imports": [
        "file:///home/{your username}/.vscode/extensions/codevars.outrun-meets-synthwave-0.0.1/synthWaveStyles.css"
    ]
}
```
8. Copy and paste the css inside of the `syncodx-style.css` file and replace the styles inside the `synthWaveStyles.css` file

---

## 🔧 Customization

- Want to tweak the colors even more? 😎 You can customize the theme further by editing the `settings.json` file in your workspace.
- Change individual elements like **keywords**, **strings**, or **functions** to fit your style. ✨

---

## 🤝 Contributing

Want to improve this theme? Feel free to open issues or submit pull requests! Contributions are always welcome. 💪

---

Stay productive and keep coding with style! 💻🚀
