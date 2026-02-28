# matthewgyang.com

Personal portfolio website for Matthew Yang — Backend Software Engineer.

Built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com). Hosted on AWS (S3 + CloudFront).

## Tech Stack

- **Framework:** Astro v5 (static site generation)
- **Styling:** Tailwind CSS v4
- **Fonts:** Space Grotesk, Inter, JetBrains Mono (Google Fonts)
- **Contact Form:** Formspree
- **Hosting:** AWS S3 + CloudFront + Route 53

## Local Development

```sh
npm install
npm run dev
```

The dev server runs at `http://localhost:4321`.

## Build

```sh
npm run build
```

Static output is generated in `./dist/`.

## Project Structure

```
src/
  components/
    Navbar.astro       # Sticky nav with mobile menu
    Hero.astro         # Animated hero section
    About.astro        # Bio and career summary
    Skills.astro       # Technology grid
    Experience.astro   # Work history timeline
    Education.astro    # Education details
    Contact.astro      # Contact form + social links
    Footer.astro       # Footer with social icons
  layouts/
    Layout.astro       # Base HTML layout
  pages/
    index.astro        # Main page (assembles all sections)
  styles/
    global.css         # Tailwind config + custom animations
public/
  favicon.svg          # Site favicon
```
