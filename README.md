# React Embedded Sandbox <a name="title"></a>

A lightweight, privacy-first front-end execution sandbox built in React for offline development, educational platforms, and technical documentation.

## Why This Exists? <a name="why-this-exists"></a>

Heavy cloud-based editors are bloated and often require persistent internet connections. We needed a lightweight, embeddable execution environment that doesn't track users, load heavy tracking scripts, or require a backend to function. This project is designed as an open-source front-end execution sandbox to be embedded into documentation sites, educational platforms, and local dev environments.

## Security & Limitations <a name="security-and-limitations"></a>

Executing user code directly in the browser is inherently dangerous. Due to the complexities of handling arbitrary HTML/CSS/JS, there are significant risks of XSS (Cross-Site Scripting) and iframe sandboxing escapes. We are actively threat-modeling the application for code-injection vulnerabilities. All pull requests must undergo strict security reviews to ensure we don't introduce XSS vulnerabilities or break iframe isolation.

## Use Cases <a name="use-cases"></a>

- **Educational Platforms**: Embedding safe coding environments for students.
- **Technical Documentation**: Interactive code snippets in Markdown documentation.
- **Offline Development**: Local testing without requiring an internet connection.

## 📝 Table of Contents

- [Title and Description](#title)
- [Why this exists?](#why-this-exists)
- [Security & Limitations](#security-and-limitations)
- [Use Cases](#use-cases)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Screenshots](#screenshots)
- [Features](#features)
- [Built with](#built-with)
- [License](#license)
- [Contributing](#contributing)
- [About Me](#about-me)

## 🏁 Getting Started <a name="getting-started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need node version `16.16.0` and npm version `8.11.0` or higher to lauch the project.

Refer to [NodeJs website](https://nodejs.org/en/download) for more instructions.

### Installing <a name="installation"></a>

Step by step process to get the project running on your local machine after the [prerequistes](#prerequistes) have been completed.

Open your command terminal in the root directory of the project.

Clone the project

```bash
  git clone https://github.com/Favourz1/react-embedded-sandbox.git
```

Go to the project directory

```bash
  cd react-embedded-sandbox
```

Installing dependencies

```
npm install
```

Starting local server

```
npm run dev
```

The development files are stored in the `./src/` folder.

## 🖥 Sceenshots <a name="screenshots"></a>

<p align="center">
  <a href="" rel="noopener">
 <img width=100% height=500px style="min-height: 200px" src="./public/live-demo.png" alt="Project demo"></a>
</p>

---

## ⛓ Features <a name="features"></a>

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Console terminal
- Cross platform
- Uses local Storage

## ⛏️ Built With <a name="built-with"></a>

- ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
- ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
- ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
- ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
- ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

## License <a name="license"></a>

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

## Contributing <a name="contributing"></a>

Contributions are always welcome!

See [contributing.md](./CONTRIBUTING.md) for ways to get started.

Please adhere to this project's code of conduct.

# Hi, I'm Favour Okoh! 👋 <a name="about-me"></a>

## 🚀 About Me

I'm a passionate and innovative Software Engineer with strong collaboration skills.

My portfolio on:

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/favour-okoh/)

Reach me on:

[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/_favourz)
