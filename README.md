# alx-project-0x03-setup

## Splash App – Shared Layout and Routing in Next.js
- This project demonstrates how to implement shared layouts, modular components, custom fonts, and imperative routing in a modern Next.js application using TypeScript, Tailwind CSS, and React Icons. The goal is to apply best practices such as the DRY (Don't Repeat Yourself) principle, clean component design, and reusable layouts, while building a functional foundation for a multi-featured AI platform.

## Learning Objectives
By completing this project, you will:
  * Implement shared layouts with reusable Header and Footer components
  * Apply the DRY principle using layout wrappers
  * Style UI components using Tailwind CSS
  * Build responsive and styled components (Button, Layout, Header, Footer)
  * Use imperative routing with useRouter in Next.js
  * Import and apply custom Google fonts globally
  * Handle 404 errors with a custom error page
  * Structure interfaces in a centralized location
  * Maintain a clean, scalable file structure

## Requirements
Node.js v16 or later
npm or yarn
Basic understanding of React, TypeScript, and CSS
Familiarity with Next.js Pages Router
VS Code or other modern code editor
Git and GitHub

## Project Structure
alx-project-0x03/ 
├── components/ │ ├── common/ │ │ └── Button.tsx │ 
└── layouts/ │ ├── Footer.tsx │ ├── Header.tsx │ 
└── Layout.tsx ├── interface/ │ 
└── index.ts ├── pages/ │ ├── 404.tsx │ 
└── index.tsx ├── public/ ├── styles/ │ 
└── global.css ├── .eslintrc.json ├── next.config.js ├── package.json ├── README.md
 └── tsconfig.json

## Tasks and Implementation Guide
*0. Implementing a Shared Layout*
 * ✅ Objective: 
   * Use a common layout wrapper for all pages.
 * ✅ Components:
   * Header.tsx – App branding + Sign In/Sign Up buttons
   * Footer.tsx – Social media icons + Useful links
   * Layout.tsx – Wraps pages in shared UI

Install:
npm install react-icons
