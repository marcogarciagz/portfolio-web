# Marco Garcia — Portfolio

Personal website/portfolio built with **HTML + Tailwind (CDN)**.  
Sections: Home, About, Experience, Projects, Skills, Certifications (badges), Sports (with race cards), and Contact.

## 🚀 Live
- GitHub Pages (default): `https://<your-username>.github.io/<repo-name>/`  
- Custom domain (optional): `https://marcogarciagz.com` (configure DNS + GitHub Pages)

> All image paths are **relative** (e.g., `images/...`, `icons/...`), so the site works under both GitHub Pages and a custom domain without changes.

---

## 🗂️ Project Structure

├─ index.html
├─ /images
│ ├─ background-mountains.jpeg
│ ├─ personal-photo.png
│ └─ /certs
│ ├─ aws-certified-ai-practitioner.webp
│ ├─ azure-data-fundamentals.webp
│ ├─ astronomer-airflow-3.webp
│ ├─ astronomer-dag-authoring-airflow-3.webp
│ ├─ professional-scrum-master.webp
│ └─ dataiku-advanced-designer.webp
├─ /icons
│ ├─ github.svg
│ ├─ linkedin.svg
│ ├─ medium.svg
│ ├─ strava.svg
│ └─ /flags
│ ├─ ch.svg
│ ├─ es.svg
│ └─ it.svg
└─ face-photo.png


> If you *ever* add folders or files that start with `_` (underscore), add a `.nojekyll` file in the repo root so GitHub Pages doesn’t ignore them.

---

## 🧰 Tech

- **Tailwind CSS (CDN)**  
- **Google Fonts** (Inter)  
- **Material Symbols** (icons)

No build step required. Just open `index.html` in a browser or deploy.

---

## ▶️ Local Preview

Just open `index.html` in your browser.  
If you prefer a local server:

```bash
# Python
python3 -m http.server 5500

# Node (http-server)
npx http-server -p 5500

Then visit http://localhost:5500