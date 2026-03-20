# B B Debasis Sahoo — Portfolio Website

A modern, responsive personal portfolio for a Java Backend Developer.

## 🚀 Quick Start

No build step required — it's a single `index.html` file.

1. Open `index.html` in any browser — it works immediately.

---

## 📦 GitHub Pages Deployment

### Option A — Root deploy (simplest)
1. Create a GitHub repo named `username.github.io` (replace `username` with your GitHub username)
2. Upload `index.html` (and `B_B_DEBASIS_SAHOO_Resume.pdf`) to the repo root
3. Go to **Settings → Pages → Source → main branch / root**
4. Your site will be live at `https://username.github.io`

### Option B — Project repo
1. Create any GitHub repo (e.g., `portfolio`)
2. Upload `index.html` to the root
3. Go to **Settings → Pages → Source → main branch / root**
4. Site lives at `https://username.github.io/portfolio`

---

## 📄 Add Resume Download

1. Place your resume PDF in the same folder as `index.html`
2. In `index.html`, find `id="downloadBtn"` and change:
   ```html
   href="#"
   ```
   to:
   ```html
   href="./B_B_DEBASIS_SAHOO_Resume.pdf" download
   ```

---

## 🔗 Update Your GitHub Link

Search for `github.com/bbdebasis` in `index.html` and replace with your real GitHub URL.

---

## ✏️ Customizations

| What to change | Where in `index.html` |
|---|---|
| GitHub profile URL | All `href="https://github.com"` occurrences |
| LinkedIn URL | `href="https://www.linkedin.com/in/bb-debasis-sahoo-a8a1261a3"` |
| Resume PDF link | `id="downloadBtn"` href |
| Android / iOS app links | Project card anchor tags |
| Color scheme | `:root` CSS variables at top of `<style>` |

---

## 🎨 Design

- **Font**: Syne (display) + Fira Code (mono) + Outfit (body)
- **Theme**: Dark tech — deep navy with cyan accent
- **Features**: Grid background, scroll animations, intersection observer reveals,
  mobile hamburger menu, sticky nav with blur backdrop

---

## 📱 Browser Support

Chrome, Firefox, Safari, Edge — all modern browsers.
Mobile responsive down to 320px.
