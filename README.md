# AI Startup Website - Collaborative Git Project

## Project Overview

This project demonstrates a collaborative Git workflow for developing an AI startup website. It simulates the work of two developers (Tom and Jerry) contributing to the same project using Git and GitHub, following industry-standard version control practices.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Installation](#installation)
- [Workflow Documentation](#workflow-documentation)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This repository serves as a hands-on exercise for:
- Git version control fundamentals
- GitHub collaboration workflows
- Branching strategies
- Team development patterns
- DevOps best practices

The project simulates a real-world scenario where multiple developers work on different features of a website simultaneously.

## Features

- **Branch Management**: Demonstration of feature branching workflow
- **Collaboration**: Simulated team collaboration patterns
- **Version Control**: Proper Git commit history and messaging
- **CI/CD Foundation**: Setup for future continuous integration

## Installation

To set up this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/abrahamnosa23/ai-startup-website.git
   cd ai-startup-website
   ```
2. Install dependencies (non required for this basic project)
3. Open index.html in your preferred browser

## Workflow Documentation
Initial Setup
  1. Repository creation on GitHub
  
  2. Local repository cloning
  
  3. Initial commit with basic structure
  
**Tom's Workflow (Navigation Updates)**
  1. Created feature branch:
     ```bash
     git checkout -b update-navigation
     ```
  2. implemented navigation updates in index.html
  3. Committed changes
     ```bash
     git add index.html
     git commit -m "Update navigation bar"
     git push origin update-navigation
     ```
  **Jerry's Workflow (Contact Information)
  1. Created features branch
     ```bash
      git checkout -b add-contact-info
     ```
  2. Added contact information to index.html
  3. Committed changes
     ```bash
      git add index.html
      git commit -m "Add contact information"
      git push origin add-contact-info

**Merge Process**
   1.  Pull requests created for both feature branches
   2.  Code review performed
   3.  Features merged into main branch

## Screenshots

**Repositiory Creation**

[Screenshot](https://github.com/Abrahamnosa23/AI-Startup-Website/tree/main/Screenshot)

## Contributing

This project follows standard Git workflow:

   1. Fork the repository
   2. Create your feature branch (git checkout -b feature/AmazingFeature)
   3. Commit your changes (git commit -m 'Add some AmazingFeature')
   4. Push to the branch (git push origin feature/AmazingFeature)
   5. Open a Pull Request

## License

Distributed under the MIT License. See LICENSE for more information.







































