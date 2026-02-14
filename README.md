# Paulo H. Resende — Academic Website

This folder contains all the customized content files for your GitHub Pages academic website,
built on the [AcademicPages](https://github.com/academicpages/academicpages.github.io) Jekyll template
(the same template used by piaiaabreu.github.io).

---

## 🚀 Setup Steps (do these once)

### Step 1 — Fork the template

1. Go to: https://github.com/academicpages/academicpages.github.io
2. Click **"Use this template"** → **"Create a new repository"**
3. Name it exactly: `YOURUSERNAME.github.io`  (e.g. `paulohresende.github.io`)
4. Set visibility to **Public**
5. Click **"Create repository"**

### Step 2 — Enable GitHub Pages

1. In your new repo, go to **Settings** → **Pages** (left sidebar)
2. Under "Source", select **"Deploy from a branch"**
3. Branch: `main`, Folder: `/(root)` → click **Save**
4. Wait ~5 minutes, then visit `https://YOURUSERNAME.github.io`

---

## 📁 Files in this package and where to paste them

For each file below, go to your repo on GitHub, navigate to the path,
click the pencil ✏️ icon to edit, paste the content, and click **"Commit changes"**.

| File in this package        | Paste it to (in your repo)          | What it controls                        |
|-----------------------------|--------------------------------------|-----------------------------------------|
| `_config.yml`               | `_config.yml` (root)                | Your name, bio, social links, site URL  |
| `_pages/about.md`           | `_pages/about.md`                   | Your homepage "About me" text           |
| `_pages/research.md`        | `_pages/research.md`                | Papers, projects, thesis                |
| `_pages/talks.md`           | `_pages/talks.md`                   | Conference presentations                |
| `_pages/grants.md`          | `_pages/grants.md`                  | Fellowships, grants, awards             |
| `_pages/cv.md`              | `_pages/cv.md`                      | CV overview + PDF download link         |
| `_data/navigation.yml`      | `_data/navigation.yml`              | Top navigation menu links               |

---

## 🖼️ Uploading your photo

1. In your repo, go to the `images/` folder
2. Click **"Add file"** → **"Upload files"**
3. Upload your photo and name it `profile.jpg`
4. That's it — it will appear automatically in the sidebar

## 📄 Uploading your CV PDF

1. In your repo, go to the `files/` folder
2. Upload your CV PDF and name it `Paulo_Resende_CV.pdf`
3. The CV page will link to it automatically

---

## ✏️ Personalizing _config.yml

Open `_config.yml` and update these lines:

```yaml
url: https://YOURUSERNAME.github.io        # ← your actual GitHub username
repository: "YOURUSERNAME/YOURUSERNAME.github.io"
author:
  github: "YOURUSERNAME"
  email: "paulo.resende@ttu.edu"
  googlescholar: "YOUR_SCHOLAR_URL"        # ← add if you have one
  orcid: "YOUR_ORCID"                      # ← add if you have one
  linkedin: "YOUR_LINKEDIN_USERNAME"       # ← add if desired
```

---

## 🔄 Making future updates

After the initial setup, you can edit any `.md` file directly on GitHub
(click the file → pencil icon → edit → commit). Changes go live in ~2–5 minutes.

---

*Built with [AcademicPages](https://github.com/academicpages/academicpages.github.io),
a Jekyll template for academic websites hosted on GitHub Pages.*
