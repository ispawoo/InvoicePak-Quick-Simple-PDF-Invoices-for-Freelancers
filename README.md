# InvoicePak-Quick-Simple-PDF-Invoices-for-Freelancers

This is a Next.js application that allows freelancers and small businesses to easily create and download professional PDF invoices. It's built with Next.js, React, ShadCN UI, and Tailwind CSS.

## Features

-   **Simple Interface:** A clean and intuitive form for creating invoices quickly.
-   **Live Preview:** See how your invoice looks in real-time as you type.
-   **PDF Generation:** Download professional-looking invoices as PDF files.
-   **Client-Side Storage:** Your invoice data is automatically saved in your browser, so you can pick up where you left off.
-   **Templates:** Start with pre-built templates for common services to speed up your workflow.
-   **Customizable:** Easily add your own branding and details.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You'll need to have [Node.js](https://nodejs.org/en/) (version 18 or later) and npm installed on your computer.

### Installation

1.  **Clone the repository (or download the source code):**
    If you have git installed, you can clone the repository. Otherwise, download the code as a ZIP file and extract it.

2.  **Install dependencies:**
    Navigate to the project directory in your terminal and run the following command to install the necessary packages:
    ```bash
    npm install
    ```

3.  **Run the development server:**
    Once the installation is complete, start the development server:
    ```bash
    npm run dev
    ```

4.  **Open the app:**
    Open [http://localhost:9002](http://localhost:9002) with your browser to see the result. You can now start editing the page, and the changes will be reflected live.

## How to Upload to GitHub

You can publish your project to GitHub to keep a version history and collaborate with others.

### Option 1: Using the GitHub CLI

If you have the [GitHub CLI](https://cli.github.com/) installed, you can follow these steps:

1.  **Initialize a new Git repository:**
    ```bash
    git init -b main
    ```

2.  **Add all files to staging:**
    ```bash
    git add .
    ```

3.  **Commit your changes:**
    ```bash
    git commit -m "Initial commit"
    ```

4.  **Create a new repository on GitHub and push your code:**
    Replace `<repository-name>` with your desired repository name.
    ```bash
    gh repo create <repository-name> --public --source=. --remote=origin --push
    ```

### Option 2: Using the GitHub Website

If you prefer to use the GitHub website:

1.  **Initialize a new Git repository:**
    ```bash
    git init -b main
    ```

2.  **Add all files to staging:**
    ```bash
    git add .
    ```

3.  **Commit your changes:**
    ```bash
    git commit -m "Initial commit"
    ```

4.  **Create a new repository on GitHub:**
    -   Go to [github.com/new](https://github.com/new).
    -   Give your repository a name and an optional description.
    -   Choose whether the repository should be public or private.
    -   Click "Create repository".

5.  **Push your local repository to GitHub:**
    Follow the instructions under "...or push an existing repository from the command line" on your new GitHub repository page. It will look something like this:
    ```bash
    git remote add origin https://github.com/ispawoo/InvoicePak-Quick-Simple-PDF-Invoices-for-Freelancers.git
    git push -u origin main
    ```

Your code is now on GitHub!
