# Buchanan Offices — Website (Komito Envato Template)

Premium flexible workspace website for Buchanan Offices, 166 Buchanan Street, Glasgow.  
Built on the **Komito HTML5 Envato template**.

---

## File Structure Required for GitHub

```
your-repo/
├── index.html              ← This file (Buchanan Offices content)
├── sitemap.xml             ← SEO sitemap
├── robots.txt              ← Crawler instructions  
├── CNAME                   ← Custom domain config
├── assets/                 ← FROM YOUR KOMITO TEMPLATE PURCHASE
│   ├── css/                ← All template CSS files
│   │   ├── bootstrap.css
│   │   ├── style.css
│   │   ├── responsive.css
│   │   ├── font-awesome-all.css
│   │   ├── flaticon.css
│   │   ├── owl.css
│   │   ├── animate.css
│   │   ├── color.css
│   │   ├── global.css
│   │   ├── elpath.css
│   │   └── jquery.fancybox.min.css
│   ├── js/                 ← All template JS files
│   │   ├── jquery.js
│   │   ├── bootstrap.min.js
│   │   ├── owl.js
│   │   ├── wow.js
│   │   ├── script.js
│   │   └── ... (all other JS files)
│   ├── images/             ← Template images + YOUR PHOTOS
│   │   ├── logo.png        ← Buchanan Offices logo (dark bg version)
│   │   ├── logo-2.png      ← Buchanan Offices logo (light bg version)
│   │   ├── favicon.ico     ← Buchanan Offices favicon
│   │   ├── og-image.jpg    ← Social sharing image (1200x630)
│   │   ├── banner/
│   │   │   ├── banner-1.jpg  ← Hero image: office/Glasgow exterior
│   │   │   ├── banner-2.jpg  ← Hero image: window-facing desks
│   │   │   └── banner-3.jpg  ← Hero image: Buchanan Street
│   │   ├── resource/
│   │   │   ├── about-1.jpg   ← About section: office interior
│   │   │   ├── about-2.jpg   ← About section: detail shot
│   │   │   └── contact-1.jpg ← Contact section image
│   │   ├── background/
│   │   │   └── skye-room-bg.jpg  ← Skye Room parallax bg
│   │   └── shape/           ← Keep all template shape/pattern files
│   └── fonts/               ← Template icon fonts
```

## Setup Steps

### 1. Prepare Assets
From your Komito Envato template download:
1. Copy the entire `assets/` folder into your repo
2. Replace the logo files with Buchanan Offices branded versions
3. Replace banner images with real office/Glasgow photos
4. Replace about/contact images with actual office photos
5. Add a `skye-room-bg.jpg` to `assets/images/background/`
6. Create an `og-image.jpg` (1200×630px) for social sharing

### 2. Images to Replace (Priority)

| File | What to Use |
|------|-------------|
| `banner-1.jpg` | Exterior of 166 Buchanan Street or the office building |
| `banner-2.jpg` | Interior shot showing window-facing desks and natural light |
| `banner-3.jpg` | Buchanan Street Glasgow streetscape |
| `about-1.jpg` | Office interior showing workspace quality |
| `about-2.jpg` | Close-up of desk/window/light detail |
| `contact-1.jpg` | Building entrance or reception area |
| `skye-room-bg.jpg` | Skye conference room or meeting space |
| `logo.png` | Logo for dark backgrounds (white/gold) |
| `logo-2.png` | Logo for light backgrounds (dark/gold) |

### 3. Deploy to GitHub Pages
1. Create a repository on GitHub
2. Upload `index.html`, `sitemap.xml`, `robots.txt`, `CNAME`, and the full `assets/` folder
3. Go to **Settings → Pages → Source: main branch, / (root)**
4. For custom domain, add DNS records:

| Type  | Name | Value                   |
|-------|------|-------------------------|
| A     | @    | 185.199.108.153         |
| A     | @    | 185.199.109.153         |
| A     | @    | 185.199.110.153         |
| A     | @    | 185.199.111.153         |
| CNAME | www  | your-username.github.io |

5. Enable **Enforce HTTPS** in GitHub Pages settings

### 4. Contact Form Setup
1. Sign up at [formspree.io](https://formspree.io)
2. Create a form, get your form endpoint
3. Replace `YOUR_FORM_ID` in the contact form's `action` attribute

### 5. SEO Checklist
- [x] Meta title, description, keywords
- [x] Open Graph & Twitter Card tags
- [x] LocalBusiness structured data (schema.org)
- [x] FAQPage structured data
- [x] Geo meta tags for local SEO
- [x] Canonical URL
- [x] robots.txt & sitemap.xml
- [ ] Submit sitemap to [Google Search Console](https://search.google.com/search-console)
- [ ] Create [Google Business Profile](https://business.google.com) with photos
- [ ] Register on Yelp, Yell.com, FreeIndex, Thomson Local
- [ ] Collect Google Reviews from tenants
- [ ] Add Google Analytics 4 tracking code

---

## Sections Mapped from Client Content

| Template Section | Buchanan Offices Content |
|-----------------|--------------------------|
| Banner carousel | 3 slides with key messaging |
| Services | 6 "Why Us" features |
| About | Company story & values |
| Category/Offices | 3 office cards (Bute, Islay, Tiree) |
| Trusted/Parallax | Skye Conference Room CTA |
| FAQ accordion | 6 FAQs with full answers |
| Testimonials | 2 tenant reviews |
| CTA section | "Ready to find your workspace?" |
| Contact | Form + info + Google Map |
| Footer | Links, address, email, hours |

## Removed from Template
- Team section (not applicable)
- News/blog section (can add later)
- Client logos carousel (no logos yet)
- Project gallery (can add office photos later)
- Social media links (add when profiles exist)

---

*Operated by Chalet Ventures Ltd t/a Buchanan Offices, Glasgow*
