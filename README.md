# Email Portfolio

## Overview
This project is a collection of responsive HTML and MJML email templates for various marketing campaigns and newsletters. All templates are built using best practices to ensure maximum compatibility across major email clients including Gmail, Apple Mail, and Outlook.

## Email Templates

### Newsletter Templates
- **monthly-newsletter.html** - Professional monthly newsletter template with content sections
- **salad-newsletter.mjml** & **salad-newsletter.html** - Salad-themed newsletter with promotional content

### Promotional Templates
- **boody-promo.mjml** & **boody-promo.html** - Boody brand promotional email
- **welcome-promo.html** - Welcome/onboarding promotional email

### Base Templates
- **email.html** & **email.mjml** - Root-level template files
- **template/email.html** & **template/email.mjml** - Base template files in template folder

## Project Structure

```
email-portfolio/
├── html/                      # Compiled HTML email templates
│   ├── boody-promo.html
│   ├── monthly-newsletter.html
│   ├── salad-newsletter.html
│   └── welcome-promo.html
├── mjml/                      # MJML source templates
│   ├── boody-promo.mjml
│   └── salad-newsletter.mjml
├── template/                  # Base template files
│   ├── email.html
│   └── email.mjml
├── assets/                    # Email assets organized by campaign
│   ├── boody/                 # Boody campaign assets
│   ├── newsletter/            # Newsletter campaign assets
│   ├── promotional/           # Promotional campaign assets
│   └── salad/                 # Salad campaign assets
├── screenshots/               # Email template screenshots
```

## Tech Stack
- **HTML** - Table-based layout for maximum email client compatibility
- **MJML** - Markup language for building responsive email templates
- **Inline & Embedded CSS** - Inline styles for critical elements
- **Google Fonts** with system font fallbacks

## Key Development Practices

### Layout & Structure
- Table-based layouts for consistent rendering across email clients
- Fixed-width containers (512px / 600px) for optimal display
- Padding applied to `<td>` elements to avoid Outlook issues
- No layout `<div>` elements used

### Responsiveness
- Desktop-optimized fixed-width containers
- Mobile media queries for responsive scaling
- Images include width attributes and responsive CSS (max-width: 100%)

### Cross-Client Compatibility
Tested and optimized for:
- Outlook (Windows & Mobile)
- Gmail (Web & Mobile)
- Apple Mail

Techniques:
- Table-based layout structure
- Inline styles for critical styling
- Pixel-based line-height for headings
- MSO-specific resets for Outlook spacing

### Typography & Images
- Google Fonts for supported clients with system font fallbacks
- All images include width attributes and alt text
- Decorative images use empty alt attributes
- Asset organization by campaign for easy management

## Assets by Campaign

### Boody Assets
- Logo and branding elements
- Multiple image variations (img01-img08)
- Icon sets (ico01-ico04)
- Color palette assets (black, olive, sand, bg01)

### Newsletter Assets
- Banner images (banner, banner02)
- Social media icons (Facebook, Instagram, Twitter, YouTube)
- Content images (img01-img02)
- Explore action graphics
- Logo

### Promotional Assets
- Campaign banners
- Social media icons
- Profile pictures
- Logo

### Salad Assets
- Campaign banner
- Product/content images (img01-img02)

## Testing & Validation
Templates are tested across major email clients for:
- Layout consistency and spacing
- Image rendering and responsiveness
- Typography and font rendering
- Cross-client compatibility

## Notes
This portfolio demonstrates email development expertise using both native HTML and MJML approaches, following production-standard best practices for email marketing campaigns.