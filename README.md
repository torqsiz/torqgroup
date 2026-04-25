# TORQ Group Website

## Files

```
torq/
├── index.html        ← Home page
├── industries.html   ← Industries (anchor links: #construction, #logistics, #industrial, #facilities)
├── services.html     ← Services
├── about.html        ← About
├── contact.html      ← Contact (form → WhatsApp)
└── README.md
```

## BEFORE YOU GO LIVE — Replace the Phone Number

Search and replace `27000000000` across all 5 HTML files with your actual WhatsApp number in international format (no +, no spaces):

**Format:** `27XXXXXXXXX`
**Example:** If your number is 071 234 5678 → use `27712345678`

Do a global find/replace in any code editor (VS Code, Notepad++):
- Find: `27000000000`
- Replace: `27XXXXXXXXX`

This will update all WhatsApp links and the phone display on the contact page simultaneously.

---

## Deploy on Netlify (Free)

1. Go to [netlify.com](https://netlify.com) and create a free account
2. From the dashboard, click **"Add new site"** → **"Deploy manually"**
3. Drag and drop the `torq/` folder into the upload area
4. Your site will be live at a `.netlify.app` URL within seconds
5. To use a custom domain: Site settings → Domain management → Add custom domain

---

## Deploy on Vercel (Free)

1. Go to [vercel.com](https://vercel.com) and create a free account
2. Click **"Add New Project"** → **"Browse"**
3. Upload or connect the `torq/` folder
4. Click **Deploy** — done
5. Custom domain: Project settings → Domains

---

## Deploy via GitHub + Netlify/Vercel (Recommended for Updates)

1. Create a GitHub account and a new repository
2. Upload the contents of the `torq/` folder to the repository
3. Connect Netlify or Vercel to the GitHub repo
4. Any future changes you push to GitHub will auto-deploy

---

## Notes

- No build step needed — these are plain HTML files
- No backend or server required — fully static
- WhatsApp links work on all devices (desktop and mobile)
- The contact form converts inputs into a pre-filled WhatsApp message
- All CTAs route exclusively to WhatsApp — no email dependency
- Mobile responsive on all pages
