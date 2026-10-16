# Nguyễn Anh Kiệt - Portfolio Website

A developer-flavoured, responsive portfolio website. The UI borrows from the tools engineers live in: a typing terminal with `neofetch` in the hero, `git log --graph` work history, editor-style skill files and repo-style project cards — with dark/light themes and smooth animations.

## 🚀 Live Demo

Visit the live website: [https://koniz-dev.github.io/koniz-portfolio](https://koniz-dev.github.io/koniz-portfolio)

## ✨ Features

- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Dark/Light Theme**: Toggle between dark and light themes with persistent preference
- **Smooth Animations**: Intersection Observer API for scroll-triggered animations
- **Terminal / IDE aesthetic**: Animated terminal hero, git-log timeline, syntax-highlight colour palette
- **Interactive Navigation**: Smooth scrolling, active section highlighting, scroll progress bar and mobile menu
- **Project Showcase**: Comprehensive display of technical skills and featured projects
- **Contact Integration**: Direct links to email, LinkedIn, and GitHub
- **Performance Optimized**: Fast loading with optimized assets and modern CSS
- **Accessibility**: Proper semantic HTML, ARIA attributes, and keyboard navigation

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with proper structure and accessibility
- **CSS3**: Modern styling with CSS Grid, Flexbox, and CSS Custom Properties
- **Vanilla JavaScript**: Interactive features, theme toggle, and smooth scrolling
- **Inline SVG icons**: Font Awesome Free icons embedded as an SVG sprite (no icon font download)
- **Google Fonts**: Inter for body text, JetBrains Mono for code-flavoured UI
- **CSS Variables**: Dynamic theming with light/dark mode support
- **Intersection Observer API**: Scroll-triggered animations
- **Local Storage**: Theme preference persistence
- **GitHub Pages + GitHub Actions**: Deployed by `.github/workflows/deploy.yml` on every push to `main`

## 📁 Project Structure

```
koniz-portfolio/
├── .github/workflows/
│   └── deploy.yml      # GitHub Pages deployment
├── index.html          # Main HTML file with portfolio content
├── 404.html            # Terminal-style not-found page
├── style.css           # Main stylesheet with theme support
├── avatar.jpg          # Profile avatar image (256x256)
├── avatar-128.jpg      # Smaller avatar for low-DPI screens
├── favicon.svg         # Site icon
├── og.jpg              # Link preview image (1200x630)
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Git (for cloning the repository)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/koniz-dev/koniz-portfolio.git
```

2. Navigate to the project directory:
```bash
cd koniz-portfolio
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

- **Hero Section**: Name, title, professional summary, and contact information
- **Skills Section**: Technical skills organized by categories
- **Experience Section**: Work experience timeline
- **Projects Section**: Featured projects showcase
- **Education Section**: Academic background
- **Contact Section**: Contact information and social links

### Styling

Modify `style.css` to customize:
- **CSS Variables**: Color schemes for light and dark themes
- **Typography**: Font families and text styling
- **Layout**: Grid and flexbox layouts
- **Animations**: Transitions and scroll-triggered effects
- **Theme Colors**: Primary, secondary, and accent colors

### Theme Customization

The website supports both light and dark themes. To customize:
1. Modify CSS variables in `:root` for the dark theme (default)
2. Update `:root[data-theme="light"]` variables for the light theme
3. Theme preference is saved in localStorage; first visit follows the OS setting

### Avatar Image

Replace `avatar.jpg` with your own profile picture:
- Recommended size: 256x256px (it is displayed at 112px)
- Format: JPG, PNG, or WebP
- The image includes a fallback icon if loading fails

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Key Features Explained

### Theme Toggle
- Click the sun/moon icon in the navigation to switch themes
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

1. Go to Repository Settings → Pages and set **Source** to **GitHub Actions**
2. Push to `main` — `.github/workflows/deploy.yml` publishes the site
3. Only the files copied in the workflow's "Collect site files" step are published, so add any new asset there

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
- LinkedIn: [koniz-dev](https://www.linkedin.com/in/kiet-nguyen-583463276)
- Email: kietna.work@gmail.com

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/koniz-dev/koniz-portfolio/issues).

## ⭐ Show Your Support

Give a ⭐️ if this project helped you!

---

*Built with ❤️ by Nguyễn Anh Kiệt*
