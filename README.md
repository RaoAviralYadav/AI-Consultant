# AI Agency Landing Page

A modern, responsive landing page for an AI consulting agency built with Next.js 16, React 19, and Tailwind CSS 4. Features stunning 3D animations, interactive components, and a professional design system.

## ✨ Features

- **Modern Tech Stack**: Built with Next.js 16 App Router and React 19
- **Beautiful UI**: Powered by shadcn/ui components with custom styling
- **3D Animations**: Interactive Spline 3D scenes for engaging visuals
- **Responsive Design**: Fully responsive across all devices
- **Dark Mode Ready**: Built-in theme support with next-themes
- **Performance Optimized**: Fast loading times with Next.js optimizations
- **Type Safe**: Full TypeScript support throughout the project

## 🛠️ Tech Stack

- **Framework**: Next.js 16.0.5
- **React**: 19.2.0
- **Styling**: Tailwind CSS 4.1.17
- **UI Components**: shadcn/ui (Radix UI primitives)
- **3D Graphics**: Spline, Three.js, React Three Fiber
- **Animations**: Framer Motion
- **Typography**: Geist Sans & Geist Mono fonts
- **Analytics**: Vercel Analytics
- **Icons**: Lucide React

## 📦 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd my-v0-project
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
# or
yarn install
```

3. Run the development server:
```bash
npm run dev
# or
pnpm dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🏗️ Project Structure

```
├── app/
│   ├── globals.css          # Global styles and Tailwind config
│   ├── layout.tsx            # Root layout component
│   ├── page.tsx              # Home page
│   ├── privacy/              # Privacy policy page
│   └── terms/                # Terms of service page
├── components/
│   └── ui/                   # Reusable UI components
├── hooks/                    # Custom React hooks
├── lib/                      # Utility functions
└── public/                   # Static assets
```

## 🎨 Key Components

### Custom UI Components
- **Navbar**: Responsive navigation with smooth scrolling
- **Hero Section**: Eye-catching hero with 3D Spline scene
- **Bento Grid**: Modern grid layout for services showcase
- **Pricing Cards**: Flexible pricing component with toggle
- **Testimonials**: Customer testimonial cards
- **Animated Backgrounds**: Gradient and particle effects

### Pages
- **Home** (`/`): Main landing page with all sections
- **Privacy Policy** (`/privacy`): Privacy policy page
- **Terms of Service** (`/terms`): Terms and conditions page

## 🎯 Features Breakdown

### Hero Section
- 3D interactive Spline scene
- Spotlight effect animation
- Clear call-to-action buttons
- Trust indicators

### Services Section
- Bento grid layout
- Service cards with icons
- Hover effects and animations

### Social Proof
- Customer testimonials
- Star ratings
- Company information

### Pricing
- Three-tier pricing structure
- Monthly/yearly toggle
- Feature comparison
- Clear CTAs

### Footer
- Multi-column layout
- Social media links
- Company information
- Quick links

## 🚀 Deployment

### Vercel (Recommended)
```bash
npm run build
vercel --prod
```

### Other Platforms
```bash
npm run build
npm run start
```

## 📝 Environment Variables

No environment variables required for basic functionality. For analytics:

```env
# Optional: Vercel Analytics
NEXT_PUBLIC_VERCEL_ANALYTICS=true
```

## 🎨 Customization

### Colors
Edit `app/globals.css` to customize the color scheme:
```css
:root {
  --primary: /* your color */;
  --secondary: /* your color */;
  /* ... */
}
```

### Content
- Update text content in `app/page.tsx`
- Modify metadata in `app/layout.tsx`
- Replace logo/icons in `/public`

## 📱 Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🔧 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 📄 License

This project uses the following open-source components:
- Next.js (MIT)
- React (MIT)
- Tailwind CSS (MIT)
- shadcn/ui (MIT)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

For support, email hello@aiagency.com or visit our website.

## 🎓 Credits

- **UI Components**: Built with [shadcn/ui](https://ui.shadcn.com/)
- **3D Scenes**: Created with [Spline](https://spline.design/)
- **Fonts**: [Geist](https://vercel.com/font) by Vercel
- **Icons**: [Lucide](https://lucide.dev/)

---

Built with ❤️ using Next.js and Tailwind CSS
~ Aviral Yadav