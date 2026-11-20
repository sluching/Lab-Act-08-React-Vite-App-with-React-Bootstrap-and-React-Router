# Portfolio Website (Lab Act 08)

A multi-page personal portfolio built with **React + Vite + TypeScript**,
**React-Bootstrap** and **React-Router (Data Mode)**.

## Run it

```bash
npm install
npm run dev      # then open the address shown in the terminal
```

Other commands: `npm run build` (type-check + production build) and
`npm run preview` (serve the built site).

## Make it yours

1. Edit **`src/profile.ts`**: name, tagline, resume, skills, contact info,
   projects. Every page reads from this one file. Search for `TODO`.
2. Put your photo in the **`public/`** folder (for example `profile.jpg`) and
   change `photo` in `src/profile.ts` to `'/profile.jpg'`.

## Project structure

```
src/
  main.tsx                   Router setup (createBrowserRouter + RouterProvider)
  App.tsx                    Shared layout: NavigationBar + <Outlet /> + footer
  profile.ts                 All the personal content
  index.css                  A few custom styles on top of Bootstrap
  components/
    NavigationBar.tsx        The single Navbar that links every page
  pages/
    Home.tsx                 Photo + short introduction
    About.tsx                Resume (Accordion, ProgressBar, ListGroup, Badge)
    Projects.tsx             Responsive grid of project Cards
    Contact.tsx              Public contact info + message Form
    NotFound.tsx             404 page for unknown addresses
```

## How the rubric is covered

| Criteria | What this project has |
| --- | --- |
| Pages | 4 pages, each in its own `.tsx` file |
| React-Bootstrap components | Navbar, Nav, Container, Row, Col, Card, Button, Badge, Image, Stack, Accordion, ListGroup, ProgressBar, Form, Alert |
| Navigation | All 4 pages linked by the one `NavigationBar` component |
| Layout | Responsive grid (`Row`/`Col` breakpoints), collapsing mobile menu, consistent spacing and colours |

## Submitting

Zip the project folder **without** `node_modules`, and attach a screenshot of
the Home page.
