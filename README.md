## ✨ Features

-   🎯 **Dynamic Percentage Visualization**: Input custom values and see them instantly converted into clear, understandable percentages.
-   📊 **Interactive Data Input**: Easily add, update, and manage the data points you want to visualize.
-   📱 **Responsive User Interface**: Enjoy a seamless experience across all devices, from desktops to mobile phones.
-   ✨ **Modern & Clean Design**: A user-friendly interface powered by Tailwind CSS for an aesthetic and efficient experience.
-   ⚡ **Fast and Efficient**: Using Next.js for optimal performance and a smooth user experience.
 
## 🖥️ Screenshots

<img width="1887" height="1036" alt="image" src="https://github.com/user-attachments/assets/e09d7a49-af13-43aa-baf1-02e614d1c7f3" />

<img width="1887" height="1025" alt="image" src="https://github.com/user-attachments/assets/cff7eba3-364e-4da5-be50-bd9e3bb941e6" />


## 🛠️ Tech Stack

**Frontend:**

[![Next.js](https://img.shields.io/badge/Next.js-Black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

[![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)](https://eslint.org/)

**Backend:**

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)

**DevOps:**

[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

## 🚀 Quick Start

Follow these steps to get a development environment up and running on your local machine.

### Prerequisites

Before you begin, ensure you have the following installed:
-   **Node.js**: `^18.17.0` or higher (LTS recommended)
-   **npm**: Comes with Node.js

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/is4r0/life-in-percentages.git
    cd life-in-percentages
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Environment setup**
    This project might use environment variables for various configurations (e.g., API keys, analytics IDs).
    ```bash
    cp .env.example .env # If a .env.example file is present
    ```
    If `.env.example` is not present, you might need to create a `.env.local` file manually if there are any specific local configurations required by Next.js or other tools.

    <!-- TODO: List detected environment variables if an .env.example is provided. -->
    ```
    # Example .env.local content (adjust as needed)
    # NEXT_PUBLIC_ANALYTICS_ID=YOUR_ANALYTICS_ID
    ```

4.  **Start development server**
    ```bash
    npm run dev
    ```

5.  **Open your browser**
    Visit `http://localhost:3000` to see the application running.

## 📁 Project Structure

```
life-in-percentages/
├── public/                 # Static assets (images, fonts, etc.)
├── src/                    # Application source code
│   └── app/                # Next.js App Router root (or 'pages' for Pages Router)
│       └── ...             # Core application pages and components
├── .env.local              # Local environment variables (not committed)
├── eslint.config.mjs       # ESLint configuration
├── next.config.ts          # Next.js configuration
├── package.json            # Project dependencies and scripts
├── package-lock.json       # npm lock file
├── postcss.config.mjs      # PostCSS configuration (likely for Tailwind CSS)
├── tsconfig.json           # TypeScript configuration
├── AGENTS.md               # Additional documentation/notes
└── CLAUDE.md               # Additional documentation/notes
```

---

<div align="center">

**⭐ Star this repo if you find it helpful or interesting!**

Made with ❤️ by [is4r0](https://github.com/is4r0)

</div>
