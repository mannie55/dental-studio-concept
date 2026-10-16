# Website Editing & Outreach Guide

This project is now a **clean, single-page landing page** optimized for client outreach. 

All external pages have been removed from the navigation. When prospects click on any menu item or treatment card, the page smoothly scrolls to that exact section on the landing page (e.g., `#treatments`, `#team`, `#about`, `#book`).

---

## 1. Running the Site Locally

From this directory (`/home/chris/concept`):

```bash
# Option A: Using Python (Recommended - No installation required)
python3 -m http.server 8000

# Option B: Using Node
npm start
```

Then open in your browser:
👉 **http://localhost:8000/**

You can also open `index.html` directly in your browser without any server:
```bash
xdg-open index.html
```

---

## 2. Changing Images

All 32 website images are stored locally in the [`assets/images/`](./assets/images/) directory. 

### Quickest way to swap an image:
1. Find the image filename in the table below.
2. Prepare your new image.
3. Save it with the **exact same filename** in `assets/images/` (overwriting the old one).

| Image File | Description / Location on Page | Recommended Dimensions |
| :--- | :--- | :--- |
| **`YRTy2NxOkfcVHGa80qEHJySIPaY.svg`** | Header brand logo mark | SVG / Vector |
| **`3Bwz0KK0xvnEmhANGJvA6eXIjw.webp`** | Hero / Studio Interior Slide 1 | 2400 × 1600 |
| **`ZAe2RSeRRvptuPbcksJup5EdVE.webp`** | Hero / Studio Interior Slide 2 | 2400 × 1600 |
| **`hkCLvVNbVvxFIG5ODVbe6sk.webp`** | Hero / Studio Interior Slide 3 | 2400 × 1600 |
| **`LhRdrbEme10eLb0FCf78WEGE.webp`** | Dr. Elena Varga portrait | 1000 × 1250 |
| **`i9YV55qg35geFijtWVbcSvyZI.webp`** | Dr. Daniel Costa portrait | 1000 × 1250 |
| **`OOJeoY41AQsCWrnPdPjAJuQO6Mk.webp`** | Specialist Portrait 3 | 1200 × 1500 |
| **`FUIjYCaa9b230ws29Jtepsd3yMk.webp`** | Specialist Team Photo | 1200 × 960 |
| **`9pbqtpQPlfvmX47hTFP8i2jxK5M.webp`** | Treatment Card: Check-up & Cleaning | 900 × 1200 |
| **`F24CQJDmx2dXfi6nsJWkhOJgLo.webp`** | Treatment Card: Teeth Whitening | 900 × 1200 |
| **`HzF0BWtd5vrANLTjN7PI9791c.webp`** | Treatment Card: Clear Aligners | 900 × 1200 |
| **`KInTNOrEsO3cpEr4VIo3kSfbYWs.webp`** | Treatment Card: Dental Implants | 900 × 1200 |
| **`gvt4wbc9chkEeyu1yAJEiFw8jQ.webp`** | Treatment Card: Porcelain Veneers | 900 × 1200 |
| **`k0vQdGjfHh1G3fy5fGzadYBTUnk.webp`** | Treatment Card: Children's Dentistry | 900 × 1200 |
| **`vsnNT8nNNbeFURYRiTPRcScke0o.webp`** | Treatment Card: Digital Diagnostics | 900 × 1200 |
| **`WxgGl4JcZGmlTJB0GkvvuqPEKlo.webp`** | 3D Teeth Model graphic | 1000 × 920 |
| **`aOdEeCc1eweIfsImrWcAemKEe0.webp`** | Studio / Practice wide shot | 1800 × 1200 |
| **`xSAy4jQg8zfuzATCFVMYt7kNAk.webp`** | Journal Card 1 Photo (3D Intraoral scan) | 1000 × 750 |
| **`sYCE7dk1FoOdidhoG9cjd3Ltvk.webp`** | Journal Card 2 Photo (Whitening) | 1000 × 750 |
| **`WwgdtjUYix7TTGuFbAayqWBdqrI.webp`** | Journal Card 3 Photo (Hygiene visit) | 1000 × 750 |
| **`Jg9K07Uwxvbg6Orhxgpl9i41kI.webp`** | Review Avatar 1 | 240 × 240 |
| **`Pdg2FsX0s2JzZ9jgiBwVofeYY.webp`** | Review Avatar 2 | 240 × 240 |
| **`VkaMPve6r9ATzF5pXHDFQ8R76hY.webp`** | Review Avatar 3 | 240 × 240 |
| **`XwgfN9owSCdUUZcCxVrwg5aEc.webp`** | Review Avatar 4 | 240 × 240 |
| **`favicon.png`** | Browser Tab Favicon | 256 × 256 |

---

## 3. Editing Text & Content

Open [`index.html`](./index.html) in your editor and use `Ctrl+F` (or `Cmd+F`) to find and replace:


### Hero Headline, Description & Credentials Mockup
- **Headline**: Search for `Advanced Dental Care` and `& Aesthetic Excellence.`
- **Description**: Search for `Comprehensive cosmetic, restorative, and preventive dentistry`
- **Clinical Credentials Badges**: Search for `vanguard-credentials-mockup` in `index.html` to customize the 4 accreditation pills:
  - `Board-Certified Specialists`
  - `ADA & AACD Member`
  - `Invisalign® Diamond Provider`
  - `3D Intraoral Diagnostics`

### Clinic Branding & Contact Info
- **Clinic Name**: Search for `Vanguard Dental Group` or `Vanguard`
- **Phone Number**: Search for `(718) 555-0142` and `tel:+17185550142`
- **Email**: Search for `info@vanguarddental.com`
- **Address**: Search for `218 Linden Avenue, Brooklyn, NY 11215`

### Doctor & Team Details
- **Doctor Names**:
  - `Dr. Elena Varga` (Cosmetic dentistry)
  - `Dr. Daniel Costa` (Orthodontics)
  - `Dr. Sofia Reyes` (Children's dentistry)
  - `Dr. Ryan Okafor` (Implants & surgery)

### Treatment Names & Pricing
- Search for:
  - `Check-up & cleaning` / `from $85`
  - `Teeth whitening` / `from $290`
  - `Clear aligners` / `from $2,900`
  - `Dental implants` / `from $1,850`
  - `Porcelain veneers` / `from $650 per tooth`

---

## 4. Single-Page Navigation Structure

All navigation and buttons scroll smoothly to sections on the page:

| Link / Button | Target Anchor ID | Description |
| :--- | :--- | :--- |
| **Treatments** | `#treatments` | Scrolls to the treatments showcase grid |
| **Specialists** | `#team` | Scrolls to doctor profiles and clinical credentials |
| **Reviews** | `#reviews` | Scrolls to 5-star patient testimonials & ratings |
| **Insurance & FAQ** | `#faq` | Scrolls to insurance coverage, payment plans & FAQ |
| **Contact** | `#book` | Scrolls to hours, phone, email & location |
| **Book a visit** | `#book` | Primary contrasting booking CTA button |

---

## 5. Directory Layout

```
concept/
├── index.html                 # The only landing page shown to prospects
├── EDITING_GUIDE.md           # This guide
├── package.json               # Local development scripts (npm start)
├── assets/
│   ├── images/                # All 32 local website images + favicon
│   └── js/
│       └── lenis.min.js       # Smooth scroll engine
└── _backup_multi_page_site/   # Backup of the original multi-page site
```
