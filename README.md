# PureBlendEmailSignatures

HTML email signature template for PureBlend Ingredients. Two-column table layout with company logo, contact details, and social media icons — designed to render consistently across major email clients.

---

## Layout

```
┌─────────────────┬──────────────────────────────────┐
│                 │  Dr. Michael Roberts              │
│  [PureBlend     │  Chief Scientific Officer         │
│   Logo]         │  ─────────────────────────────    │
│                 │  📧 email   📞 phone   🌐 site     │
│                 │  Natural Solutions • Pure Innovation│
│                 │  [LinkedIn] [X] [Instagram] [FB]  │
└─────────────────┴──────────────────────────────────┘
  [confidentiality notice]
```

Table-based HTML — no CSS classes, no external stylesheets. Uses inline styles throughout for maximum compatibility with email clients that strip `<style>` tags.

---

## Usage

1. Open `signature.html` in a browser
2. Select all (Ctrl+A / Cmd+A) and copy
3. Paste into your email client's HTML signature editor

Tested with Gmail and Outlook web.

---

## Customization

Edit `signature.html` directly:

| What to change | Where |
|---|---|
| Name and title | `<strong>` tags in the right column |
| Email / phone / website | `<a href>` and text nodes in the contact row |
| Social links | `href` attributes on social icon `<a>` tags |
| Brand color | `#7BAA4E` (used for name color and left border accent) |
| Logo | Replace `assets/PureBlend2.png` |

Social icons are 25×25 px PNGs in `assets/`. Keep the `assets/` folder alongside `signature.html` — paths are relative.

---

## Files

```
signature.html        — the signature template
assets/
  PureBlend2.png      — company logo
  email-icon.png      — email icon
  phone-icon.png      — phone icon
  website-icon.png    — website icon
  icons8-linkedin-48.png
  icons8-x-50.png
  icons8-instagram-48.png
  icons8-facebook-logo-48.png
```
