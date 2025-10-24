# Gates Foundation Data Initiative Website

A static website for the Gates Foundation Supported Datasets for AI Model Training program, using the exact styling from the Development Data Partnership (datapartnership.org).

## Features

- **Authentic Design**: Uses actual datapartnership.org CSS, fonts (Roboto & Asap Condensed), and color palette
- **Bootstrap 4.5**: Responsive grid system and components
- **Exact Color Scheme**: 
  - Primary Navy: #001E60
  - Orange Accent: #F7951D / #DF6B00
  - Teal: #56C3C4 / #3DA3A8
  - Purple: #310459 / #2e2d70
- **7 Dataset Cards**: Bootstrap card components with proper spacing and hover effects
- **Gradient Hero Banner**: Matches datapartnership.org's bg-primary-gradient style
- **Application Section**: Call-to-action with Microsoft Form link
- **Authentic Footer**: Multi-column footer with exact structure from datapartnership.org

## Files Included

- `index.html` - Main webpage with Bootstrap structure
- `css/main.css` - Exact CSS from datapartnership.org
- `README.md` - This file

## File Structure

```
your-repository/
├── index.html          # Main webpage
├── css/
│   └── main.css       # datapartnership.org stylesheet
└── README.md          # Documentation
```

## Deploying to GitHub Pages

### Option 1: New Repository

1. Create a new repository on GitHub (e.g., `gates-foundation-datasets`)
2. Upload `index.html` and the `css` folder (containing `main.css`) to the repository
3. Go to repository Settings > Pages
4. Under "Source", select "Deploy from a branch"
5. Choose `main` branch and `/ (root)` folder
6. Click Save
7. Your site will be available at: `https://[username].github.io/[repository-name]/`

### Option 2: Existing Repository

1. Add `index.html` and the `css` folder to your existing repository
2. Follow steps 3-7 from Option 1

### Option 3: User/Organization Site

1. Create a repository named `[username].github.io`
2. Upload the files maintaining the folder structure
3. The site will automatically deploy to `https://[username].github.io/`

## Customization Needed

Before deployment, you should:

1. **Replace Placeholder Text**: Update the hero description and application process paragraphs with actual content
2. **Add Real Images**: Replace placeholder images with actual dataset imagery
   - Current placeholders use: `https://via.placeholder.com/400x250/[COLOR]/FFFFFF?text=Dataset+[N]`
   - Replace with your own images or use a service like Unsplash
3. **Update Links**: Change all `#` links and the Microsoft Form URL to actual destinations
4. **Logo**: Consider adding an actual logo in the header
5. **Dataset Details**: Update the 7 dataset cards with your actual dataset information

## Image Recommendations

For best results, use images that are:
- 400x250 pixels (or 16:10 aspect ratio)
- High quality and relevant to each dataset
- Optimized for web (compressed)

## Color Scheme (from datapartnership.org)

The site uses the exact color palette from datapartnership.org:

- **Primary Navy**: `#001E60` (navbar, headings, primary text)
- **Orange Primary Button**: `#F7951D` (main CTA buttons)
- **Orange Hover**: `#DF6B00` (link hovers, button hovers)
- **Teal Line**: `#56C3C4` (decorative line accent)
- **Teal Secondary**: `#3DA3A8` (gradients, secondary elements)
- **Purple Dark**: `#310459` (gradient backgrounds)
- **Purple Sidebar**: `#2e2d70` (accents)
- **Light Gray Text**: `#737373` (footer links)

## Typography (from datapartnership.org)

- **Headings**: 'Asap Condensed', sans-serif
- **Body Text**: 'Roboto', sans-serif
- Both fonts loaded via Google Fonts

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

[Add your license information here]

## Contact

[Add contact information here]
