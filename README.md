# Evergreen-Banking

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Overview

Evergreen-Banking is a modern, fully responsive front-end website developed for a fictional banking institution. It features a sleek, professional user interface designed to provide an immersive and intuitive experience, adapting seamlessly across various devices and screen sizes. The project showcases best practices in web design for a client-side rendered application.

## System Architecture

The project adheres to a straightforward client-side architecture, leveraging standard web technologies to deliver a static, interactive experience.

*   **`index.html`**: This file serves as the primary entry point for the website. It defines the structural content of the banking platform and links to external resources for styling and interactivity.
*   **`assets/`**: This directory is designated for static resources critical to the website's presentation and functionality. It typically contains:
    *   **CSS files**: For defining the visual styles, layout, and responsive behavior of the website.
    *   **JavaScript files**: For implementing client-side interactivity, dynamic content updates, and user experience enhancements.
    *   **Image files**: Graphics, icons, and other visual media used throughout the site.
*   The interaction model is entirely client-side, meaning all rendering and logic occur within the user's web browser, without requiring a back-end server for core functionality.

## Prerequisites

To view and interact with the Evergreen-Banking website, the following are required:

*   **Web Browser**: A modern web browser (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge, Apple Safari) is necessary to render the HTML, CSS, and execute JavaScript.
*   **Git**: For cloning the repository.

For local development and serving the project:

*   **Code Editor**: A text editor or Integrated Development Environment (IDE) such as Visual Studio Code is recommended for modifying the source code.
*   **Node.js & npm (Optional)**: If you wish to use a local HTTP server like `http-server` for development purposes.

## Installation

To get a local copy of the project up and running, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/MuhammedFaazCC/Evergreen-Banking.git
    ```
2.  **Navigate into the project directory**:
    ```bash
    cd Evergreen-Banking
    ```

## Usage

### Viewing the Website

To access the Evergreen-Banking website, simply open the `index.html` file in your preferred web browser.

1.  Navigate to the `Evergreen-Banking` directory.
2.  Double-click on `index.html` or open it via your browser's file menu.

### Local Development Server (Recommended)

For a more robust development experience, especially when dealing with relative paths or certain browser security policies, it is recommended to serve the project using a local HTTP server.

#### Using `http-server` (Node.js required)

1.  **Install `http-server` globally** (if you haven't already):
    ```bash
    npm install -g http-server
    ```
2.  **Start the server** from the project root directory:
    ```bash
    http-server .
    ```
3.  Open your web browser and navigate to the address provided by `http-server` (typically `http://localhost:8080`).

#### Using VS Code Live Server Extension

1.  Install the "Live Server" extension by Ritwick Dey from the Visual Studio Code Marketplace.
2.  Open the `Evergreen-Banking` project folder in VS Code.
3.  Right-click on `index.html` in the Explorer panel.
4.  Select "Open with Live Server". This will launch the site in your default browser and automatically reload on file changes.
