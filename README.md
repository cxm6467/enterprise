# Enterprise Application

A modern web application built with Next.js, TypeScript, and Atomic Design principles.

## 🚀 Features

- ⚡ Next.js 14 with TypeScript
- 🎨 Atomic Design Architecture
- 🧪 Testing with Jest and React Testing Library
- 🧹 Code Quality with ESLint and Prettier
- 🛠️ Git Hooks with Husky

## 🛠️ Prerequisites

- Node.js 20.11.1+ (LTS)
- npm 10.5.0+

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/cxm6467/enterprise.git
   cd enterprise
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🧪 Testing

Run tests:
```bash
npm test
```

Run tests in watch mode:
```bash
npm run test:watch
```

## 🧹 Linting & Formatting

Lint code:
```bash
npm run lint
```

Format code:
```bash
npm run format
```

## 🏗️ Project Structure (Atomic Design)

```
src/
├── components/
│   ├── atoms/          # Basic building blocks (buttons, inputs, etc.)
│   ├── molecules/      # Groups of atoms (search bar, card header, etc.)
│   ├── organisms/      # Complex UI components (header, forms, etc.)
│   └── templates/      # Page-level layouts
├── pages/              # Next.js pages and API routes
├── styles/             # Global styles and themes
├── types/              # TypeScript type definitions
└── utils/              # Utility functions and helpers
```

## 🔧 Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/blog/next-14)
- **Language**: [TypeScript 5.0+](https://www.typescriptlang.org/docs/)
- **Styling**: [CSS Modules](https://github.com/css-modules/css-modules) (built-in with [Next.js](https://nextjs.org/docs/pages/building-your-application/styling/css-modules))
- **Testing**: [Jest](https://jestjs.io/), [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- **Linting**: [ESLint](https://eslint.org/), [Prettier](https://prettier.io/)
- **Version Control**: [Git](https://git-scm.com/)

## 📚 Documentation

- [Next.js Documentation](https://nextjs.org/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Atomic Design Methodology](https://bradfrost.com/blog/post/atomic-web-design/)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

Made with ❤️ by [Your Name] ← intentionally keeping this line as is.
