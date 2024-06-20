# First 90 Days as Head of Architecture

![Gremlins Inc](/content/images/logo.png)

This repository contains a static site created with Hugo, designed to store and present information around a 90-day plan for a Head of Architecture role, using the fictitious company Gremlins Inc, along with some extras in the appendix. The site is built using the Hugo static site generator with the Learn theme and is hosted on GitHub Pages using a custom GitHub Action.

## Table of Contents

- [About the Site](#about-the-site)
- [Installation](#installation)
- [Running Hugo Locally](#running-hugo-locally)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## About the Site

The site contains:

- A comprehensive 90-day plan for a Head of Architecture role.
- Key aspects of software architecture.
- Measuring the effectiveness of an architecture team
- Leveraging Diagrams as Code to prevent stale documentation

The site is structured to provide valuable insights and guidance for a new Head of Architecture at Gremlins Inc.

## Installation

To install and run the site locally, you need to have Hugo installed on your machine. Follow the steps below to install Hugo and get started.

### Install Hugo

1. **Download and Install Hugo:**
   - Visit the [Hugo Releases page](https://github.com/gohugoio/hugo/releases) and download the latest version of Hugo for your operating system.
   - Follow the instructions to install Hugo on your system.

2. **Verify Installation:**
   ```sh
   hugo version

   Ensure that Hugo is installed correctly by running the above command. You should see the installed version of Hugo.

### Running Hugo Locally
1. **Clone the Repo:**
   ```sh
   git clone https://github.com/your-username/head-of-architecture-interview-guide.git
   cd head-of-architecture-interview-guide
   ```

2. **Start the Hugo Server** 
   ```sh
   hugo server -D
   ```
   The -D flag includes content marked as draft. Open your browser and navigate to http://localhost:1313 to see the site in action.

## Deployment

The site is automatically deployed to GitHub Pages using a custom GitHub Action. The action is configured to build the site and push the generated content to the `gh-pages` branch.

## Contributing

We welcome contributions to enhance the content and functionality of the site. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with a descriptive message.
4. Push your changes to your fork.
5. Open a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

