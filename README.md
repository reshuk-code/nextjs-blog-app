# Next.js Blog Application

This is a simple blog application built with Next.js, demonstrating static site generation (SSG) and dynamic routing.

## Features

- List of blog posts.
- Individual blog post pages.
- Markdown support for blog content.

## Technologies Used

- **Framework**: Next.js
- **Styling**: CSS Modules
- **Content**: Markdown

## Setup and Installation

### Prerequisites

- Node.js (LTS version recommended)

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/nextjs-blog-app.git
    cd nextjs-blog-app
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Run the development server:
    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
nextjs-blog-app/
├── components/
│   ├── Layout.js
│   └── Date.js
├── pages/
│   ├── _app.js
│   ├── index.js
│   └── posts/
│       └── [id].js
├── lib/
│   └── posts.js
├── public/
│   └── favicon.ico
├── styles/
│   ├── globals.css
│   └── utils.module.css
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```


*Last automated update: 2026-06-17 03:16:53*

*Last automated update: 2026-06-17 03:17:07*