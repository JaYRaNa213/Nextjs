# Nextjs
```
├── app/                             # App Router pages
│   ├── (main)/                     # Public-facing site
│   │   ├── page.tsx                # Home page
│   │   ├── layout.tsx              # Global layout
│   │   ├── globals.css             # Global styles
│   │   ├── about/page.tsx          # About page
│   │   ├── contact/page.tsx        # Contact page
│   │   ├── [slug]/page.tsx         # Dynamic route example
│   │   └── api/                     # API routes
│   │       ├── users/route.ts      # User APIs
│   │       ├── products/route.ts   # Product APIs
│   │       └── services/           # Service APIs
│   │           ├── route.ts
│   │           └── [serviceSlug]/route.ts
├── components/                      # Reusable UI & layout components
│   ├── common/                      # Generic UI elements
│   │   ├── Button.tsx
│   │   ├── Modal.tsx
│   │   ├── Navbar.tsx
│   │   ├── ThemeToggle.tsx
│   │   └── index.ts
│   ├── layout/                      # Layout-specific components
│   │   ├── Header.tsx
│   │   ├── Footer.tsx
│   │   ├── Hero.tsx                 # Home hero section
│   │   ├── Testimonials.tsx
│   │   └── index.ts
│   ├── ui/                          # UI helpers
│   │   ├── Card.tsx
│   │   ├── Badge.tsx
│   │   └── index.ts
├── constants/                       # Static JSON & config
│   ├── siteConfig.json              # Site-wide settings
│   ├── routes.json                  # Route definitions
│   ├── data/                        # Example data sets
│   │   └── sampleData.json
├── context/                         # Global state providers
│   ├── AuthContext.tsx
│   ├── ThemeContext.tsx
│   └── CartContext.tsx
├── hooks/                           # Custom React hooks
│   ├── useTranslation.ts
│   ├── useAuth.ts
│   └── useFetch.ts
├── lib/                             # Libraries/utilities
│   ├── i18n.ts
│   └── apiClient.ts
├── locales/                         # Translations
│   ├── en.json
│   └── hi.json
├── providers/                       # Context & theme providers
│   ├── RootProvider.tsx
│   ├── StoreProvider.tsx
│   └── ThemeProvider.tsx
├── services/                        # Business logic & API calls
│   ├── bookingService.ts
│   ├── productService.ts
│   └── userService.ts
├── store/                           # State management
│   ├── features/
│   │   └── appSlice.ts
│   ├── hooks.ts
│   └── store.ts
├── styles/                          # CSS / Tailwind
│   ├── globals.css
│   └── animations.css
├── types/                           # TypeScript types
│   ├── index.d.ts
│   ├── product.ts
│   ├── service.ts
│   └── user.ts
├── utils/                           # Utility functions
│   ├── formatters.ts
│   └── helpers.ts
├── public/                          # Static assets
│   ├── images/                      # Images only
│   ├── icons/                       # Icons only
│   └── fonts/                       # Fonts only
├── tailwind.config.ts               # Tailwind config
├── tsconfig.json                     # TypeScript config
├── package.json                      # Project dependencies
└── README.md                         # Project overview
```


### new structure 

```
my-nextjs-template/
│
├── public/
│   ├── assets/
│   │   ├── images/
│   │   ├── icons/
│   │   ├── fonts/
│   │   └── logos/
│   ├── favicon.ico
│   └── robots.txt
│
├── src/
│   ├── app/                  # Next.js App Router (or use pages/ for Pages Router)
│   │   ├── [slug]/          # Dynamic route folder for slugs
│   │   │   └── page.tsx
│   │   ├── api/             # Server API routes
│   │   │   ├── example/
│   │   │   │   └── route.ts
│   │   │   └── index.ts
│   │   ├── layout.tsx       # Main App layout
│   │   ├── page.tsx         # Home Page
│   │   └── not-found.tsx
│   │
│   ├── components/          # All reusable components
│   │   ├── common/          # General-purpose UI components
│   │   │   ├── Button.tsx
│   │   │   ├── Modal.tsx
│   │   │   ├── Navbar.tsx
│   │   │   ├── Footer.tsx
│   │   │   └── ThemeToggle.tsx
│   │   │
│   │   ├── layout/          # Page or section layouts
│   │   │   ├── Header.tsx
│   │   │   ├── Footer.tsx
│   │   │   └── PageLayout.tsx
│   │   │
│   │   ├── ui/              # UI elements
│   │   │   ├── Card.tsx
│   │   │   ├── Badge.tsx
│   │   │   ├── Accordion.tsx
│   │   │   └── Loader.tsx
│   │   │
│   │   ├── forms/           # Form components
│   │   │   ├── Input.tsx
│   │   │   ├── Textarea.tsx
│   │   │   └── Select.tsx
│   │   │
│   │   └── sections/        # Sections of a page
│   │       ├── HeroSection.tsx
│   │       ├── AboutSection.tsx
│   │       └── ContactSection.tsx
│   │
│   ├── constants/           # Static constants & config
│   │   ├── routes.ts
│   │   ├── siteConfig.ts
│   │   └── placeholders.json
│   │
│   ├── context/             # React contexts
│   │   ├── AuthContext.tsx
│   │   ├── ThemeContext.tsx
│   │   └── AppContext.tsx
│   │
│   ├── hooks/               # Custom hooks
│   │   ├── useAuth.ts
│   │   ├── useFetch.ts
│   │   └── useTranslation.ts
│   │
│   ├── lib/                 # Utility libraries
│   │   ├── apiClient.ts
│   │   ├── i18n.ts
│   │   └── utils.ts
│   │
│   ├── locales/             # Localization files
│   │   ├── en.json
│   │   └── hi.json
│   │
│   ├── providers/           # Context providers
│   │   ├── AuthProvider.tsx
│   │   ├── ThemeProvider.tsx
│   │   └── AppProvider.tsx
│   │
│   ├── services/            # API services
│   │   ├── authService.ts
│   │   ├── userService.ts
│   │   ├── productService.ts
│   │   └── settingsService.ts
│   │
│   ├── store/               # Redux / Zustand store
│   │   ├── store.ts
│   │   └── hooks.ts
│   │
│   ├── styles/              # Global styles
│   │   ├── globals.css
│   │   └── tailwind.css
│   │
│   ├── types/               # TypeScript type definitions
│   │   ├── common.d.ts
│   │   ├── user.d.ts
│   │   └── product.d.ts
│   │
│   └── utils/               # Utility functions
│       ├── dateUtils.ts
│       ├── stringUtils.ts
│       └── numberUtils.ts
│
├── .env.local               # Environment variables
├── tailwind.config.ts
├── next.config.js
├── tsconfig.json
├── package.json
└── README.md
