# Aziz Shahiwala's Portfolio

Thank you for taking the time to visit and contribute to this portfolio project. This document outlines how you can report issues, suggest improvements, or contribute changes.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Folder Structure](#folder-structure)
- [How to Contribute](#how-to-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Improvements](#suggesting-improvements)
- [Code Style Guidelines](#code-style-guidelines)
- [Commit Message Format](#commit-message-format)
- [Contact](#contact)

---

## Project Overview

This is a personal portfolio website built with plain HTML, CSS, and JavaScript. It is hosted on GitHub Pages and showcases projects, skills, education, and certificates.

**Live site:** https://azizshahiwala.github.io/Portfolio

**Tech stack:**
- HTML5
- CSS3 (with media queries for responsiveness)
- Vanilla JavaScript
- Font Awesome 6.5.0 (CDN)

---

## Folder Structure

```
Portfolio/
├── index.html              # Main HTML file
├── styles.css              # All CSS styles
├── script.js               # JavaScript (hamburger menu, interactions)
└── assets/
    ├── photo.jpg           # Profile photo
    ├── aboutme.png         # About section background image
    └── certificates/       # Certificate images and PDFs
```

---

## How to Contribute

### 1. Fork the repository

Click the **Fork** button at the top right of the repository page on GitHub.

### 2. Clone your fork locally

```bash
git clone https://github.com/your-username/Portfolio.git
cd Portfolio
```

### 3. Create a new branch

Always work on a new branch, never directly on `main` or `master`:

```bash
git checkout -b fix/your-fix-name
# or
git checkout -b feature/your-feature-name
```

### 4. Make your changes

Open the project in your editor and make the necessary changes.

### 5. Test locally

Open `index.html` directly in a browser or use a local server:

```bash
# Using VS Code Live Server extension (recommended)
# Or using Python
python -m http.server 5500
```

Check the following before submitting:
- [ ] Site loads without errors in the browser console
- [ ] Layout looks correct on desktop (1280px+)
- [ ] Layout looks correct on tablet (768px)
- [ ] Layout looks correct on mobile (375px)
- [ ] Nav hamburger menu works on mobile
- [ ] All links open correctly

### 6. Commit and push

```bash
git add .
git commit -m "fix: describe what you fixed"
git push origin fix/your-fix-name
```

### 7. Open a Pull Request

Go to the original repository on GitHub and click **New Pull Request**. Describe what you changed and why.

---

## Reporting Bugs

If you find a bug, please open a [GitHub Issue](https://github.com/Azizshahiwala/Portfolio/issues) and include:

- A clear title describing the bug
- Steps to reproduce it
- What you expected to happen
- What actually happened
- Screenshot if applicable
- Browser and device you were using

**Example:**

```
Title: Nav links not scrolling to correct section on mobile

Steps to reproduce:
1. Open site on mobile (375px)
2. Tap hamburger menu
3. Tap "Projects"

Expected: Page scrolls to Projects section
Actual: Page does not scroll, stays at top

Browser: Chrome 120 on Android
```

---

## Suggesting Improvements

Open a [GitHub Issue](https://github.com/Azizshahiwala/Portfolio/issues) with the label `enhancement` and describe:

- What you would like to see improved
- Why it would be beneficial
- Any reference or example if applicable

---

## Code Style Guidelines

Please follow these conventions to keep the code consistent:

### HTML
- Use semantic tags (`<section>`, `<header>`, `<nav>`) over generic `<div>` where appropriate
- All section IDs follow the pattern `main-sectionname` (e.g. `main-about`, `main-skills`)
- Class names use kebab-case (e.g. `about-content`, `skill-item`)

### CSS
- All colors use the existing theme variables:
  - Accent green: `#8ade2a`
  - Dark background: `#0f2525`
  - Card background: `rgba(255,255,255,0.05)`
  - Primary text: `#ffffff`
  - Muted text: `#aaaaaa`
- Media query breakpoints:
  - Mobile: `max-width: 767px`
  - Tablet: `min-width: 768px` and `max-width: 1023px`
  - Desktop: `min-width: 1024px`
- Do not add inline styles — use CSS classes instead

### JavaScript
- Keep JS minimal — only for interactions (hamburger menu, animations)
- Use `addEventListener` over inline `onclick` in new code
- No external JS libraries — vanilla JS only

---

## Commit Message Format

Use this format for all commits:

```
type: short description
```

**Types:**

| Type | When to use |
|---|---|
| `fix` | Bug fix |
| `feat` | New feature or section |
| `style` | CSS or visual changes |
| `content` | Text or content updates |
| `refactor` | Code restructure, no visual change |
| `docs` | Changes to documentation |

**Examples:**

```
fix: hamburger menu not closing after link click
feat: add achievements section
style: update card hover animation timing
content: update about bio text
```

---

## Contact

If you have any questions or want to reach out directly:

- **Email:** shahiwalaaziz8@outlook.com
- **LinkedIn:** https://www.linkedin.com/in/aziz-shahiwala-ab5b27288/
- **GitHub:** https://github.com/Azizshahiwala

---

*This portfolio is a personal project and is actively being developed. Contributions that improve quality, accessibility, or design are always welcome.*
