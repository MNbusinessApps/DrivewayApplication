# Driveway App

**Where every car decision starts and ends right.**

Driveway is a founder-driven automotive marketplace advisory service designed to guide buyers and sellers through the automotive marketplace with clarity, confidence, and precision.

## 🌟 About Driveway

The automotive market can be overwhelming, with confusing listings and costly mistakes waiting to happen. Driveway fills this gap by acting as your professional advisory service. We don't own, deliver, or sell cars—instead, we provide curated guidance, expert evaluation, and tailored results to help you make informed decisions.

### Mission

To bridge the gap between car confusion and informed decision-making. Every client should be able to navigate buying or selling a car with confidence and precision.

### Vision

Driveway is the route every buyer and seller should take, ensuring decisions are accurate, professional, and stress-free.

---

## 🎨 Branding

### Logo

The Driveway logo features the word "DRIVEWAY" with a distinctive design element: the "Y" transforms into a winding road sign with an arrow, symbolizing the path to smart car decisions.

### Colors

| Color | Hex Code | Usage |
|-------|----------|-------|
| Teal | `#008080` | Primary brand color, buttons, headers, highlights |
| Grey | `#808080` | Secondary backgrounds, borders, accents |
| Dark Grey | `#333333` | Primary text color |
| Light Grey | `#F9F9F9` | Page backgrounds |
| Darker Teal | `#006666` | Button hover states |

### Typography

- **Font Family:** Inter, system-ui, sans-serif
- **Headings:** Bold, modern sans-serif
- **Body Text:** Clean, readable sans-serif
- **Style:** Minimalist and professional

### Slogan

> "Driveway → Where every car decision starts and ends right."

---

## 📁 Project Structure

```
driveway-app/
├── index.html      # Main landing page with all sections
├── styles.css      # Complete styling with CSS variables
├── script.js       # Interactive functionality
├── README.md       # Project documentation
└── assets/         # Images and other assets (if any)
```

---

## 🚀 Features

### Home Page
- **Hero Section:** Welcoming header with tagline and CTA buttons
- **About Driveway:** Company overview and value proposition
- **Service Tiers:** Pricing preview with Basic and Premium options
- **Buy/Sell Forms:** Embedded Google Forms for easy submissions

### Navigation
- Fixed header with smooth scrolling
- Mobile-responsive hamburger menu
- Active section highlighting
- Quick access to all sections

### Interactive Elements
- Smooth scroll navigation
- Button hover effects with animations
- Fade-in animations on scroll
- Mobile-friendly responsive design

---

## 📝 Forms

### Buy a Car Form
**URL:** [Driveway Buy Form](https://docs.google.com/forms/d/e/1FAIpQLSe8SYFanYB8ofWCgRMwMO8wG9awQ2GXJYEPIEhbnwmj4KSJGg/viewform)

**Captures:**
- Name, Email, Phone
- Vehicle preferences: Make, Model, Year, Mileage, Type
- Budget and Location
- Additional notes

**Confirmation:** "Thank you! Your criteria has been submitted. Driveway → will curate a list of cars tailored to your needs and send it within 24–48 hours."

### Sell a Car Form
**URL:** [Driveway Sell Form](https://docs.google.com/forms/d/e/1FAIpQLSffj3xLRj5qmYE2cRH_b7zitRNM1egzd62u5JHeAUZ9JWh28w/viewform)

**Captures:**
- Name, Email, Phone
- Vehicle details: Make, Model, Year, Mileage, Condition
- Asking Price, VIN (optional)
- Photos and Notes (optional)

**Confirmation:** "Thank you! Your car details have been submitted. Driveway → will evaluate and provide guidance within 24–48 hours."

---

## 💰 Pricing Tiers

### Basic Search - $100
- Curated car list delivered within 24-48 hours
- Multiple options matching your criteria
- Standard turnaround time

### Premium Search - $250
- Everything in Basic, plus:
- CARFAX/AutoCheck reports included
- Priority turnaround
- Direct consultation
- Ongoing support throughout your search

**Note:** Full details and payment collection occur after submission during personal follow-up.

---

## 🔄 Workflow After Submission

1. **Form Submission:** Client submits criteria via embedded Google Form
2. **Data Collection:** Responses automatically feed into the Driveway Hub (private Google Sheet)
3. **Internal Review:** Founder reviews submissions, curates results, runs vehicle history reports
4. **Client Follow-up:** Personal call to discuss options, confirm service tier, and collect payment
5. **Delivery:** Professional PDF or email delivery of curated results with expert guidance

---

## 🛠️ Setup Instructions

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/driveway-app.git
   cd driveway-app
   ```

2. **Open in browser:**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server: `npx serve` or `python -m http.server`

3. **Make changes:**
   - Edit `index.html` for content changes
   - Edit `styles.css` for styling adjustments
   - Edit `script.js` for functionality updates

### Deployment to GitHub Pages

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial commit: Driveway App"
   git remote add origin https://github.com/your-username/driveway-app.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to Repository Settings → Pages
   - Select main branch as source
   - Save and wait for deployment

3. **Your site will be live at:**
   `https://your-username.github.io/driveway-app/`

### Custom Domain (Optional)

1. Add CNAME file with your domain
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings

---

## 🎯 Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📱 Responsive Breakpoints

| Viewport | Width | Layout |
|----------|-------|--------|
| Mobile | < 768px | Hamburger menu, stacked columns |
| Tablet | 768px - 1024px | Fluid padding, 2-column grids |
| Desktop | > 1024px | Fixed max-width, horizontal nav |

---

## 🔧 Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --color-teal: #008080;      /* Change to your brand color */
    --color-grey: #808080;      /* Change to your secondary color */
    /* ... other variables */
}
```

### Adding New Sections

1. Add HTML section in `index.html`:
   ```html
   <section class="new-section" id="new-section">
       <div class="container">
           <!-- Your content here -->
       </div>
   </section>
   ```

2. Add navigation link in header

3. Add styles in `styles.css` if needed

### Modifying Forms

To change the embedded Google Forms:

1. Update the `src` attribute in the iframe elements:
   ```html
   <iframe src="YOUR_NEW_FORM_URL" ...></iframe>
   ```

---

## 📊 Technical Details

### Performance Optimizations

- CSS variables for efficient theming
- Smooth animations with hardware acceleration
- Mobile-first responsive design
- System font stack for fast loading
- No external JavaScript dependencies

### Accessibility Features

- Semantic HTML structure
- Proper heading hierarchy
- Keyboard navigation support
- Focus indicators on interactive elements
- Sufficient color contrast
- ARIA labels where needed

### SEO Considerations

- Meta description for search engines
- Semantic heading structure
- Proper title tag
- Alt text ready for images

---

## 🔐 Privacy & Legal

- All form data is stored in a private Google Sheet
- Client information is never shared with third parties
- Terms & Conditions and Privacy Notice links in footer
- Compliant with standard privacy regulations

---

## 📞 Contact

**Driveway →**  
Your trusted route to smarter car decisions.

- **Email:** info@ driveway.app
- **Website:** [Your Domain]

---

## 🙏 Acknowledgments

- Google Forms for form handling
- Google Fonts (Inter) for typography
- SVG icons for visual elements

---

## 📄 License

This project is proprietary software. All rights reserved.

---

**Built with care by MiniMax Agent**

*Driveway → Where every car decision starts and ends right.*