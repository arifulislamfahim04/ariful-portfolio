# Your Website — How to Use This

This is a normal website (HTML/CSS/JS in one file, `index.html`), not a Blogger theme. That's on purpose: it works anywhere, it's easier to edit, and nothing is "hard-coded" against you — every section pulls from your actual resume and LinkedIn.

## What's in this folder

```
index.html                          → the whole website (open it in any browser to preview)
assets/profile.jpg                  → your photo (pulled from your resume PDF)
assets/Ariful_Islam_Fahim_Resume.pdf → your CV, linked to the "Download CV" button
README.md                           → this file
```

## Put it online for free with GitHub Pages (10 minutes)

1. Go to github.com and log into your account.
2. Click the **+** in the top right → **New repository**.
3. Name it something like `ariful-portfolio`. Keep it **Public**. Click **Create repository**.
4. On the new repo page, click **uploading an existing file**.
5. Drag in `index.html` and the whole `assets` folder, then click **Commit changes**.
6. Go to the repo's **Settings** tab → **Pages** (left sidebar).
7. Under "Build and deployment", set **Source** to **Deploy from a branch**, branch **main**, folder **/ (root)**. Click **Save**.
8. Wait about a minute, then refresh — GitHub will show you a live link like:
   `https://yourusername.github.io/ariful-portfolio/`

That link is your website. Share it anywhere — LinkedIn, your CV, job applications.

## How to edit things yourself later

You don't need to code. Open `index.html` in any text editor (even Notepad, or GitHub's own editor — click the pencil icon on the file in your repo) and change the **text between the tags**. For example:

```html
<h3>Textile Engineering Intern</h3>
```

Just change the words between `<h3>` and `</h3>`. Don't touch anything with `<` or `>` in it unless you're sure — that's what holds the page together.

To swap your photo: replace `assets/profile.jpg` with a new photo of the same name (crop it roughly square first).

To update your CV: replace `assets/Ariful_Islam_Fahim_Resume.pdf` with a new PDF, keeping the exact same file name — the Download button will then serve your newer file automatically.

## About the parts you asked about

- **Download CV button** — now links to your real resume PDF and downloads it.
- **Contact form** — has no server behind it (a static site like this can't send emails on its own). Right now, clicking "Send message" opens the visitor's own email app with a message pre-filled to you. It always works, with zero setup.
  - If you'd like a form that submits silently without opening an email app, sign up free at [formspree.io](https://formspree.io), get your form endpoint, and I can wire it in — just ask.
- **Map** — a real, working Google Maps embed of Dhaka. No API key needed for this basic version.
- **Get in touch / nav links** — all scroll to the right section on the same page now.
- **Social icons** — LinkedIn, email, and phone, all with proper hover contrast (no invisible-on-blue icons).
- **Freelance / "on vacation" banner, pricing, testimonials** — removed. They didn't fit a student's portfolio and you had no content for them. Replaced with an "Open to internship / trainee roles" tag in the hero.
- **Footer credit** — added, with a working LinkedIn link.

## One thing I noticed while combining your CV and LinkedIn

Your CV lists CGPA as 3.90/4.00, while your LinkedIn summary says 3.91/4.00. I used 3.90 (matching your CV, which also states it in the education section) — worth double-checking which is accurate before this goes live.
