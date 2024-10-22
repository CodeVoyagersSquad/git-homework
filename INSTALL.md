# Installation Guide

This guide will help you set up and run our team webpage locally.

## Prerequisites

- A web browser (Chrome, Firefox, Safari, or Edge recommended)
- Git installed on your computer
  - [Download Git](https://git-scm.com/downloads) if you haven't installed it yet
  - Verify installation by running `git --version` in your terminal

## Installation Steps

1. Clone the Repository
   ```bash
   git clone https://github.com/CodeVoyagersSquad/git-homework.git
   cd git-homework
   ```

2. Project Structure
   The repository contains the following files:
   - `index.html`: Main team webpage
   - `README.md`: Project overview and documentation
   - `LICENSE.md`: Project license information
   - `CONTRIBUTING.md`: Guidelines for contributing to the project
   - `CODE-OF-CONDUCT.md`: Project code of conduct

## Running the Project

1. Open in Browser
   - Navigate to the project directory
   - Double-click on `index.html` or right-click and open with your preferred web browser
   
   Alternatively, you can use Python's built-in HTTP server:
   ```bash
   # If you have Python 3 installed
   python -m http.server 8000
   
   # Then open http://localhost:8000 in your browser
   ```

## Troubleshooting

### Common Issues

1. Page not displaying properly
   - Make sure all files are in the correct directory
   - Try clearing your browser cache
   - Ensure you're using a modern web browser

2. Git clone issues
   - Verify you have the correct repository URL
   - Check your internet connection
   - Ensure you have appropriate permissions

### Getting Help

If you encounter any problems:
1. Check the GitHub repository issues section
2. Contact team members through the emails listed on the webpage
3. Create a new issue in the repository

## Updates and Maintenance

To keep the project up to date:
```bash
git pull origin main
```

## Development Setup (Optional)

For developers who want to contribute:
1. Fork the repository
2. Create a new branch for your features
3. Follow the contribution guidelines in CONTRIBUTING.md

## Version Information

- Current Version: 1.0.0
- Last Updated: October 2024
- Tested on: Chrome 120+, Firefox 120+, Safari 17+