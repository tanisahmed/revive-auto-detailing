# Revive Auto Detailing — Shopify OS 2.0 Theme

Premium Shopify Online Store 2.0 theme for Revive Auto Detailing, Karachi.

---

## 📁 File Structure

```
revive-auto-detailing/
├── layout/
│   └── theme.liquid              # Main layout (fonts, global CSS, WhatsApp button)
├── templates/
│   ├── index.json                # Homepage
│   ├── page.json                 # Generic pages
│   ├── page.paint-protection-film.json   # PPF page
│   ├── page.ppf-booking.json     # Booking page
│   └── 404.json                  # 404 error page
├── sections/
│   ├── header.liquid             # Sticky nav + mobile hamburger
│   ├── footer.liquid             # Footer with contact/hours/location
│   ├── hero.liquid               # Homepage hero
│   ├── services.liquid           # What We Offer (4 service cards)
│   ├── why-choose.liquid         # Benefits + special offer banner
│   ├── reviews.liquid            # Google reviews card
│   ├── process.liquid            # 4-step process
│   ├── lead-form.liquid          # Free estimate form
│   ├── main-page.liquid          # Generic page content
│   ├── 404.liquid                # 404 page
│   ├── ppf-hero.liquid           # PPF page hero
│   ├── ppf-benefits.liquid       # PPF benefits grid
│   ├── ppf-packages.liquid       # Vehicle selector + dynamic pricing
│   ├── ppf-gallery.liquid        # Work gallery (6 images)
│   ├── ppf-faq.liquid            # FAQ accordion
│   ├── ppf-cta.liquid            # PPF booking CTA
│   └── ppf-booking.liquid        # Multi-step booking form (4 steps)
├── config/
│   ├── settings_schema.json      # Theme editor settings
│   └── settings_data.json        # Default setting values
└── locales/
    └── en.default.json           # English translations
```

---

## 🚀 Installation on Shopify

### Method 1: Shopify CLI (Recommended)
```bash
# Install Shopify CLI
npm install -g @shopify/cli @shopify/theme

# Login
shopify auth login --store your-store.myshopify.com

# Push theme
shopify theme push --path ./revive-auto-detailing
```

### Method 2: Manual Upload via Admin
1. Go to **Shopify Admin → Online Store → Themes**
2. Click **"Add theme" → "Upload zip file"**
3. Zip this entire folder and upload

---

## ⚙️ After Installation

### Create Required Pages
In Shopify Admin → **Online Store → Pages**, create:

| Page Title | Handle (URL) | Template |
|---|---|---|
| Paint Protection Film | `paint-protection-film` | `page.paint-protection-film` |
| Book PPF Appointment | `ppf-booking` | `page.ppf-booking` |
| About Us | `about-us` | `page` (default) |
| Contact | `contact` | `page` (default) |
| FAQ | `faq` | `page` (default) |

### Customize via Theme Editor
Go to **Online Store → Customize** to edit:
- Logo text (default: "RAD")
- Phone number
- Email address
- Business address
- Hero headline & subheading
- PPF gallery images (upload before/after photos)

---

## 📱 Pages & Features

| Page | URL | Features |
|---|---|---|
| Homepage | `/` | Hero, Services, Benefits, Reviews, Process, Lead Form |
| PPF Page | `/pages/paint-protection-film` | Hero, Benefits, Dynamic Pricing, Gallery, FAQ, CTA |
| Booking | `/pages/ppf-booking` | 4-step form with validation & success screen |

### Key Features
- ✅ Fully responsive (mobile-first)
- ✅ Sticky header + mobile hamburger menu
- ✅ Dynamic PPF pricing by vehicle type (JS-powered)
- ✅ 4-step booking form with validation
- ✅ Package selection carries over from PPF page to booking
- ✅ Floating WhatsApp button on all pages
- ✅ FAQ accordion
- ✅ Google Fonts (Nunito Sans)
- ✅ No external dependencies / frameworks
- ✅ Shopify Theme Editor compatible (all sections have schema)

---

## 🎨 Brand Colors

| Variable | Color | Hex |
|---|---|---|
| Primary | Dark Blue | `#1e3a8a` |
| Secondary | Light Gray | `#f3f4f6` |
| Text | Dark Gray | `#1f2937` |
| Border | Gray | `#d1d5db` |
| Success/WhatsApp | Green | `#10b981` |
| Error | Red | `#ef4444` |

---

## 💰 PPF Pricing Table

| Vehicle | NAR Classic 8.0mil | NAR Premium 8.5mil | Duration |
|---|---|---|---|
| Hatchback | PKR 260,000 | PKR 290,000 | 8-10 hrs |
| Sedan | PKR 300,000 | PKR 330,000 | 8-10 hrs |
| SUV | PKR 330,000 | PKR 380,000 | 9-11 hrs |
| XL SUV | PKR 370,000 | PKR 420,000 | 10-12 hrs |

---

## 📞 Contact
- **Phone:** +92 303 7231111
- **Email:** info@reviveautodetailing.pk
- **Address:** A-65, Main Shahrah-e-Qaideen, Karachi 74800
- **Hours:** Mon–Sat 9AM–7PM | Sunday Closed
