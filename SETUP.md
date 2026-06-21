# Setup Guide — GitHub Profile @0xAre

Step-by-step instructions to deploy the profile README, enable GitHub Pages, and optimize your GitHub account settings.

---

## CRITICAL: Share README to Profile

If your profile at [github.com/0xAre](https://github.com/0xAre) still shows only **Pinned** repos and **Contributions** (no custom README above them), the README exists in the repo but is **not linked to your profile yet**.

**Fix (1 minute):**

1. Open [github.com/0xAre/0xAre](https://github.com/0xAre/0xAre)
2. Look at the **right sidebar** (About section) or the **green banner** at the top of the repo
3. Click **"Share to profile"** (or **"Add to profile"**)
4. Hard-refresh your profile: `Ctrl + Shift + R`
5. Verify in incognito: [github.com/0xAre](https://github.com/0xAre)

This step is required when the repo was created via CLI instead of GitHub's "Add README" UI flow. See [GitHub Docs — Managing your profile README](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme).

---

## 1. Create the Profile Repository

1. Go to [github.com/new](https://github.com/new)
2. Set **Repository name** to exactly `0xAre` (must match your username)
3. Set visibility to **Public**
4. Do **not** initialize with README (we already have one locally)
5. Click **Create repository**

---

## 2. Push Local Files

Open a terminal in this workspace (`e:\Project APP\Profil GIthub`) and run:

```bash
git init
git add README.md docs/ SETUP.md
git commit -m "Add professional profile README and portfolio"
git branch -M main
git remote add origin https://github.com/0xAre/0xAre.git
git push -u origin main
```

### Alternative: GitHub CLI

If `gh` is authenticated:

```bash
gh auth login
gh repo create 0xAre/0xAre --public --source=. --remote=origin --push
```

---

## 3. Enable GitHub Pages

This repository (`0xAre/0xAre`) publishes a **project site**, not your account root URL.

| Site type | Repository | Live URL |
|-----------|------------|----------|
| **Project site (this setup)** | `0xAre/0xAre` with `/docs` | **https://0xare.github.io/0xAre/** |
| **User site (optional)** | Separate repo named `0xAre.github.io` | **https://0xare.github.io** (root only) |

Steps for the project site:

1. Open [github.com/0xAre/0xAre/settings/pages](https://github.com/0xAre/0xAre/settings/pages)
2. Under **Build and deployment** → **Source**, select **Deploy from a branch**
3. Set **Branch** to `main` and **Folder** to `/docs`
4. Click **Save**
5. Wait 1–3 minutes for deployment
6. Your portfolio will be live at: **https://0xare.github.io/0xAre/**

> **Note:** `https://0xare.github.io` without `/0xAre/` only works if you create and deploy a **user/organization** Pages repo (`0xAre.github.io`). The profile README repo alone does not serve the root domain.


---

## 4. Profile Settings Checklist

Go to [github.com/settings/profile](https://github.com/settings/profile) and update:

| Field | Value |
|-------|-------|
| **Name** | `Andika Aryansyach` |
| **Company** | `Daemon Protocol` |
| **Bio** | `Founding Engineer @ Daemon Protocol · Full-Stack & Security · Desktop · Android · SaaS · Poltek SSN` |
| **Pronouns** | `he/him` |
| **Website** | `https://0xare.github.io/0xAre/` |
| **Email** | `aryansyach4@gmail.com` (keep public if desired) |

Update via CLI (requires `user` scope):

```powershell
gh auth refresh -h github.com -s user
gh api -X PATCH user -f company="Daemon Protocol" -f bio="Founding Engineer @ Daemon Protocol · Full-Stack & Security · Desktop · Android · SaaS · Poltek SSN"
```

### Pinned Repositories

Keep these four pinned (order by priority):

1. [caraka-dekstop](https://github.com/0xAre/caraka-dekstop)
2. [CryptoSuite](https://github.com/0xAre/CryptoSuite)
3. [RunIT](https://github.com/0xAre/RunIT)
4. [SARX-128](https://github.com/0xAre/SARX-128)

---

## 5. Repository Descriptions & Topics

### RunIT — Description (copy-paste)

Go to [github.com/0xAre/RunIT/settings](https://github.com/0xAre/RunIT/settings) → **General** → **Description** and paste:

```
AI-native event execution SaaS — Next.js, Gemini agents, Firebase, live mission-control dashboard.
```

### Repository Topics

Add these topics to each pinned repository via **About** section (gear icon on repo page):

| Repository | Topics |
|------------|--------|
| **caraka-dekstop** | `rust`, `tauri`, `cryptography`, `mesh-networking`, `privacy` |
| **CryptoSuite** | `cryptography`, `react`, `typescript`, `education` |
| **RunIT** | `ai`, `nextjs`, `firebase`, `saas`, `event-management`, `typescript` |
| **SARX-128** | `cryptography`, `stream-cipher`, `c`, `ieee`, `security` |

### SARX-128 — Suggested Description

```
SARX-128: A lightweight sponge-based stream cipher with Speck block cipher — IEEE published research with C implementation.
```

---

## 6. Verify Everything Works

- [ ] Profile README renders at [github.com/0xAre](https://github.com/0xAre)
- [ ] GitHub Pages loads at [0xare.github.io](https://0xare.github.io/0xAre/)
- [ ] Website field in profile points to Pages URL
- [ ] All four pinned repos have descriptions and topics
- [ ] RunIT description is set (no longer blank)
- [ ] Bio reflects Full-Stack & Security + Founding Engineer @ Daemon Protocol
- [ ] Company field set to `Daemon Protocol`

---

## 7. Optional Enhancements

- IEEE links are already included in `README.md` and `docs/index.html`:
  - Xplore: https://ieeexplore.ieee.org/document/11324550
  - DOI: https://doi.org/10.1109/ICCED68324.2025.11324550
- Update SARX-128 repo description with the IEEE link when convenient
- Add a `CITATION.cff` to SARX-128 for academic discoverability

---

## File Structure

```
0xAre/
├── README.md          # Profile README (shown on github.com/0xAre)
├── SETUP.md           # This guide
└── docs/
    ├── index.html     # GitHub Pages landing page
    └── style.css      # Portfolio styling
```
