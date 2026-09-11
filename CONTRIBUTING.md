# Contributing to AI Resume Analyzer 📄

Thank you for your interest in contributing to **AI Resume Analyzer**! We welcome contributions, bug reports, feature requests, and feedback from the developer community.

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18.x or later)
- [npm](https://www.npmjs.com/) or `yarn` / `pnpm`

### Local Development Setup

1. **Fork & Clone the Repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/ai-resume-analyzer.git
   cd ai-resume-analyzer
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**
   Copy `.env.example` to `.env` (if applicable) and fill in required API keys:
   ```bash
   cp .env.example .env
   ```

4. **Start Development Server**
   ```bash
   npm run dev
   ```

---

## 🛠️ Contribution Guidelines

### Branch Naming Conventions

- `feature/feature-name` for new capabilities
- `fix/bug-description` for bug fixes
- `docs/documentation-change` for documentation updates
- `refactor/component-name` for code refactoring

### Commit Message Guidelines

We follow Conventional Commits specification:

- `feat: add PDF text extraction retry mechanism`
- `fix: resolve ATS score calculation edge case`
- `docs: update setup steps in README`
- `style: format score card component`

### Pull Request Process

1. Create a feature branch from `main`.
2. Ensure code passes linting and builds cleanly (`npm run build`).
3. Open a Pull Request using our [PR Template](.github/PULL_REQUEST_TEMPLATE.md).
4. Provide a detailed summary of your changes and attach screenshots if applicable.

---

## 🎨 Code Style

- Use **React functional components** with hooks.
- Maintain strict **TypeScript typing** (avoid `any`).
- Follow **Tailwind CSS** utility classes for styling.
- Run `npm run lint` before committing.

Thank you for making AI Resume Analyzer better! 🚀
