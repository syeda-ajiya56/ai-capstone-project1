# AI Capstone Project

A capstone repository for the **AI-Assisted Development** course. This project demonstrates how to build software with modern tools—Node.js, Git, GitHub, and Cursor IDE—while using AI responsibly as a development assistant.

---

## Project Overview

This repository is the home for my AI Capstone project. The goal is to practice professional software development workflows: version control, clean code, documentation, and thoughtful use of AI tools.

**What this project covers:**

- Setting up a Node.js development environment
- Using Git and GitHub for source control and collaboration
- Writing maintainable, well-documented code
- Applying AI-assisted development practices with human review and verification

**Tech stack:**

| Tool        | Purpose                                      |
| ----------- | -------------------------------------------- |
| Node.js     | JavaScript runtime for application logic     |
| Git         | Local version control                        |
| GitHub      | Remote repository hosting and collaboration  |
| Cursor IDE  | AI-assisted code editor                      |

---

## Prerequisites

Before you begin, make sure you have the following installed:

| Requirement   | Minimum Version | Download                                      |
| ------------- | --------------- | --------------------------------------------- |
| Node.js       | 18.x or later   | [nodejs.org](https://nodejs.org/)             |
| npm           | 9.x or later    | Included with Node.js                         |
| Git           | 2.x or later    | [git-scm.com](https://git-scm.com/)           |
| Cursor IDE    | Latest          | [cursor.com](https://cursor.com/)             |

**Optional but recommended:**

- A [GitHub](https://github.com/) account for cloning and contributing
- Basic familiarity with the command line (Terminal on macOS/Linux, PowerShell or Git Bash on Windows)

Verify your setup:

```bash
node --version
npm --version
git --version
```

---

## Installation

Follow these steps to get the project running on your machine.

### 1. Clone the repository

```bash
git clone https://github.com/syeda-ajiya56/ai-capstone-project1.git
cd ai-capstone-project1
```

### 2. Install dependencies

When a `package.json` file is added to the project, install dependencies with:

```bash
npm install
```

> **Note:** This project is in early setup. If `package.json` is not yet present, skip this step until dependencies are defined.

### 3. Open in Cursor

1. Launch **Cursor IDE**
2. Go to **File → Open Folder**
3. Select the `ai-capstone-project1` directory

---

## Project Structure

```
ai-capstone-project1/
├── .gitignore          # Files and folders excluded from Git
├── CLAUDE.md           # AI assistant guidelines for this repository
├── LICENSE             # MIT License
├── README.md           # Project documentation (this file)
├── package.json        # Node.js project metadata and dependencies (planned)
├── src/                # Application source code (planned)
│   └── index.js        # Main entry point (planned)
└── tests/              # Test files (planned)
```

| File / Folder   | Description                                                |
| --------------- | ---------------------------------------------------------- |
| `.gitignore`    | Keeps build artifacts, dependencies, and secrets out of Git |
| `CLAUDE.md`     | Conventions and rules for AI-assisted development          |
| `LICENSE`       | Open-source license (MIT)                                  |
| `README.md`     | Setup guide and project documentation                      |
| `src/`          | Where application code will live                           |
| `tests/`        | Where automated tests will live                            |

---

## Usage

### Running the project

Once the application entry point is added, you will typically start the project with:

```bash
npm start
```

For development with auto-reload (when configured):

```bash
npm run dev
```

> **Current status:** The project scaffold is in place. Application code and npm scripts will be added in upcoming milestones.

### Git workflow

Use Conventional Commits for clear, readable history:

```bash
# Stage changes
git add .

# Commit with a descriptive message
git commit -m "feat: add initial project structure"

# Push to GitHub
git push origin main
```

**Common commit prefixes:**

| Prefix     | Use when…                              |
| ---------- | -------------------------------------- |
| `feat:`    | Adding a new feature                   |
| `fix:`     | Fixing a bug                           |
| `docs:`    | Updating documentation                 |
| `refactor:`| Restructuring code without changing behavior |
| `test:`    | Adding or updating tests               |

### AI-assisted development

This project follows these AI usage guidelines (see `CLAUDE.md` for details):

1. Use AI to review and improve documentation and code
2. Always verify AI suggestions before accepting them
3. Keep the README and major changes documented before committing

---

## Future Improvements

Planned enhancements for upcoming milestones:

- [ ] Add `package.json` and define npm scripts (`start`, `dev`, `test`)
- [ ] Implement core application logic in `src/`
- [ ] Add unit and integration tests in `tests/`
- [ ] Set up linting and formatting (e.g., ESLint, Prettier)
- [ ] Add a `.env.example` file for environment variable documentation
- [ ] Configure CI/CD with GitHub Actions for automated testing
- [ ] Expand documentation with API references and contribution guidelines

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Author

**Syeda Ajiya** — AI-Assisted Development Capstone

---

### 📝 Project Note
* **Repository Setup:** Initial project setup and boilerplate commits were made using a shared environment / setup assistance.
* **Development:** All implementation, feature additions, and ongoing development for this project are done solely by **Syeda Ajiya** (`syeda-ajiya56`).

Repository: [github.com/syeda-ajiya56/ai-capstone-project1](https://github.com/syeda-ajiya56/ai-capstone-project1)
