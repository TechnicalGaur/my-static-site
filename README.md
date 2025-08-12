# Static Website Hosting with GitHub Pages

A simple static website built with **HTML** and **CSS**, hosted for free using **GitHub Pages**.

---

## 📌 Project Overview
This project demonstrates how to deploy a static website using GitHub Pages.  
It includes a minimal HTML structure, basic CSS styling, and the setup required for free hosting directly from a GitHub repository.

---

## 🚀 Live Demo
🔗 **Website URL:** https://technicalgaur.github.io/my-static-site/

---

## 📂 Project Structure
.
├── .nojekyll # Disables Jekyll processing on GitHub Pages

├── index.html # Main HTML page

├── style.css # Stylesheet for the site

├── CNAME # (Optional) Custom domain configuration

└── README.md # Project documentation




---

## 🛠 Technologies Used
- **HTML5** – for structuring content
- **CSS3** – for styling
- **GitHub Pages** – for hosting

---

## 📦 Deployment Steps

### 1️⃣ Create a New Repository
1. Go to [GitHub](https://github.com/) and create a **new public repository**.
2. Name it as you like (for example: `my-static-site`).

### 2️⃣ Add Your Project Files
- Create `index.html` and `style.css`.
- Optionally add `.nojekyll` and `CNAME` (if using a custom domain).

### 3️⃣ Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit - static website"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

# 4️⃣ Enable GitHub Pages
Open your repository on GitHub.

Go to Settings → Pages.

Under Build and deployment, select:

Branch: main

Folder: / (root)

Click Save.

Your site will be published in a few seconds, and GitHub will show you the live URL.


# 🌐 Custom Domain (Optional)
If you own a domain and want to use it:

Create a CNAME file in the repository root with your domain name:

```www.example.com```

Update your domain DNS:

Add A records pointing to:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

Add a CNAME record for www pointing to:

```<your-username>.github.io```

Save changes in your domain provider’s DNS panel.


# 📜 License

This project is licensed under the MIT License – you can freely use and modify it.


# Screenshot



  <img width="1366" height="768" alt="Screenshot 2025-08-12 145441" src="https://github.com/user-attachments/assets/355202e1-31bf-45b3-92df-7e7cc10368a0" />







<img width="1366" height="768" alt="Screenshot 2025-08-12 145601" src="https://github.com/user-attachments/assets/55496cba-429e-41eb-bc24-6aaca343217e" />








<img width="1282" height="767" alt="Screenshot 2025-08-12 145356" src="https://github.com/user-attachments/assets/f2fd79b5-c801-4ad0-a00a-0eadb6f50216" />








