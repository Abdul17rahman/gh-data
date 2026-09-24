# gh-data

A Vite-based front-end project used to explore and work with **GitHub Actions Jobs, Data, and Artifacts**.

Repository: https://github.com/Abdul17rahman/gh-data

## About

`gh-data` is a practice project focused on GitHub Actions — specifically working with job data and build artifacts within CI workflows. The app itself is a small Vite front-end, containerized with Docker, and wired up with a GitHub Actions workflow (`.github/workflows/`) to demonstrate CI automation.

## Tech Stack

- **Build Tool:** [Vite](https://vitejs.dev/)
- **Language:** JavaScript
- **Linting:** ESLint (`.eslintrc.json`)
- **Containerization:** Docker & Docker Compose
- **CI/CD:** GitHub Actions

## Project Structure

```
gh-data/
├── .github/workflows/     # GitHub Actions workflow definitions
├── public/                # Static public assets
├── src/                   # Application source code
├── .eslintrc.json         # ESLint configuration
├── .gitignore
├── Dockerfile              # Container build definition
├── docker-compose.yml      # Multi-container orchestration
├── index.html              # App entry HTML
├── package.json            # Project dependencies & scripts
├── package-lock.json
└── vite.config.js          # Vite build configuration
```

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended) and npm
- [Docker](https://www.docker.com/) (optional, for containerized runs)

## Setup & Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Abdul17rahman/gh-data.git
   cd gh-data
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the development server**

   ```bash
   npm run dev
   ```

   Vite will start a local dev server (by default at `http://localhost:5173`).

4. **Build for production**
   ```bash
   npm run build
   ```

### Running with Docker

```bash
docker compose up --build
```

## GitHub Actions

This repository's core purpose is experimenting with GitHub Actions workflows — check `.github/workflows/` for the defined jobs, and the repository's **Actions** tab to see workflow runs, job data, and generated artifacts.

## Notes

This is a hands-on practice repository for learning CI/CD concepts with GitHub Actions (jobs, artifacts, and workflow data) rather than a production application.

## License

No license specified. Contact the repository owner ([Abdul17rahman](https://github.com/Abdul17rahman)) for usage permissions.
