# Brainn Frontend Challenge

This repository contains the code for the Brainn Frontend Challenge, a web application that displays lottery results. The goal is to build a simple, responsive, and fun application using modern web technologies.

## Getting Started

This project is built with [Next.js](https://nextjs.org/), bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

Install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

### Running the Development Server

Start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

### Features

- **Lottery Types**: Supports 6 lottery types - Mega-sena, Quina, Lotofácil, Lotomania, Timemania, and Dia de sorte.
- **Dynamic Theme**: Changes theme, draw number, draw date, and drawn numbers based on the selected lottery type.
- **Responsive Design**: Ensures a good experience on mobile devices as per the provided layout.
- **API Integration**: Fetches lottery data from the provided API via REST or GraphQL.

### Technologies Used

- **React** with **TypeScript**
- **Next.js**
- **Tailwind CSS**
- **GraphQL**
- **React Hook Form** and **Zod**
- **React Testing Library** and/or **Cypress** for testing

### Resources

- **Layout**: [Figma Design](https://www.figma.com/file/H2qrYBCFMf4didYmxRwTxP/Brainn-Frontend-Challenge)
- **API**: [Brainn API](https://brainn-api-loterias.herokuapp.com)
- **Typography**: Montserrat (webfont)
