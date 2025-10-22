# Fullstack Developer Portfolio
A minimal, easy-to-customize developer portfolio template built with [Astro](https://astro.build/) and [TailwindCSS](https://tailwindcss.com/). No JavaScript in final build.

## Demo
Check out a real-world example: [devidev.io](https://devidev.io)

![Astro Developer Portfolio Template - About Preview | devi|dev|io](assets/preview-about.png)

![Astro Developer Portfolio Template - Projects Preview | devi|dev|io](assets/preview-projects.png)

## Features
- **Full-Stack Web Development** – working in both, front-end and back-end using HTML, CSS, JavaScript, Node.js, and Express.js.  
- **UX/UI-Driven Design** – intuitive layouts and seamless user flows focused on usability, engagement, and conversion.  
- **Marketing & META Integrations** – advanced setups with Facebook Pixel, Conversion API, and Analytics to track and optimize performance.  
- **Conversion-Focused Websites** – every project built to maximize ROI through speed, structure, and user experience.  
- **SEO & Performance Optimization** – clean code, structured data, and fast-loading pages designed for top search rankings.  
- **Responsive & Mobile-First Design** – websites that adapt beautifully across all devices and screen sizes.  
- **Scalable Architecture (MVC)** – organized, maintainable, and ready to grow with your business needs.  
- **Business-Oriented Approach** – bridging code and strategy to help brands increase visibility, traffic, and sales.  
- **Modern Aesthetics** – sleek, professional visuals with a focus on brand identity and conversion psychology.  
- **Portfolio & Project Highlights** – real-world examples showcasing impactful, data-driven web solutions.


## Tech Stack
- [Astro](https://astro.build/)
- [TailwindCSS](https://tailwindcss.com/)
- [Shiki](https://github.com/shikijs/shiki)

## Getting Started

```sh
# 1. Clone the repository
git clone https://github.com/devidevio/astro-developer-portfolio .

# 2. Install dependencies
npm install

# 3. Run the development server
npm run dev

# 4. Build for production
npm run build

# Deploy the contents of the `./dist` folder wherever you like.
```

## Customization
### Site & Domain Configuration
- Modify `astro.config.mjs` to update your `site` settings, including metadata for SEO.

### Theme Customization
- Adjust the primary theme color in `tailwind.config.js`, to fit your branding.

### Updating Content & SEO
Edit the **Frontmatter** variables in these files:
- `src/layouts/Layout.astro` – General page info (title, SEO, etc.)
- `src/components/Socials.astro` – Update your social media links.
- `src/components/Profile.astro` – Personal profile information.
- `src/components/ContentProjects.astro` – Projects/portfolio section content.
- `src/components/ContentAbout.astro` – About section content.

### Profile Picture
- Replace `/src/assets/profile.png` with your own image.

### Logo & OpenGraph Image
- Update these files:
  - `/public/img/logo.svg` (your logo)
  - `/public/img/meta.png` (your OpenGraph image)

Need a free OpenGraph image?
- https://tailwind-generator.com/og-image-generator/generator

### Sitemap & Robots.txt
- Adjust `/public/robots.txt` to match your domain.

## ⭐ Contributing
Feel free to fork, customize, and contribute to this project. If you find it useful, leaving a star would be greatly appreciated.
