# Nguyễn Anh Kiệt - Portfolio Website

A modern, responsive portfolio website showcasing software engineering skills and projects. Features a clean design with dark/light theme toggle, smooth animations, and comprehensive project showcase.

## 🚀 Live Demo

Visit the live website: [https://koniz-dev.github.io/koniz-dev-portfolio](https://koniz-dev.github.io/koniz-dev-portfolio)

## ✨ Features

- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Dark/Light Theme**: Toggle between dark and light themes with persistent preference
- **Smooth Animations**: Intersection Observer API for scroll-triggered animations
- **Modern UI/UX**: Clean, professional design with gradient accents and smooth transitions
- **Interactive Navigation**: Smooth scrolling navigation with active section highlighting
- **Project Showcase**: Comprehensive display of technical skills and featured projects
- **Contact Integration**: Direct links to email, LinkedIn, and GitHub
- **Performance Optimized**: Fast loading with optimized assets and modern CSS
- **Accessibility**: Proper semantic HTML, ARIA attributes, and keyboard navigation

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with proper structure and accessibility
- **CSS3**: Modern styling with CSS Grid, Flexbox, and CSS Custom Properties
- **Vanilla JavaScript**: Interactive features, theme toggle, and smooth scrolling
- **Font Awesome**: Professional icons for UI elements
- **Google Fonts**: Inter font family for modern typography
- **CSS Variables**: Dynamic theming with light/dark mode support
- **Intersection Observer API**: Scroll-triggered animations
- **Local Storage**: Theme preference persistence
- **GitHub Pages**: Free hosting and deployment

## 📁 Project Structure

```
koniz-dev-portfolio/
├── index.html          # Main HTML file with portfolio content
├── style.css           # Main stylesheet with theme support
├── avatar.jpg          # Profile avatar image
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Git (for cloning the repository)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/koniz-dev/koniz-dev-portfolio.git
```

2. Navigate to the project directory:
```bash
cd koniz-dev-portfolio
```

3. Open `index.html` in your web browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000

# Using Live Server (VS Code extension)
# Right-click on index.html and select "Open with Live Server"
```

## 🎨 Customization

### Updating Personal Information

Edit the following sections in `index.html`:

- **Hero Section** (lines 32-96): Name, title, professional summary, and contact information
- **Skills Section** (lines 98-178): Technical skills organized by categories
- **Experience Section** (lines 180-244): Work experience timeline
- **Projects Section** (lines 246-302): Featured projects showcase
- **Education Section** (lines 304-319): Academic background
- **Contact Section** (lines 321-360): Contact information and social links

### Styling

Modify `style.css` to customize:
- **CSS Variables** (lines 8-43): Color schemes for light and dark themes
- **Typography**: Font families and text styling
- **Layout**: Grid and flexbox layouts
- **Animations**: Transitions and scroll-triggered effects
- **Theme Colors**: Primary, secondary, and accent colors

### Theme Customization

The website supports both light and dark themes. To customize:
1. Modify CSS variables in `:root` for light theme
2. Update `.dark-theme` variables for dark theme
3. Theme preference is automatically saved in localStorage

### Avatar Image

Replace `avatar.jpg` with your own profile picture:
- Recommended size: 300x300px or larger
- Format: JPG, PNG, or WebP
- The image includes a fallback icon if loading fails

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Key Features Explained

### Theme Toggle
- Click the moon/sun icon in the navigation to switch themes
- Theme preference is automatically saved and restored on page reload
- Smooth transitions between light and dark modes

### Smooth Scrolling
- Navigation links smoothly scroll to corresponding sections
- Scroll-to-top button appears when scrolling down
- Intersection Observer API triggers animations as sections come into view

### Responsive Design
- Mobile-first approach with progressive enhancement
- Optimized layouts for all screen sizes
- Touch-friendly navigation and interactions

## 🚀 Deployment

### GitHub Pages (Recommended)

1. Push your code to a GitHub repository
2. Go to Repository Settings → Pages
3. Select "Deploy from a branch"
4. Choose your main branch and root folder
5. Your site will be available at `https://yourusername.github.io/koniz-dev-portfolio`

### Other Hosting Options

- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **Firebase Hosting**: Google's hosting platform
- **Any static hosting service**

## 🔧 Browser Support

- Chrome 60+ (full support)
- Firefox 55+ (full support)
- Safari 12+ (full support)
- Edge 79+ (full support)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Nguyễn Anh Kiệt**
- GitHub: [@koniz-dev](https://github.com/koniz-dev)
- LinkedIn: [koniz-dev](https://www.linkedin.com/in/koniz-dev)
- Email: kietna.work@gmail.com

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/koniz-dev/koniz-dev-portfolio/issues).

## ⭐ Show Your Support

Give a ⭐️ if this project helped you!

---

*Built with ❤️ by Nguyễn Anh Kiệt*
