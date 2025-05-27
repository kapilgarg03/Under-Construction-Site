# 🚧 Under Construction Site

A simple, reusable **"Under Construction"** static site. Use this template to temporarily host a placeholder page for domains under development.

---

## ✨ Features

- Animated background with [particles.js](https://vincentgarreau.com/particles.js/)
- Responsive, modern design
- Light/Dark mode toggle
- Animated progress bar
- Social and contact links in the footer
- Easy customization via template variables

---

## 🚀 Usage

1. **Clone this repository** to your domain or web server.

2. **Set your site title:**
   - Replace `{{SITE_TITLE}}` in `index.html` with your desired site name.
   - Or, use the provided GitHub Actions workflow to inject the title automatically (via Repository Secrets).

3. **Customize content:**
   - Edit the message, social links, and contact info in `index.html` as needed.
   - Adjust styles in `style.css` if desired.
   - Tweak particle effects in `particles.json`.

4. **Deploy:**
   - Upload the files to your web host, or
   - Use the included GitHub Actions workflow to deploy to GitHub Pages.

---

## 🖥 Preview Locally

To test changes before deploying, you can run a local server:

```bash
	python -m http.server
```

Then open [http://localhost:8000](http://localhost:8000) in your browser to view the site.

---

## 🛠 GitHub Pages Deployment (via GitHub Actions)

This project includes a GitHub Actions workflow for automatic deployment:

1. Go to your GitHub repo → **Settings** → **Secrets and variables** → **Actions**
2. Add the following secrets:
   - `SITE_TITLE` — Your desired site title
   - `CUSTOM_DOMAIN` — Your domain (e.g., `quantleaf.in`)
   - `GH_PAT` — A GitHub Personal Access Token with `repo` scope

> 🔐 A PAT is required because the workflow pushes to the `gh-pages` branch.

---

## 🙏 Credits

- 🎆 Background animation powered by [particles.js](https://vincentgarreau.com/particles.js/)
- 🧩 Icons from [Simple Icons](https://simpleicons.org/)

---

## 📄 License

**MIT License** — free to use and modify.
