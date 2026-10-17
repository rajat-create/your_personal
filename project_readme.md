# ❤️ Something Special For You — Romantic Proposal Website

A cute, interactive, and mobile-responsive web application designed to ask your special someone the big question! Built with a single self-contained `index.html` file, it allows you to generate a personalized link with her name that leads into a playful, heartwarming proposal experience.

---

## ✨ Features

* **🔗 Two-in-One URL Logic:**
  * **Creator Mode (`index.html`):** When opened without a URL parameter, it displays a setup card where you can type her name, generate a custom shareable link (`?name=HerName`), copy it with one click, or preview the experience directly.
  * **Recipient Mode (`index.html?name=Sophia`):** When she opens your custom link, the setup screen is automatically hidden and the personalized romantic experience begins immediately.
* **💖 3-Stage Interactive Proposal Flow:**
  * **Screen 1 (Welcome):** Greets her by name inside a soft glassmorphism card with an animated beating heart.
  * **Screen 2 (The Question):** Asks *"[Her Name], do you love me?"* alongside a cute bear illustration holding a heart.
  * **Screen 3 (Celebration):** Triggers a multi-cannon romantic confetti burst and a joyful celebration message when she clicks **"Yes! 💕"**.
* **🏃‍♂️ Playfully Evasive "No" Button:** Hovering over (desktop) or tapping (mobile) the **"No 😢"** button makes it jump to a random safe spot on the screen, cycles through cute pleading messages (*"Are you sure? 🥺"*, *"Think again! 💭"*), and makes the **"Yes! 💕"** button grow bigger with each attempt.
* **🌸 Romantic Aesthetic:** Features a pastel rose-pink gradient background, floating heart particles, glassmorphism UI cards, and Google Fonts (*Dancing Script* & *Poppins*).
* **📱 100% Mobile & Desktop Responsive:** Touch-friendly evasion logic ensures the "No" button works smoothly on smartphones as well as laptops.

---

## 🚀 Quick Start & Deployment

Because the entire project lives inside a single `index.html` file with zero build steps, you can host it for free in under a minute:

### Option 1: GitHub Pages (Recommended)
1. Upload `index.html` and this `README.md` to a public GitHub repository.
2. Go to **Settings** → **Pages** in your repository.
3. Under **Build and deployment** → **Branch**, select `main` (or `master`) and click **Save**.
4. Wait ~60 seconds, then open your live URL (`https://your-username.github.io/your-repo-name/`).

### Option 2: Netlify Drop
1. Place `index.html` inside a folder on your computer.
2. Go to [Netlify Drop](https://app.netlify.com/drop) and drag the folder into the browser window.
3. *(Tip)* Go to **Site configuration** → **Change site name** to customize your URL (e.g., `for-my-love.netlify.app`).

---

## 💌 How to Send It to Her

1. Open your deployed website link in your browser.
2. Type her name in the **"Her Name ❤️"** input box and click **Generate Proposal Link ✨**.
3. Click the **Copy** button next to the generated URL (it will look like `https://your-site.com/?name=HerName`).
4. Send that copied link to her via WhatsApp, Instagram, or iMessage!

---

## 🛠️ Tech Stack

* **HTML5** — Semantic structure and custom SVG illustrations
* **Tailwind CSS (CDN)** — Responsive styling, gradients, and glassmorphism
* **Vanilla JavaScript** — URL parameter parsing (`URLSearchParams`), DOM state management, and viewport collision-safe button evasion
* **Canvas Confetti** — Celebration particle effects (`canvas-confetti`)
* **Google Fonts** — *Dancing Script* & *Poppins*

---

## 🎨 Easy Customization

Want to tweak the messages? Open `index.html` in any text editor and look for:
* **The Question Text:** Search for `do you love me?` or `Will you be mine forever?` around line 265 to customize the prompt.
* **Pleading Messages:** Edit the `pleadingMessages` array inside the `<script>` tag to add your own inside jokes or cute phrases.

---

## 📄 License

This project is open-source and free to use. Good luck with your proposal! 💍✨