# CMD Portfolio

This repository contains the code for Chirag's CMD-style portfolio web application. The portfolio offers a terminal-like interface with various commands for an interactive experience.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Available Commands](#available-commands)
- [About](#about)
- [License](#license)

## Introduction

The CMD Portfolio is a React and Next.js project that replicates a command-line interface, providing an engaging way to showcase information and navigate through various commands.

## Project Structure

- **components:** React components for different parts of the portfolio.
  - `input.tsx`: Manages user input and command execution.
  - `ps1.tsx`: Displays the prompt and CMD style.
  - `history.tsx`: Renders the command history.
- **pages:** Main pages of the portfolio.
  - `index.tsx`: Home page with the terminal interface.
  - `404.tsx`: Redirects to the home page for invalid URLs.
- **styles:** Global CSS styles and Tailwind CSS configuration.
- **utils:** Utility functions for command execution and tab completion.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/chirag640/cmd-portfolio.git
    cd cmd-portfolio
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Run the development server:

    ```bash
    npm run dev
    ```

Visit [http://localhost:3000](http://localhost:3000) to explore the CMD Portfolio.

## Available Commands

- `help`: Display a list of available commands.
- `projects`: Display a list of GitHub projects.
- `quote`: Get a random quote.
- `weather [city]`: Get the weather for a specific city (API call).

## About

Designed and developed by Chirag Chaudhary. Visit [Chirag's GitHub repository](https://github.com/chirag640) for more information.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
