# Walkers Software — Company Site

The official site for **Walkers Software Development LLC**, an Atlanta-based software studio building custom web and mobile applications, automation systems, and AI integrations for startups and growing businesses.

🌐 **Live:** [dre15w1.github.io/WalkersSoftware](https://dre15w1.github.io/WalkersSoftware/)
🎯 **Custom domain (pending DNS):** walkerssoftware.com

---

## About

Single-file static site (`index.html`) — no build step, no dependencies except Google Fonts.

**Sections:** Hero · Services · Selected Work · Process · Tech Stack · Studio · Contact

**Design system:**
- Fonts: Space Grotesk (display), Inter (body), JetBrains Mono (labels)
- Palette: Dark slate `#0b0e11` · Electric teal `#2dd4a7`
- Aesthetic: Engineering studio — grid textures, terminal accents

---

## Custom Domain Setup (walkerssoftware.com)

### Step 1 — GitHub side
1. Repo **Settings → Pages**
2. Under "Custom domain," enter `walkerssoftware.com`
3. Save (GitHub creates a CNAME file in the repo automatically)
4. Check "Enforce HTTPS" once the cert is issued (~15 min after DNS propagates)

### Step 2 — DNS side (at your domain registrar)
Add these records:

| Type  | Host | Value |
|-------|------|-------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| CNAME | www  | dre15w1.github.io |

DNS propagation takes minutes to a few hours. After that, the site serves at `https://walkerssoftware.com` with a free auto-renewed certificate.

---

## Updating the Site

All content lives in `index.html`. Edit and commit — GitHub Pages redeploys automatically in ~30 seconds.

© 2026 Walkers Software Development LLC · Atlanta, GA
