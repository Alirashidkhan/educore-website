# EduCore - Institution ERP Marketing Website

A modern, responsive marketing website for EduCore, a comprehensive school and institution management ERP software.

## Features

- **Responsive Design**: Mobile-first CSS Grid layout that works on all devices
- **Premium Branding**: Dark navy (#0d1b5e) and gold (#C9A227) color scheme
- **Interactive Components**:
  - ROI Calculator with dynamic pricing
  - Enquiry popup form
  - Pricing toggle (Starter/Professional)
  - Video modals
  - WhatsApp float integration
  - Cookie consent banner
  - Announcement bar
- **Compliance Messaging**: NAAC, ISO, and data security certifications
- **Mobile App Section**: Dual-phone mockup showcase
- **Security Focus**: Trust badges, uptime SLA, data ownership messaging
- **12 Integrated Modules**: Student management, accounts, attendance, and more
- **Lead Generation**: Built-in enquiry form with popup trigger

## File Structure

```
educore-website/
├── index.html          # Main website (all-in-one HTML with inline CSS & JS)
├── logo.svg            # Light version logo
├── logo-white.svg      # Dark background version logo
├── README.md           # This file
└── .gitignore          # Git ignore rules
```

## Pricing Strategy

- **Starter Plan**: ₹249/student/year (up to 400 students)
- **Professional Plan**: ₹349/student/year (up to 2000 students)
- All 12 modules included (no à la carte add-ons like competitors)

## Deployment Options

### Option 1: GitHub Pages (Free, Static)
```bash
git push origin main
# Enable GitHub Pages in repository settings
```

### Option 2: Render.com (Recommended, with Backend Support)
1. Deploy static website to Render Web Service
2. Set up Node.js backend for form handling
3. Connect PostgreSQL database via Neon

## Getting Started

1. Create a repository on GitHub: `educore-website`
2. Clone locally or use git in this folder
3. Push to GitHub with:
   ```bash
   git remote add origin https://github.com/Alirashidkhan/educore-website.git
   git branch -M main
   git push -u origin main
   ```

## Development

The entire website is contained in a single `index.html` file with:
- **CSS**: All styling (1000+ lines)
- **JavaScript**: Interactive features and animations
- **HTML**: Semantic markup with accessibility

No build tools or external frameworks required. Simply open `index.html` in a browser to develop locally.

## Future Enhancements

- [ ] Backend API for form submissions
- [ ] Database integration (PostgreSQL)
- [ ] Newsletter subscription
- [ ] Analytics integration
- [ ] Admin dashboard for enquiries
- [ ] Blog/Resources section
- [ ] Blog section

## Support

For questions or issues, contact: alirashid2503@gmail.com

---
**EduCore** - Your Complete Institution ERP Solution
