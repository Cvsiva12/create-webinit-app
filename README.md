🚧 create-webinit-app is Currently Under Development 🚧
--------------------------------------------------

# Create WebInit App 🚀

[![NPM version](https://img.shields.io/npm/v/create-webinit-app?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/create-webinit-app)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Powered by Next.js](https://img.shields.io/badge/Next.js-Template-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org)
[![Styled with Mantine UI](https://img.shields.io/badge/Mantine_UI-Template-339AF0?style=for-the-badge&logo=mantine&logoColor=white)](https://mantine.dev)

**`create-webinit-app` is a command-line interface (CLI) tool to quickly scaffold a new web project using the [WebInit Next.js & Mantine Starter Template](https://github.com/dev-onyx/webinit).**

It streamlines the setup process by cloning the template, customizing essential project files with your chosen project name, installing dependencies, initializing a fresh Git repository, and starting the development server for you.

---

## ✨ Features

* **Quick Scaffolding:** Creates a new project from the WebInit template in seconds.
* **Project Customization:** Automatically updates and setting up the project for you.
* **Dependency Installation:** Runs `npm install` to get all necessary packages.
* **Git Initialization:** Initializes a new local Git repository with an initial commit for your project.
* **Development Server:** Automatically starts the Next.js development server (`npm run dev`) after setup.
* **Interactive & Argument-based:** Use it interactively or provide the project name directly as an argument.

---

## 🛠️ Prerequisites

Before you begin, ensure you have the following installed:

* [Node.js](https://nodejs.org/) (version 16.x or higher recommended)
* [npm](https://www.npmjs.com/) (version 7.x or higher recommended) or [yarn](https://yarnpkg.com/)
* [Git](https://git-scm.com/)

---

## 🚀 Usage

The easiest way to use `create-webinit-app` is with `npx`, which ensures you're always using the latest version:

```bash
npx create-webinit-app [your-project-name]
```

**Examples:**

1. **Interactive Mode (Recommended for first-time use):**

    ```bash
    npx create-webinit-app
    ```

    The CLI will then prompt you for your project name.

2. **Direct Project Name:**

    ```bash
    npx create-webinit-app my-awesome-site
    ```

    This will create a new directory named `my-awesome-site` in your current location.

### Command-Line Options

You can view all available options using the help command:

```bash
npx create-webinit-app --help
```

---

## 📝 What Happens Next?

After running the command and providing a project name (if prompted):

1. The latest version of the [WebInit template](https://github.com/dev-onyx/webinit) is cloned into a new directory named after your project.
2. The template's original Git history and README.md are removed.
3. `package.json` is updated with your project's name, a default version (`0.1.0`), and a generated description. Template-specific metadata is removed.
4. A new, simple `README.md` is created for your project.
5. The placeholder title and welcome message in `src/pages/index.js` are updated with your project name.
6. Node.js dependencies are installed using `npm install`.
7. A new Git repository is initialized, and all files are committed.
8. The Next.js development server (`npm run dev`) is started, and your default browser is opened to `http://localhost:3000`.

You're then ready to start building your application!

---

## 🌍 The WebInit Template

This CLI tool uses the [**WebInit Next.js & Mantine Starter Template**](https://github.com/dev-onyx/webinit). This template provides a production-ready foundation with:

* Next.js 15.x (Pages Directory)
* React 19.x
* Mantine UI 8.x (with a custom ShadCN-inspired theme)
* Tailwind CSS 4.x
* Geist Fonts
* Lucide Icons
* ESLint, Prettier
* And much more!

For full details on the template's features and structure, please visit its [repository](https://github.com/dev-onyx/webinit).

---

## 🤝 Contributing to `create-webinit-app`

Contributions to improve `create-webinit-app` are welcome! Whether it's bug reports, feature suggestions, or code contributions:

1. **Fork** this repository (`github.com/dev-onyx/create-webinit-app`).
2. Create a new **branch** (`git checkout -b feature/your-amazing-feature`).
3. Make your changes.
4. **Commit** your changes (`git commit -m 'Add some amazing feature'`).
5. **Push** to the branch (`git push origin feature/your-amazing-feature`).
6. Open a **Pull Request**.

Please ensure your code adheres to the project's linting standards.

---

## 📄 License

`create-webinit-app` is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file in this repository for details.

---

<p align="center">
  Developed with ❤️ by <a href="https://github.com/dev-onyx" target="_blank">dev-onyx</a>
</p>