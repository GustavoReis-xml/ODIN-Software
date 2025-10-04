# CodeGators-Software

This repository contains a full-stack web application, structured as a monorepo.

## Project Structure

The project is organized into the following directories:

-   `/packages/client`: The frontend application.
-   `/packages/server`: The backend application.
-   `/database`: Contains database-related files, such as diagrams and scripts.

## Getting Started

### Prerequisites

-   [Node.js](https://nodejs.org/) (v16 or later recommended)
-   [npm](https://www.npmjs.com/) (v8 or later recommended)

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2.  Navigate to the project's root directory:
    ```bash
    cd codegators-software
    ```
3.  Install all dependencies for both the client and server using the root `package.json`:
    ```bash
    npm install
    ```
    This command uses npm workspaces to install dependencies for all packages in the `packages/` directory.

### Running the Application

To start both the client and server for development, run the following command from the root directory:

```bash
npm run dev
```

This will start the frontend and backend applications concurrently.