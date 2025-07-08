# cow-boy-css

## 🐎 cow-boy-css

cow-boy-css is a minimal, mobile-first CSS utility framework made for developers who prefer to ride light and fast—no build tools, no configs, just pure CSS.
Inspired by modern utility-first frameworks like Tailwind CSS, but stripped down to its bare essentials for simplicity, speed, and total control.

## Features

-⚡ Lightweight & Fast: No build steps, no dependencies—just drop it in and ride.

-🪶 Utility-First: Compose styles using small, reusable CSS classes.

-📱 Mobile-First & Responsive: Designed to be fluid and flexible by default.

-📂 Modular: Clean separation of concerns with organized CSS files.

-💾 Reusable Across Projects: Use it on any project, anytime—your own CSS toolbelt.

## Folder structure

```
cow-boy-css/
├── css/
│   ├── base.css          # Resets & basic styles
│   ├── colors.css        # Color utilities (backgrounds, text colors)
│   ├── typography.css    # Font sizes, alignment, font weights
│   ├── spacing.css       # Padding, margin, gap utilities
│   ├── layout.css        # Flexbox, grid, containers
│   ├── responsive.css    # Media query utilities for breakpoints
│   └── index.css         # Main entry point that imports all above files
│
├── testing/              # Local testing sandbox (optional, ignored if needed)
│   ├── index.html        # Test page for trying out classes
│   └── test-styles.css   # Extra testing styles (optional)
│
├── .gitignore            # Git ignore settings (optional testing exclusions)
├── LICENSE               # License (MIT recommended)
└── README.md             # You’re reading it
```

## How to use

### Via CDN

Skip downloading! Use cow-boy-css straight from GitHub with [jsDelivr](https://www.jsdelivr.com/):

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/Cyden-Mnara/cow-boy-css/css/index.css"
/>
```

### Clone repo:

```
 git clone https://github.com/Cyden-Mnara/cow-boy-css.git

```

### Add as a Git Submodule:

```
 git submodule add https://github.com/Cyden-Mnara/cow-boy-css.git

```

### Pull Latest Updates (for Submodules):

```
 git submodule update --remote --merge

```

1. In your HTML ,import `index.css`:

```
<link rel="stylesheet" href="path/cow-boy-css/css/index.css" />

```

2. Start styling using utility classes like:

```
<div class="container bg-primary text-center p-4 sm:flex">
  <h1 class="text-lg font-bold text-white">Howdy, Partner! 🤠</h1>
</div>

```

### For React / Vite / CRA:

Import directly into your main CSS entry point (e.g. main.css or App.css):

```
@import url('cow-boy-css/css/index.css');

```

If you're using CSS Modules, import it globally in index.js or main.jsx:

```
import 'cow-boy-css/css/index.css';

```

### For Vue / Nuxt:

In Nuxt 3 or Vue CLI, add to your global CSS (e.g. assets/main.css):

```
@import url('cow-boy-css/css/index.css');

```

Or, directly in your main entry file:

```
// nuxt.config.js or nuxt.config.ts
css: ['cow-boy-css/css/index.css']

```

## Responsive Breakpoints

The following prefixes allow you to apply utility classes at specific viewport widths:

| Prefix | Min Width | Example Class |
| ------ | --------- | ------------- |
| `sm:`  | 640px     | `sm:flex`     |
| `md:`  | 768px     | `md:p-8`      |
| `lg:`  | 1024px    | `lg:flex-row` |

Just add the prefix before any utility class to make it responsive at the given breakpoint.

## Philosophy:

"Wrangle your styles, code with grit. No compilers, no configs—just cowboy CSS magic."

## Lisence:

MIT License — Free to use, modify, and ride into the sunset.
