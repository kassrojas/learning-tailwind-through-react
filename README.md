# TailwindCSS Learning App

A React application designed to help users learn TailwindCSS by providing interactive, real-time previews of TailwindCSS classes. This app supports both light and dark modes, is fully responsive for mobile and desktop use, and includes translation capabilities to cater to a diverse user base.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Plan](#project-plan)
- [Acceptance Criteria](#acceptance-criteria)
- [Resources](#resources)

## Project Overview

The **TailwindCSS Learning App** aims to provide an interactive platform where users can learn and experiment with TailwindCSS classes. Similar to the MDN documentation, the app will display TailwindCSS properties categorized into tabs. Users can click on various class buttons to see their effects in real-time within a preview window. Additionally, the app will support content translation and offer both light and dark themes to enhance user experience.

## Features

- **Interactive TailwindCSS Playground:** Real-time preview of TailwindCSS classes applied to sample code.
- **Categorized Documentation:** Tabs for different TailwindCSS properties (e.g., Font Family, Colors, Spacing).
- **Class Buttons:** Clickable buttons representing TailwindCSS classes to apply and see changes instantly.
- **Light and Dark Mode:** Toggle between light and dark themes using TailwindCSS and TailwindUI.
- **Responsive Design:** Fully functional on both mobile and desktop devices.
- **Content Translation:** Translate app content into different languages using a free translation API.
- **User Preferences:** Save user preferences (e.g., theme, selected classes) using a free database solution.

## Tech Stack

- **Frontend:**
  - [React](https://reactjs.org/) with [TypeScript](https://www.typescriptlang.org/)
  - [TailwindCSS](https://tailwindcss.com/) for styling
  - [TailwindUI](https://tailwindui.com/) components (optional)
- **Backend:**
  - [Firebase](https://firebase.google.com/) or [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for the free database
- **APIs:**
  - [LibreTranslate](https://libretranslate.com/) or similar for translation
- **Hosting:**
  - [GitHub Pages](https://pages.github.com/) or [Vercel](https://vercel.com/) for deployment
- **Version Control:**
  - [GitHub](https://github.com/) for repository hosting

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- [Git](https://git-scm.com/) installed
- A GitHub account

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/tailwindcss-learning-app.git
   cd tailwindcss-learning-app
   ```

2. Create a `.env` file in the root directory and add necessary API keys (e.g., translation API).
3. `npm install` dependencies
4. `npm start` to run application
