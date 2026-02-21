# AIToolsHub

AI Tools Reviews & Comparisons - Discover the best AI software for your needs.

## Features

- 🔍 **Search & Filter** - Find AI tools by category, pricing, or use case
- ⭐ **Expert Reviews** - Detailed ratings and honest assessments
- 🏷️ **Categories** - Writing, Image, Video, Code, Chatbots, and more
- 🔗 **Affiliate Links** - Direct access to tool websites
- 📱 **Responsive Design** - Works on all devices
- 🎨 **Dark Theme** - Modern UI with cyan accents

## Tech Stack

- **React 18** - UI Library
- **TypeScript** - Type Safety
- **Vite** - Build Tool
- **Tailwind CSS** - Styling
- **shadcn/ui** - Component Library
- **Lucide React** - Icons

## Getting Started

### Prerequisites

- Node.js 20+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/aitoolshub.git

# Navigate to project
cd aitoolshub

# Install dependencies
npm install

# Start development server
npm run dev
```

### Build for Production

```bash
npm run build
```

The `dist` folder will contain the production build.

## Deployment

### Vercel (Recommended)

```bash
npm i -g vercel
vercel
```

### Netlify

```bash
npm run build
# Drag dist/ folder to Netlify Drop
```

## Project Structure

```
├── src/
│   ├── main.tsx          # App entry point
│   ├── App.tsx           # Main component
│   ├── index.css         # Global styles
│   └── App.css           # Component styles
├── index.html            # HTML template
├── package.json          # Dependencies
├── vite.config.ts        # Vite config
├── tailwind.config.js    # Tailwind config
└── tsconfig.json         # TypeScript config
```

## Customization

### Adding New Tools

Edit `src/App.tsx` and add to the `tools` array:

```typescript
{
  id: "7",
  name: "Your Tool",
  description: "Description here",
  category: "Category",
  rating: 4.5,
  pricing: "Freemium",
  affiliateUrl: "https://example.com",
  features: ["Feature 1", "Feature 2"]
}
```

### Styling

- Colors defined in `tailwind.config.js`
- Custom utilities in `src/index.css`
- Component styles in `src/App.css`

## License

MIT License - feel free to use this for your own projects.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

Built with ❤️ using React, Vite, and Tailwind CSS.