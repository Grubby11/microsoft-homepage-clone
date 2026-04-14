# Microsoft Homepage Clone

> A modern, responsive clone of the Microsoft homepage built with React, Vite, and Tailwind CSS v4.2

## 🌐 Live Demo

**[Visit the Live Website](https://YOUR-PROJECT.vercel.app)** ← Replace with your actual Vercel URL

---

## ✨ Features

- ⚡ **Lightning Fast** - Built with Vite for instant HMR and optimized builds
- 🎨 **Modern Design** - Responsive design using Tailwind CSS v4.2
- 📱 **Mobile Friendly** - Fully responsive across all devices
- 🔍 **SEO Optimized** - Meta tags and semantic HTML
- ♿ **Accessible** - WCAG compliant markup
- 🚀 **Production Ready** - Deployed on Vercel with auto-deployment

---

## 🛠️ Tech Stack

- **Frontend Framework:** React 18+
- **Build Tool:** Vite
- **Styling:** Tailwind CSS v4.2
- **Hosting:** Vercel
- **Version Control:** Git & GitHub

---

## 📋 Prerequisites

Before you begin, ensure you have:
- Node.js (v16 or higher)
- npm or yarn
- Git

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/microsoft-homepage-clone.git
cd microsoft-homepage-clone
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm run dev
```

Visit `http://localhost:5173` in your browser. The app will automatically reload when you make changes.

---

## 📦 Available Scripts

```bash
# Start development server with HMR
npm run dev

# Build for production
npm run build

# Preview production build locally
npm run preview

# Run linting (if ESLint is configured)
npm run lint
```

---

## 📁 Project Structure

```
microsoft-homepage-clone/
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable components
│   ├── pages/          # Page components
│   ├── App.jsx         # Main app component
│   ├── App.css         # App styles
│   ├── index.css       # Global styles with Tailwind
│   └── main.jsx        # Entry point
├── index.html          # HTML template
├── package.json        # Dependencies and scripts
├── vite.config.js      # Vite configuration
├── tailwind.config.js  # Tailwind CSS configuration
├── postcss.config.js   # PostCSS configuration
├── vercel.json         # Vercel deployment config
└── README.md           # This file
```

---

## 🎨 Tailwind CSS Configuration

Tailwind CSS v4.2 is already configured. To customize:

1. Edit `tailwind.config.js` for theme extensions
2. Edit `src/index.css` for custom styles
3. Run `npm run build` to generate optimized CSS

---

## 🚀 Deployment

This project is deployed on **Vercel** with automatic deployments.

### Deploy Your Own

1. Push your code to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Select this repository
4. Click "Deploy"
5. Your site is live! 🎉

### Auto-Deployment

Every push to the `main` branch automatically deploys to production.

---

## 🔧 Configuration Files

### `vercel.json`
```json
{
  "buildCommand": "npm run build",
  "outputDirectory": "dist"
}
```

### `vite.config.js`
```javascript
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

export default defineConfig({
  plugins: [react()],
})
```

### `tailwind.config.js`
```javascript
export default {
  content: [
    './index.html',
    './src/**/*.{js,jsx,ts,tsx}',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

---

## 📝 Environment Variables

If you need environment variables:

1. Create `.env.local` in project root (not tracked by git)
2. Add variables with `VITE_` prefix:
   ```
   VITE_API_URL=https://api.example.com
   VITE_PUBLIC_KEY=your_public_key
   ```
3. Access in code:
   ```javascript
   const apiUrl = import.meta.env.VITE_API_URL
   ```

For production, add variables in Vercel Dashboard → Settings → Environment Variables

---

## 🎯 Performance Optimizations

✅ **CSS Optimization** - Tailwind purges unused styles automatically  
✅ **Code Splitting** - Vite automatically splits code at route boundaries  
✅ **Image Optimization** - Serve optimized images  
✅ **Lazy Loading** - Implement for images and components  
✅ **Minification** - Vite minifies all assets in production  

---

## 🐛 Troubleshooting

### Styles not showing?
```bash
npm run build
vercel --prod
```

### Port 5173 already in use?
```bash
npm run dev -- --port 3000
```

### Build fails?
```bash
rm -rf node_modules dist
npm install
npm run build
```

---

## 📚 Learning Resources

- [Vite Documentation](https://vitejs.dev)
- [React Documentation](https://react.dev)
- [Tailwind CSS v4 Documentation](https://tailwindcss.com/docs)
- [Vercel Documentation](https://vercel.com/docs)

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Your Name**
- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)
- Portfolio: [Your Portfolio](https://yourportfolio.com)

---

## 🙏 Acknowledgments

- Inspired by Microsoft's official homepage
- Built with modern web technologies
- Deployed on Vercel's amazing platform

---

## 📞 Support

If you encounter any issues:

1. Check the [Troubleshooting](#-troubleshooting) section
2. Open an [issue on GitHub](https://github.com/YOUR_USERNAME/microsoft-homepage-clone/issues)
3. Check related documentation links above

---

**Last Updated:** April 2026  
**Status:** ✅ Production Ready

---

## 🔗 Quick Links

| Link | Description |
|------|-------------|
| [Live Site](https://YOUR-PROJECT.vercel.app) | View deployed website |
| [GitHub Repo](https://github.com/YOUR_USERNAME/microsoft-homepage-clone) | Source code |
| [Issues](https://github.com/YOUR_USERNAME/microsoft-homepage-clone/issues) | Report bugs |
| [Discussions](https://github.com/YOUR_USERNAME/microsoft-homepage-clone/discussions) | Ask questions |
