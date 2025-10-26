# Personal Portfolio Website

A modern, responsive, and customizable portfolio website built with HTML, CSS, and JavaScript.

##  Live Demo

Check out the live demo hosted on Netlify:  
**[https://venerable-fairy-91241f.netlify.app/](https://venerable-fairy-91241f.netlify.app/)**

## Features

-  Modern and attractive design with smooth animations
-  Fully responsive layout for all devices
-  Fast and lightweight performance
-  Smooth scrolling navigation with active states
-  Animated skill bars with progress indicators
-  Project filtering system by category
-  Contact form with validation
-  Research papers section with status indicators
-  Certifications display
-  Clean and professional UI/UX

## Customization Guide

### 1. Personal Information
Replace the following placeholders in `index.html`:
- **Your Name** - Your full name
- **Your Profession** - Your job title or field
- **Your Specialization** - Your areas of expertise
- Contact information (email, phone, location)
- Social media links (GitHub, LinkedIn, etc.)

### 2. Profile Photo
1. Add your photo to the `images/` folder
2. Name it `profile.jpg` (or update the path in HTML)
3. Recommended size: 400x400 pixels for best quality
4. Ensure the image is professional and well-cropped

### 3. Sections Content
Update each section with your personal information:

#### About Section
- Your professional bio and background
- Personal interests and goals
- Key achievements or highlights

#### Skills Section
- Your technical skills with proficiency levels (0-100%)
- Categorize skills (Programming, Data Science, Tools, etc.)
- Update skill percentages in both HTML and data attributes

#### Education Section
- Your academic history with dates
- Institution names and degrees
- Relevant coursework or achievements

#### Projects Section
- Your portfolio projects with:
  - Project title and description
  - Technologies used (tags)
  - Live demo and GitHub links
  - Project images (update placeholder images)

#### Research Section
- Your research papers and publications
- Co-authors and publication status
- Conference/journal information
- Links to papers or abstracts

#### Certifications Section
- Professional certifications
- Issuing organizations and dates
- Credential links

### 4. Styling Customization
Customize the appearance in `styles/style.css` by updating CSS variables in the `:root` section:

```css
:root {
    --primary: #2c3e50;      /* Main brand color */
    --secondary: #3498db;    /* Accent color */
    --accent: #e74c3c;       /* Highlight color */
    --success: #2ecc71;      /* Success states */
    --warning: #f39c12;      /* Warning states */
    /* ... other variables */
}
```

### 5. Deployment Options

#### Netlify (Recommended)
1. Fork this repository
2. Go to [netlify.com](https://netlify.com)
3. Connect your GitHub account
4. Select your repository
5. Deploy with default settings

#### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" and choose main branch
4. Your site will be available at `https://username.github.io/repository-name`

#### Vercel
1. Fork this repository
2. Go to [vercel.com](https://vercel.com)
3. Import your GitHub repository
4. Deploy with default settings

## File Structure
```
portfolio/
├── index.html              # Main HTML file
├── styles/
│   └── style.css           # All CSS styles
├── js/
│   └── script.js           # JavaScript functionality
├── images/
    └── profile.jpg         # Your profile photo

```

## Browser Support
-  Chrome (latest)
-  Firefox (latest)
-  Safari (latest)
-  Edge (latest)

## Performance Features
- Optimized images and assets
- Minimal JavaScript with efficient animations
- CSS variables for easy theming
- Responsive images and layouts
- Fast loading times

## Contributing
Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider submitting a pull request to help others!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License
This project is open source and available under the [MIT License](LICENSE).

## Support
If you encounter any issues or have questions:
1. Check the [live demo](https://venerable-fairy-91241f.netlify.app/) for reference
2. Review the customization guide above
3. Create an issue in the GitHub repository

## Example Customization Checklist
- [ ] Replace "Your Name" with actual name
- [ ] Update contact information
- [ ] Add profile photo
- [ ] Customize skills and percentages
- [ ] Add real projects with descriptions
- [ ] Update education history
- [ ] Add research papers (if any)
- [ ] Include certifications
- [ ] Test on different devices
- [ ] Deploy to hosting service

---

**Happy Coding!** 

Remember to replace all placeholder content with your actual information before deploying your portfolio. The live demo shows exactly how your portfolio will look once customized!