# Modern Web Solutions

A beautiful, responsive website built with Vite, React, TypeScript, and Tailwind CSS. Perfect for showcasing modern web development capabilities.

## 🚀 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Fully Responsive**: Optimized for all devices and screen sizes
- **Performance Optimized**: Built with Vite for lightning-fast development and builds
- **TypeScript**: Type-safe development experience
- **Tailwind CSS**: Utility-first CSS framework for rapid styling
- **Lucide Icons**: Beautiful, customizable icons
- **GitHub Pages Ready**: Configured for easy deployment

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Deployment**: GitHub Pages (via GitHub Actions)

## 📦 Getting Started

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd <your-repo-name>
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 🚀 Deployment to GitHub Pages

This project is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setup Instructions:

1. **Push to GitHub**: Push your code to a GitHub repository
2. **Enable GitHub Pages**: 
   - Go to your repository settings
   - Navigate to "Pages" section
   - Set source to "GitHub Actions"
3. **Automatic Deployment**: The site will automatically deploy when you push to the main branch

### Manual Deployment:

If you prefer manual deployment:

```bash
npm run build
# Then upload the 'dist' folder to your hosting provider
```

## 📁 Project Structure

```
├── src/
│   ├── App.tsx          # Main application component
│   ├── main.tsx         # Application entry point
│   ├── index.css        # Global styles with Tailwind
│   └── vite-env.d.ts    # Vite type definitions
├── public/              # Static assets
├── .github/
│   └── workflows/
│       └── deploy.yml   # GitHub Actions deployment
├── index.html           # HTML template
├── vite.config.ts       # Vite configuration
├── tailwind.config.js   # Tailwind CSS configuration
└── package.json         # Dependencies and scripts
```

## 🎨 Customization

### Colors
The site uses a blue and purple color scheme. You can customize colors in:
- `tailwind.config.js` for theme colors
- `src/App.tsx` for component-specific colors

### Content
Update the content in `src/App.tsx`:
- Hero section text and call-to-action
- Features and services
- About section information
- Contact information
- Footer links

### Images
Replace the Unsplash images with your own:
- Update image URLs in the `src/App.tsx` file
- Add your own images to the `public` folder

## 📱 Responsive Design

The website is fully responsive with breakpoints for:
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## ⚡ Performance Features

- **Lazy Loading**: Images and components load as needed
- **Optimized Assets**: Vite automatically optimizes assets for production
- **Modern JavaScript**: Uses ES modules for better performance
- **CSS Optimization**: Tailwind CSS purges unused styles

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

## 📞 Support

If you have any questions or need help with deployment, please open an issue or contact the development team.

---

Built with ❤️ using ChatAndBuild
