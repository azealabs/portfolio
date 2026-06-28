# AZea Labs Portfolio

Official portfolio website for **AZea Labs**, a software development and QA automation ecosystem created by Antonio Zea.

The goal of this project is to serve as the main public hub for AZea Labs, including professional information, projects, QA Labs, future academy content, and technical learning resources.

## Live Website

```text
https://azealabs.com
https://www.azealabs.com
```

## Project Status

Current status:

```text
Portfolio MVP - In progress
```

The first public landing page is already deployed and available through Cloudflare Pages.

## Tech Stack

This project uses:

* Astro
* TypeScript
* Tailwind CSS
* Cloudflare Pages
* GitHub

## Main Goals

The AZea Labs portfolio is intended to:

* Present the AZea Labs ecosystem
* Showcase software and QA automation projects
* Introduce QA Labs as a future automation practice platform
* Introduce QA Academy as a future educational product
* Serve as a professional portfolio for Antonio Zea
* Document the evolution of the ecosystem over time

## Project Structure

```text
/
├── public/
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── README.md
```

## Local Development

Install dependencies:

```sh
npm install
```

Start the local development server:

```sh
npm run dev
```

The site will be available at:

```text
http://localhost:4321
```

## Build

Create a production build:

```sh
npm run build
```

Preview the production build locally:

```sh
npm run preview
```

## Deployment

This project is deployed with **Cloudflare Pages**.

Production branch:

```text
main
```

Build command:

```sh
npm run build
```

Build output directory:

```text
dist
```

Every push to the `main` branch triggers a new deployment.

## Roadmap

Planned improvements:

* Add a complete portfolio README
* Add favicon
* Add Open Graph metadata
* Add social preview image
* Add 404 page
* Add project detail pages
* Add LinkedIn link
* Improve responsive testing
* Prepare QA Labs planning content
* Connect future subdomains:

  * `labs.azealabs.com`
  * `academy.azealabs.com`
  * `api.azealabs.com`

## Related Repositories

Planned ecosystem repositories:

```text
azealabs-docs
portfolio
qalabs-web
qalabs-api
automation-examples
qa-academy
```

## License

This project is currently private/internal for AZea Labs development and learning purposes.
