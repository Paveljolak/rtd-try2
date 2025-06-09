# Ubiquity Robotics Gen 6 Documentation

This repository contains the source files for the Gen 6 robot documentation by Ubiquity Robotics.  It is built using [Spinx](https://www.sphinx-doc.org/) and styled using the [Read the Docs](https://github.com/readthedocs/sphinx_rtd_theme) theme. The documentation is deployed via [Github Pages](https://pages.github.com/).

## Overview
This site provides technical documentation for Ubiquity Robotics' sixth-generation robots, including information on hardware components, usage guides, software images and system sofware.

## Deployment
The documentation is built and deployed automatically using GitHub Actions. The latest version is available at:

<!-- TODO: Change this to the actual website when the repo is switched. -->
**[https://paveljolak.github.io/rtd-try2/](https://paveljolak.github.io/rtd-try2/)**

## Local Development
To build and run the documentation locally:

<!-- TODO: Add the right links and names for cloning the repository. -->
```bash
git clone https://github.com/Paveljolak/rtd-try2.git
cd your-repo-name
python3 -m venv .venv # Run this only the first time you clone the repo.
source .venv/bin/activate  # Windows: .venv\Scripts\activate


# Install latest compatible dependencies:
pip install -r required_packages.txt # Run this only the first time you clone the repo


# (Optional) Install exact versions used in development:
# pip install -r required_packages_versions.txt

# Build the documentation 
make html 

# Open in browser
firefox _build/html/index.html

# (Optional - Requires sphinx-autobuild)
sphinx-autobuild . _build/html # autobuilds the site on save. It serves it locally on port 8000. 
# [sphinx-autobuild] Serving on http://127.0.0.1:8000

```