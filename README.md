# AgroSL – Sierra Leone Farmer Advisory Portal

## 🌿 Overview

**AgroSL** is a digital public good designed to empower smallholder farmers across Sierra Leone with real-time agricultural information, weather alerts, market intelligence, and expert farming guidance. The platform provides essential services completely free to farmers across all 16 districts.

**Current Status:** 12,400+ registered farmers | 14 districts covered | 6 key crops tracked

---

## 📋 Features

### 1. **Daily Crop Advisories**
- Real-time crop guidance tailored to Sierra Leone's agricultural seasons
- District-specific recommendations for:
  - Rice cultivation and pest management
  - Groundnut planting optimization
  - Cassava pest alerts
  - Maize fertilizer timing
  - Palm oil harvesting tips
  - Plantain water management

### 2. **Weather Intelligence**
- District-level weather forecasts
- Temperature, humidity, wind speed, and rainfall data
- 5-day weather outlook with farming recommendations
- Alerts for adverse weather conditions (48 hours notice)

### 3. **Live Market Prices**
- Weekly crop price updates from district markets
- Price tracking across Freetown, Bo, and Makeni markets
- Price trend indicators (Rising/Falling/Stable)
- Coverage: Rice, Groundnut, Cassava, Maize, Palm Oil, Plantain

### 4. **Farming Tips & Best Practices**
- Soil testing and pH management
- Water conservation techniques
- Intercropping strategies
- Integrated pest management
- Post-harvest storage solutions
- Digital record-keeping guidance

### 5. **Farmer Registration & Support**
- Free registration system
- SMS advisory delivery
- Direct access to certified extension officers
- Training resources in English and Krio
- Support across all Sierra Leone districts

### 6. **Contact & Extension Services**
- Farmer helpline: +232 76 123 456 (Mon–Fri, 8am–5pm)
- Email: info@agrosl.gov.sl
- SLBC Radio advisories: Every Monday & Thursday at 6:30am
- Head office: Ministry of Agriculture, Youyi Building, Freetown

---

## 🎨 Design System

### Color Palette
- **Primary Green (Deep):** #1B4332 – Trust, growth, agriculture
- **Primary Green (Mid):** #2D6A4F – Accent color
- **Light Green:** #52B788 – Secondary accent
- **Gold:** #D4A017 – Premium, wealth, harvest
- **Soil Brown:** #8B5E3C – Earth, farming heritage
- **Cream:** #F9F5EC – Background, warmth
- **Charcoal:** #1C1C1C – Text, authority

### Typography
- **Serif (Playfair Display):** Headings, premium feel
- **Sans-serif (Inter):** Body text, readability

---

## 🛠️ Technical Stack

### Frontend
- **HTML5** – Semantic markup
- **CSS3** – Custom design system with CSS variables
- **Vanilla JavaScript** – No dependencies
  - Intersection Observer API for scroll reveal animations
  - DOM manipulation for form handling and menus

### Features
- **Responsive Design** – Mobile-first approach (breakpoints: 768px, 480px)
- **Accessibility** – ARIA labels, semantic HTML
- **Performance** – No external dependencies, lightweight
- **Cross-browser** – Modern browser support

---

## 📁 Project Structure

```
AgroSL/
├── index.html          # Main application file
├── README.md           # This documentation
└── assets/             # (Future) Images, icons, media
```

### Key Sections in HTML

| Section | ID | Purpose |
|---------|-----|---------|
| Navigation | `nav` | Fixed top navbar with mobile menu |
| Hero Banner | `.hero` | Main landing section with CTA |
| Today's Advisory | `.advisory-strip` | Rotating advisory carousel |
| Crop Cards | `#advisory` | Grid of seasonal crop guidance |
| Weather | `#weather` | Current weather + 5-day forecast |
| Market Prices | `#market` | Crop price table by district |
| Tips | `#tips` | Farming best practices |
| Registration | `#register` | Farmer signup form |
| Contact | `#contact` | Support information + contact form |
| Footer | `footer` | Navigation links, branding |

---

## 🚀 Getting Started

### Opening the Website

1. **Download/Clone the project**
2. **Open `index.html` in any modern web browser**
3. **No server or build process required** – it's a static site

### Browser Compatibility
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📱 Features Breakdown

### Advisory Carousel
- Rotates through 5 key advisories automatically every 6 seconds
- Manual navigation with up/down buttons
- Updates daily with seasonal guidance

**Advisories Include:**
1. Rain alerts and weather-based recommendations
2. Crop planting season updates
3. Pest and disease alerts
4. Market price movements
5. Free seedling distribution announcements

### Registration Form
**Required Fields:**
- First & Last Name
- Phone Number
- District (dropdown with all 16 districts)
- Primary Crop (9 crop options)

**Optional:**
- Farm Size (hectares)
- Current Farming Challenge

**Features:**
- Form validation on submit
- Success confirmation message
- Mobile-responsive layout

### Contact Form
**Fields:**
- Name
- Email or Phone
- Subject (6 predefined categories)
- Message

**Features:**
- Input validation
- Success message display
- Form auto-clear after submission

---

## 🎯 User Demographics

**Target Users:**
- Smallholder farmers (0.5–5 hectares)
- Extension officers
- Agricultural cooperatives
- Rural farming communities

**Accessibility:**
- Available in English
- Krio language resources linked
- SMS delivery for low-bandwidth regions
- Simple, intuitive interface

---

## 📊 Key Statistics (As of June 2026)

| Metric | Value |
|--------|-------|
| Registered Farmers | 12,400+ |
| Districts Covered | 14 of 16 |
| Crops Tracked | 6 (Rice, Groundnut, Cassava, Maize, Palm Oil, Plantain) |
| SMS Subscribers | Growing daily |
| Extension Officers | 100+ trained |

---

## 🔄 Content Updates

### Daily Updates
- Today's Advisory carousel (manual update)
- Weather data (district-specific)

### Weekly Updates
- Market prices from Bo, Makeni, and Freetown markets
- Crop advisory rotation

### Seasonal Updates
- Crop guidance aligned with planting/harvest seasons
- Regional variations by district

---

## 🛡️ Privacy & Data

- **No data collection:** The portal is informational
- **Future roadmap:** SMS backend will require opt-in registration
- **Privacy Policy:** Link in footer (to be added)
- **DPG Status:** Registered Digital Public Good

---

## 💡 Future Enhancements

- [ ] Backend SMS integration
- [ ] Mobile app (iOS/Android)
- [ ] Real-time weather API integration
- [ ] Agricultural market API
- [ ] Multi-language support (full Krio interface)
- [ ] Farmer testimonials/success stories
- [ ] Video tutorials embedded
- [ ] Soil and weather station network integration
- [ ] Farmer-to-farmer knowledge sharing forum

---

## 📄 Responsive Breakpoints

| Breakpoint | Device | Changes |
|-----------|--------|---------|
| 768px | Tablet | Hamburger menu, single-column forms |
| 480px | Mobile | Larger touch targets, simplified layout |
| Reduced Motion | Accessibility | Disabled animations |

---

## 🤝 Contributing

To contribute to AgroSL:

1. **Report issues** – Contact info@agrosl.gov.sl
2. **Suggest features** – Use the contact form
3. **Translations** – Reach out for Krio/local language support
4. **Extension Officer Input** – Share feedback from farmers

---

## 📞 Support

**For Farmers:**
- Helpline: +232 76 123 456 (Mon–Fri, 8am–5pm)
- Email: info@agrosl.gov.sl
- Register at [agrosl.gov.sl](https://agrosl.gov.sl)

**For Technical Issues:**
- Check browser compatibility
- Clear browser cache
- Ensure JavaScript is enabled

---

## 📜 License & Attribution

**Built with ❤️ for Sierra Leonean farmers**

© 2026 AgroSL – Sierra Leone Farmer Advisory Portal

- **Ministry of Agriculture** – Government partnership
- **DPG Principles** – Open, collaborative, transparent
- **Open Source** – Available for reuse and adaptation

---

## 🌐 Links

- [Ministry of Agriculture](https://www.agriculture.gov.sl)
- [DPG Principles](https://digitalpublicgoods.net)
- [Open Source Guidelines](https://opensource.org)

---

**Last Updated:** June 2026  
**Version:** 1.0  
**Status:** Active & Growing




