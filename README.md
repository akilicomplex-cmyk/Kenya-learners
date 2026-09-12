# Kenya Learner Atlas

An interactive dashboard providing a clear view of primary-school learner enrolment across Kenya (CBC Grades 1–7, 2023 Baseline).

## 🚀 Live Demo & Publishing via GitHub Pages

This project is completely static, self-contained, and ready to be hosted immediately on **GitHub Pages** (or Netlify, Vercel, Cloudflare Pages, etc.).

### How to Publish to GitHub Pages:

1. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com/new) and create a new repository (e.g., `kenya-learner-atlas`).
2. **Push the Files**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Kenya Learner Atlas dashboard"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - In your repository, go to **Settings** > **Pages** (under Code and automation).
   - Under **Build and deployment** > **Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and folder `/ (root)`, then click **Save**.
   - Within 1–2 minutes, your dashboard will be live at `https://<your-username>.github.io/<your-repo-name>/`.

## 📁 Repository Structure

```text
├── index.html        # Main HTML shell (configured with relative asset paths for any base URL)
├── assets/
│   ├── index-B8IDDjVB.js   # Compiled application logic, data & interactive charts
│   └── index-C52vPEzP.css  # Original styling, color themes, and responsive layout
└── README.md         # Deployment and usage documentation
```

## 🎨 Features & Visual Identity
- **Original Colors & Aesthetics**: Exact palette (`#203b39` pine green, `#E87722` warm orange, warm off-white background, custom typography using Google Fonts `DM Sans` & `DM Serif Display`).
- **Interactive Views**:
  - **Overview**: High-level national snapshot, Top 12 county distribution, gender balance breakdown, grade-by-grade progress.
  - **Learner Journey**: CBC transition flow and grade progression.
  - **County Lens**: Deep-dive comparison across all 47 counties.
  - **Filters**: Real-time filtering by Region, County, and Comparison metrics (Enrolment, Girls share, Learners/school).
- **100% Self-Contained**: No external backend or database required; runs entirely in the browser.
