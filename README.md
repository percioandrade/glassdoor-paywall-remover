# Glassdoor Paywall Remover (Update)

This userscript removes annoying overlays and inline style restrictions on Glassdoor pages, allowing users to scroll and read content freely — even when a paywall or "ContentWall" is present.

> ✅ Works on Glassdoor pages with `.main` layout block and paywall overlays.

---

## 🚀 Features

- Hides paywall elements like:
  - `#HardsellOverlay`
  - `#ContentWallHardsell`
  - `#UserAlert`
- Unlocks scrolling on blocked pages.
- Removes inline styles that force fixed height/position.
- Observes and auto-corrects dynamic reapplication of styles using `MutationObserver`.

---

## 📦 Installation

To use this userscript, you'll need a userscript manager extension:

- [Tampermonkey (Chrome/Edge)](https://www.tampermonkey.net/)
- [Greasemonkey (Firefox)](https://www.greasespot.net/)

Once installed, click the link below to add the script:

👉 **[Install via GreasyFork](https://greasyfork.org/pt-BR/scripts/531857-glassdoor-paywall-remover-update)**

---

## 🛠 How it works

The script waits for the page to fully load, then:

1. Removes known paywall overlays.
2. Unlocks page scroll by removing inline CSS on `<body class="main">`.
3. Injects custom CSS to ensure scroll is restored on `<main>`.
4. Watches for any reapplication of the restrictive styles and removes them in real time.

---

## 📄 License

This project is licensed under the MIT License.  
Feel free to use, modify, and distribute!

---

## 🙌 Credits

Developed and maintained by the community.  
Originally inspired by the need to freely access Glassdoor reviews without intrusive overlays.

