# Hamed Ahmed - Software Engineer Portfolio

A modern, responsive portfolio website built with HTML, CSS, and Tailwind CSS. This portfolio showcases my skills, projects, and professional experience as a software engineer.

## 🚀 Features

- **Modern Design**: Clean and professional design with smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth scrolling navigation and hover effects
- **Fast Loading**: Optimized for performance with CDN resources
- **SEO Friendly**: Proper meta tags and semantic HTML structure

## 📋 Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Me**: Professional background and key statistics
3. **Skills & Technologies**: Visual representation of technical skills
4. **Featured Projects**: Showcase of best work with technology tags
5. **Contact**: Contact form and social media links

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography

## 📦 Installation & Setup

### Prerequisites
- A modern web browser
- Basic knowledge of HTML/CSS (for customization)

### Quick Start
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Customize the content to match your information

## 🎨 Customization Guide

### Personal Information
Update the following sections in `index.html`:

#### Hero Section
```html
<h1 class="text-5xl md:text-7xl font-bold mb-6">
    Your Name
</h1>
<h2 class="text-2xl md:text-3xl mb-8 text-blue-100">
    Your Title
</h2>
```

#### About Section
- Update the description text
- Modify the statistics (years of experience, projects completed, etc.)
- Change location and availability information

#### Skills Section
- Adjust skill levels by modifying the width percentages
- Add or remove skills as needed
- Update technology names

#### Projects Section
- Replace placeholder projects with your actual work
- Update project descriptions and technologies
- Add real GitHub and demo links

#### Contact Section
- Update email address and phone number
- Add your actual social media links
- Customize the contact form

### Profile Picture
Replace the placeholder image:
```html
<img src="path/to/your/photo.jpg" 
     alt="Your Name" 
     class="w-32 h-32 rounded-full mx-auto mb-6 border-4 border-white/30">
```

### Color Scheme
Modify the primary colors in the Tailwind config:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#3B82F6',    // Change this to your preferred color
                secondary: '#1F2937',
                accent: '#10B981'
            }
        }
    }
}
```

## 🌐 Deployment to GitHub Pages

### Method 1: Using GitHub Desktop
1. Create a new repository on GitHub
2. Clone it to your local machine using GitHub Desktop
3. Copy all portfolio files to the repository folder
4. Commit and push to GitHub
5. Go to repository Settings > Pages
6. Select "Deploy from a branch" and choose "main" branch
7. Your portfolio will be available at `https://yourusername.github.io/repository-name`

### Method 2: Using Command Line
```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial portfolio commit"

# Add remote repository (replace with your GitHub repo URL)
git remote add origin https://github.com/yourusername/your-repo-name.git

# Push to GitHub
git push -u origin main

# Enable GitHub Pages in repository settings
```

### Method 3: Direct Upload
1. Create a new repository on GitHub
2. Upload all files directly through the GitHub web interface
3. Enable GitHub Pages in repository settings

## 📱 Mobile Optimization

The portfolio is fully responsive and includes:
- Mobile-first design approach
- Touch-friendly navigation
- Optimized images and content
- Fast loading on mobile networks

## 🔧 Performance Optimization

- CDN resources for faster loading
- Optimized images and assets
- Minimal JavaScript for better performance
- Efficient CSS with Tailwind's purge feature

## 📈 SEO Optimization

- Semantic HTML structure
- Proper meta tags
- Alt text for images
- Clean URL structure
- Fast loading times

## 🎯 Best Practices

- Keep content updated and relevant
- Use high-quality images
- Include real project links
- Maintain consistent branding
- Regular updates and improvements

## 📞 Support

If you need help customizing or deploying your portfolio:

1. Check the customization guide above
2. Review the HTML structure and comments
3. Test on different devices and browsers
4. Validate your HTML and CSS

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Font Awesome](https://fontawesome.com/) for the icons
- [Google Fonts](https://fonts.google.com/) for typography

---

**Note**: Remember to replace all placeholder content with your actual information before deploying. This includes your name, contact details, projects, and social media links.

Happy coding! 🚀
