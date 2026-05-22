# Zae's Creative Vault ✦

A personal portfolio website — cinematic, minimal, and visually curated.  
Built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no build tools, no dependencies.

**Live site:** [zaes-creative-vault.vercel.app](https://zaes-creative-vault.vercel.app) *(update this once deployed)*

---

## Folder Structure

```
zaes-creative-vault/
│
├── index.html                  ← The entire website (edit this)
│
├── images/
│   ├── profile/
│   │   └── profile.jpg         ← Your profile photo (recommend: square, min 400×400px)
│   │
│   ├── photography/
│   │   ├── golden-hour.jpg
│   │   ├── portraits-in-still.jpg
│   │   ├── urban-textures.jpg
│   │   ├── chasing-dusk.jpg
│   │   └── soft-light.jpg
│   │
│   ├── fashion/
│   │   ├── velvet-season.jpg
│   │   ├── baroque-reverie.jpg
│   │   └── bloom-and-contrast.jpg
│   │
│   └── research/
│       ├── project-1.jpg
│       ├── project-2.jpg
│       └── project-3.jpg
│
└── README.md                   ← This file
```

---

## How to Customize

### 1. Profile section (Hero)
Open `index.html` and find the profile image placeholder. Replace it:

```html
<!-- BEFORE (placeholder) -->
<div class="profile-img-placeholder">
  ...
</div>

<!-- AFTER (your real photo) -->
<img src="/images/profile/profile.jpg" alt="Zae" style="width:100%;height:100%;object-fit:cover;border-radius:50%;" />
```

Update your name and bio by finding these lines and editing them:
```html
<p class="hero-name">[ Your Full Name Here ]</p>
<p class="hero-bio">A multi-disciplinary creative ...</p>
```

### 2. Photography images
Find each `.photo-img` div and replace the inner placeholder:

```html
<!-- BEFORE -->
<div class="photo-img">
  <div class="photo-img-inner"> ... </div>
</div>

<!-- AFTER -->
<div class="photo-img">
  <img src="/images/photography/golden-hour.jpg" alt="Golden Hour Series"
       style="width:100%;height:100%;object-fit:cover;" />
</div>
```

### 3. Fashion images
Same pattern — find `.fashion-img` divs:

```html
<!-- AFTER -->
<div class="fashion-img">
  <img src="/images/fashion/velvet-season.jpg" alt="Velvet Season"
       style="width:100%;height:100%;object-fit:cover;" />
</div>
```

### 4. Research images
Find `.research-img` divs and replace:

```html
<!-- AFTER -->
<div class="research-img">
  <img src="/images/research/project-1.jpg" alt="Project Title"
       style="width:100%;height:100%;object-fit:cover;border-radius:4px;" />
</div>
```

### 5. Social media links
Search for `href="#"` in the contact and footer sections and replace with your real URLs:

```html
<!-- Instagram -->
<a href="https://instagram.com/YOUR_HANDLE" class="social-btn">

<!-- TikTok -->
<a href="https://tiktok.com/@YOUR_HANDLE" class="social-btn">

<!-- LinkedIn -->
<a href="https://linkedin.com/in/YOUR_PROFILE" class="linkedin-cta">
```

### 6. Email address
Find this line near the bottom of the contact section:
```html
<p class="contact-email reveal">or reach me at · yourname@email.com</p>
```

### 7. Footer copyright
```html
<p class="footer-copy">© 2025 Zae's Creative Vault · All Rights Reserved</p>
```

---

## Image Tips

| Section | Recommended ratio | Min size |
|---|---|---|
| Profile photo | 1:1 (square) | 400 × 400px |
| Photography — wide cards | 16:7 | 1200 × 525px |
| Photography — regular cards | 4:3 | 800 × 600px |
| Fashion cards | 3:4 (portrait) | 600 × 800px |
| Research thumbnails | 4:3 | 600 × 450px |

Keep file sizes under **500KB** per image for fast loading. Use [Squoosh](https://squoosh.app) (free, browser-based) to compress before uploading.

---

## Deploying Updates

Every time you push to `main`, Vercel automatically redeploys.

```bash
# after editing index.html or adding images
git add .
git commit -m "update portfolio content"
git push
```

That's it — your live site updates in ~30 seconds.

---

*Curated with creativity and vision. ✦*
