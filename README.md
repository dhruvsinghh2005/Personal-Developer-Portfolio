<div align="center">

# 🚀 Dhruv Raj Singh — Personal Developer Portfolio

A modern, responsive personal portfolio website built with **React**, **Tailwind CSS v4**, and **Vite**, featuring glassmorphism design, smooth animations, and an integrated contact form.

[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-Rolldown-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## ✨ Features

- **🎨 Glassmorphism UI** — Sleek, translucent card components with backdrop blur and glowing borders
- **⚡ Smooth Animations** — Fade-in reveals, floating elements, marquee skill ticker, and animated border buttons
- **📱 Fully Responsive** — Mobile-first design with a collapsible hamburger navigation
- **📬 Contact Form** — Functional email delivery powered by [EmailJS](https://www.emailjs.com/) (no backend required)
- **📄 Downloadable Resume** — One-click PDF resume download directly from the hero section
- **🌙 Dark Theme** — A curated dark color palette with teal accent colors for a premium look
- **🔗 Social Integration** — Direct links to GitHub and LinkedIn profiles

---

## 📸 Sections

| Section | Description |
|---------|-------------|
| **Hero** | Full-screen landing with profile photo, animated skill marquee, CTA buttons, and floating "Available for work" badge |
| **About** | Personal introduction with highlight cards (Full-Stack Development, Problem Solving, Team Collaboration, Continuous Learning) |
| **Projects** | Featured work showcase with hover-reveal links, tech tags, and expandable project grid |
| **Experience** | Interactive timeline with glowing connector line and role details |
| **Contact** | Working contact form with EmailJS integration, contact info cards, and availability status |

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| **Framework** | React 19 |
| **Styling** | Tailwind CSS v4 |
| **Build Tool** | Vite (Rolldown) |
| **Icons** | Lucide React |
| **Email Service** | EmailJS |
| **Fonts** | Inter, Playfair Display |
| **Linting** | ESLint 9 |

---

## 📁 Project Structure

```
Personal-Developer-Portfolio/
├── public/
│   ├── hero-bg.jpg              # Hero section background image
│   ├── profile-photo.jpg        # Profile photo
│   ├── resume.pdf               # Downloadable resume
│   └── projects/                # Project screenshot images
│       ├── project1.png
│       ├── project2.png
│       ├── project3.png
│       └── project4.png
├── src/
│   ├── assets/                  # Static assets (SVGs, etc.)
│   ├── components/              # Reusable UI components
│   │   ├── AnimatedBorderButton.jsx
│   │   └── Button.jsx
│   ├── layout/                  # Layout components
│   │   ├── Navbar.jsx
│   │   └── Footer.jsx
│   ├── sections/                # Page sections
│   │   ├── Hero.jsx
│   │   ├── About.jsx
│   │   ├── Projects.jsx
│   │   ├── Experience.jsx
│   │   ├── Testimonials.jsx
│   │   └── Contact.jsx
│   ├── App.jsx                  # Root application component
│   ├── main.jsx                 # Entry point
│   └── index.css                # Global styles & design tokens
├── index.html                   # HTML entry point
├── vite.config.js               # Vite configuration with path aliases
├── eslint.config.js             # ESLint configuration
├── package.json
└── .env.local                   # Environment variables (not committed)
```

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** ≥ 18
- **npm** ≥ 9

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/dhruvsinghh2005/Personal-Developer-Portfolio.git
   cd Personal-Developer-Portfolio
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env.local` file in the project root:

   ```env
   VITE_EMAILJS_SERVICE_ID=your_service_id
   VITE_EMAILJS_TEMPLATE_ID=your_template_id
   VITE_EMAILJS_PUBLIC_KEY=your_public_key
   ```

   > 💡 Sign up at [EmailJS](https://www.emailjs.com/) to get your credentials.

4. **Start the development server**

   ```bash
   npm run dev
   ```

   The app will be running at `http://localhost:5173`.

### Build for Production

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

## 🎨 Customization

### Colors & Theme

All design tokens are defined in `src/index.css` under the `@theme` block:

```css
@theme {
  --color-background: #0f1418;
  --color-primary: #20b2a6;
  --color-surface: #1a2329;
  /* ... */
}
```

### Adding Projects

Edit the `projects` array in `src/sections/Projects.jsx`:

```jsx
const projects = [
  {
    title: "Your Project Name",
    description: "A brief description of your project.",
    image: "/projects/your-image.png",
    tags: ["React", "Node.js", "MongoDB"],
    link: "https://your-live-demo.com",
    github: "https://github.com/your-repo",
  },
];
```

### Adding Experience

Edit the `experiences` array in `src/sections/Experience.jsx`:

```jsx
const experiences = [
  {
    period: "Jan 2025 — Present",
    role: "Your Role",
    company: "Company Name",
    description: "What you did...",
    technologies: ["React", "Node.js"],
    current: true,
  },
];
```

---

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start the development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build |
| `npm run lint` | Run ESLint for code quality checks |

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

**Built with ❤️ by [Dhruv Raj Singh](https://github.com/dhruvsinghh2005)**

</div>
