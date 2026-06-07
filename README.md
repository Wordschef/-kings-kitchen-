# King's Kitchen & Catering Services

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

A professional website for King's Kitchen & Catering Services, featuring a modern design with admin dashboard capabilities built with Supabase.

## 🌟 Features

- **Responsive Design**: Mobile-first approach, works seamlessly on all devices
- **Services Showcase**: Highlight corporate catering, event catering, and culinary training
- **Gallery Section**: Display previous events and work samples
- **Contact Form**: Easy customer inquiries and booking requests
- **Mobile Navigation**: Smooth hamburger menu for mobile devices
- **Modern UI/UX**: Professional color scheme with smooth animations
- **Backend Ready**: Supabase integration for future admin dashboard
- **SEO Optimized**: Meta tags and proper semantic HTML

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Wordschef/-kings-kitchen-.git
cd -kings-kitchen-
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file based on `.env.example`:
```bash
cp .env.example .env
```

4. Add your Supabase credentials to `.env`:
```
VITE_SUPABASE_URL=your_url
VITE_SUPABASE_ANON_KEY=your_key
```

### Development

Run the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:5173`

### Build

Build for production:
```bash
npm run build
```

### Preview

Preview production build:
```bash
npm run preview
```

## 📦 Deployment

### Deploy to Vercel

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
npm run deploy
```

### Deploy to Netlify

1. Connect your repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`

## 🎨 Customization

### Colors

Edit the CSS variables in `index.html` under `:root`:

```css
:root {
  --deep-green: #0F4C3A;
  --warm-gold: #D4A017;
  --light-green: #1a6b52;
  /* ... more colors ... */
}
```

### Content

Edit the relevant sections in `index.html`:
- Hero section
- Services cards
- About section
- Contact information
- Footer links

## 🔐 Security

- Never commit `.env` file to version control
- Use environment variables for sensitive data
- Keep Supabase API keys private
- Regularly update dependencies

## 📞 Contact Information

- **Location**: Mararaba, Abuja, Nigeria
- **Email**: info@kingskitchen.com
- **Phone**: +234 (0) XXX XXXX XXX
- **Hours**: Mon-Fri 9AM-6PM, Sat 10AM-5PM

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💼 Author

**Okrepke**
- GitHub: [@Wordschef](https://github.com/Wordschef)

## 🤝 Support

For support, email info@kingskitchen.com or create an issue on GitHub.

## 🙏 Acknowledgments

- Built with [Vite](https://vitejs.dev/)
- Backend powered by [Supabase](https://supabase.com/)
- Deployment ready for [Vercel](https://vercel.com/)

---

**Made with ❤️ for King's Kitchen & Catering Services**