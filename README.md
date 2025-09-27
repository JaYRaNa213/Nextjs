


### NextJS website template :
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
│   ├── app/
│   │   ├── (admin)/
│   │   │   ├── dashboard/
│   │   │   │   └── page.tsx
│   │   │   ├── manages-blogs/
│   │   │   │   └── page.tsx
│   │   │   └── users/
│   │   │       └── page.tsx
│   │   ├── (pages)/
│   │   │   ├── about-us/
│   │   │   │   └── page.tsx
│   │   │   ├── astrology/
│   │   │   │   └── page.tsx
│   │   │   ├── blogs/
│   │   │   │   └── page.tsx
│   │   │   ├── braj-yatra/
│   │   │   │   └── page.tsx
│   │   │   ├── brajshop/
│   │   │   │   └── page.tsx
│   │   │   ├── horoscope/
│   │   │   │   └── page.tsx
│   │   │   ├── pandits/
│   │   │   │   └── [panditSlug]/
│   │   │   └── services/
│   │   │       ├── e-puja/
│   │   │       │   ├── EPujaServices.tsx
│   │   │       │   ├── loading.tsx
│   │   │       │   ├── page.tsx
│   │   │       │   └── [pujaSlug]/
│   │   │       │       ├── ClientComponents.tsx
│   │   │       │       ├── CTASection.tsx
│   │   │       │       ├── page.tsx
│   │   │       │       └── TempleDetails.tsx
│   │   │       I
│   │   │       ├── HeroSection.tsx
│   │   │       ├── page.tsx
│   │   │       ├── PoojaCard.tsx
│   │   │       ├── puja/
│   │   │       │   ├── page.tsx
│   │   │       │   └── [pujaSlug]/
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
