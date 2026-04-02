# Murali Krishna Bezawada — Portfolio

Personal portfolio website for Murali Krishna Bezawada, Data Scientist & ML Engineer based in Chicago, IL.

## Live Site

🌐 [Your domain here] — hosted via GitHub Pages

## Tech Stack

- Pure HTML/CSS/JavaScript — no frameworks, no build tools
- Google Fonts (Cormorant Garamond + DM Sans)
- Deployed via GitHub Pages

## Folder Structure

```
portfolio/
├── index.html                          # Main portfolio page
├── assets/
│   └── Murali_Krishna_Bezawada_Resume.pdf   # Resume (add your PDF here)
├── CNAME                               # Custom domain config
└── README.md
```

## Setup Instructions

### 1. Add your resume PDF

Place your resume PDF in the `assets/` folder and name it exactly:
```
Murali_Krishna_Bezawada_Resume.pdf
```

### 2. Deploy to GitHub Pages

1. Push this repo to GitHub (repository name: `your-username.github.io` OR any name)
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Click **Save**

Your site will be live at `https://your-username.github.io` (or the repo subfolder URL).

### 3. Connect your custom domain

1. In the repo root, the `CNAME` file contains your domain — update it with your actual domain
2. Go to **Settings → Pages → Custom domain**, enter your domain and save
3. At your domain registrar (e.g. GoDaddy, Namecheap), add these DNS records:

**For apex domain (yourdomain.com):**
| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

**For www subdomain:**
| Type | Name | Value |
|------|------|-------|
| CNAME | www | your-username.github.io |

4. DNS changes can take up to 24 hours to propagate
5. Once active, enable **Enforce HTTPS** in GitHub Pages settings

## Contact

- Email: muralibezawada01@gmail.com
- LinkedIn: [linkedin.com/in/murali-krishna-bezawada-a39b46206](https://linkedin.com/in/murali-krishna-bezawada-a39b46206)
- GitHub: [github.com/MURALIKRISHNABEZAWADA](https://github.com/MURALIKRISHNABEZAWADA)
