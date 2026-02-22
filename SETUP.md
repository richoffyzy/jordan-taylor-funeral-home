# Jordan & Taylor Funeral and Cremation Website

A professional, dignified website for Jordan & Taylor Funeral and Cremation, serving families in Waco, Texas and surrounding communities.

## About

Jordan & Taylor Funeral and Cremation is a family-owned and operated funeral home with over 40 years of experience providing compassionate care and dignified services to families during their most difficult times.

**Contact Information:**
- **Address:** 1235 Chestnut Street, Waco, TX 76704
- **Phone:** (254) 429-3210 / (254) 429-5350
- **Email:** taylorjordanassociate@gmail.com
- **Availability:** 24 Hours a Day, 7 Days a Week

## Features

### Website (index.html)
- **Responsive Design:** Mobile-friendly layout that works on all devices
- **Hero Section:** Elegant introduction with contact information
- **About Section:** Information about the funeral home and services
- **Services Section:** Detailed information about funeral, cremation, pre-need planning, and veteran services
- **Obituaries Section:** 
  - Picture frame display with 6 recent obituaries
  - Search functionality to find obituaries by name or date
  - View All feature to browse additional obituaries
- **Veterans Benefits:** Comprehensive information about military honors and VA benefits
- **Payment Options:** Clear information about accepted payment methods

### Mobile Version (mobile.html)
- Optimized for mobile devices
- Compact hero section with expandable contact information
- Touch-friendly navigation
- Streamlined content presentation

## Technology Stack

- **HTML5:** Semantic markup
- **CSS3:** Modern styling with custom properties
- **JavaScript:** Interactive features (search, navigation, modals)
- **Google Fonts:** Cormorant Garamond & Lato typefaces

## Design Elements

### Color Palette
- **Primary Navy:** #2c4a5c
- **Accent Gold:** #c9b896
- **Cream Background:** #f5f2ed
- **Text Dark:** #000000

### Typography
- **Headings:** Cormorant Garamond (Serif)
- **Body Text:** Lato (Sans-serif)

## File Structure

```
jordan-taylor-funeral-home/
├── index.html          # Main website
├── mobile.html         # Mobile-optimized version
└── README.md          # Project documentation
```

## Features Breakdown

### Obituaries System
The obituaries section includes:
- **Picture Frame Display:** Professional bordered section containing 6 obituaries
- **Real-time Search:** Filter obituaries by name or date as you type
- **Pagination:** View additional obituaries 6 at a time
- **Consistent Layout:** All cards maintain uniform height and alignment
- **Sample Data:** 8 pre-loaded obituaries for demonstration

### Navigation
- Sticky header with smooth scrolling
- Quick links in footer
- Service detail pages with back navigation
- Mobile-responsive menu

### Interactive Elements
- Hover effects on cards and buttons
- Expandable contact information in hero section
- Service detail modals
- Smooth scroll animations

## Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select main branch as source
5. Your site will be live at: `https://[username].github.io/[repository-name]`

### Custom Domain
To use a custom domain:
1. Add a CNAME file with your domain name
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Adding Obituaries
Edit the obituaries section in `index.html`:
```html
<div class="obituary-card" data-name="Name Here" data-date="Date Here">
    <div class="obituary-photo">
        <img src="image-url-here" alt="Photo">
    </div>
    <div class="obituary-info">
        <h3>Name Here</h3>
        <p class="obituary-date">Date Here</p>
    </div>
</div>
```

### Updating Contact Information
Update contact details in:
- Top bar section
- Hero section contact info
- Footer section

### Modifying Services
Edit the services section to add/remove/modify service offerings and descriptions.

## Professional Affiliations

- National Funeral Directors Association (NFDA) Member
- Texas Funeral Directors Association Member

## License

© 2026 Jordan & Taylor Funeral and Cremation. All rights reserved.

## Support

For technical support or questions about the website, please contact the development team or refer to the GitHub repository issues section.

---

**Built with care and respect for families during their time of need.**
