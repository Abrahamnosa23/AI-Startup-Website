# AI Startup Website - Collaborative Git Project

![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

A demonstration of collaborative development using Git and GitHub, simulating a team workflow between two developers (Tom and Jerry).

## Project Overview
This project showcases:
- Git branching strategies
- Pull request workflows
- Conflict resolution
- Team collaboration patterns

## Features
- Modular development of website components
- Isolated feature branches
- GitHub pull request reviews
- CI/CD-ready structure

## Screenshot


## Workflow Steps

### Initial Setup
```bash
git clone https://github.com/your-username/ai-startup-website.git
cd ai-startup-website
```
### Tom's Navigation Update
   1. Create branch

      ```bash
      git checkout -b update-navigation
      ```
   2. Edit index.html
      <nav>Navigation Bar Content</nav>
   3. Push changes

      ```bash
      git add index.html
      git commit -m "Add navigation bar"
      git push origin update-navigation
      ```
### Jerry's Contact Info
   1. Sync with main:

      ```bash
      git checkout main
      git pull origin main
      ```
   2. Create branch:

      ```bash
      git checkout -b add-contact-info
      ```
   3. Edit index.html:

      <footer>Contact: email@example.com</footer>

## Workflow Screenshots

### Creating Pull Requests
   * Pull Request Creation

### Merging Changes
   * Merging PR

## Branch Management
Branch	Purpose	Status
main	Production	Protected
update-navigation	Tom's work	Merged
add-contact-info	Jerry's work	Merged

## Commands Cheatsheet
   ```bash
   # Compare branches
   git diff main..update-navigation
   
   # Check merge conflicts
   git status
   
   # Update local repo
   git fetch --all
   git pull origin main
   ```

## Contribution Guide
   1. Fork the repository
   2. Create your feature branch (git checkout -b feature/AmazingFeature)
   3. Commit your changes (git commit -m 'Add some feature')
   4. Push to the branch (git push origin feature/AmazingFeature)
   5. Open a Pull Request

## License
   MIT © Abraham Aigbokhan
