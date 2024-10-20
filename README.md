# DigLib React Client

This repository contains the built version of the DigLib React application, automatically deployed from our GitLab CI/CD pipeline.

**Source Code**: [https://gitlab.stud.idi.ntnu.no/it1901/groups-2024/gr2462/gr2462](https://gitlab.stud.idi.ntnu.no/it1901/groups-2024/gr2462/gr2462)


## Overview

DigLib is a digital library management system with a React frontend. This repository hosts the production-ready build of the React application.

## Deployment

The app is automatically deployed to Cloudflare Pages:

- **Deployment URL**: [https://diglib-react-deployment.pages.dev/](https://diglib-react-deployment.pages.dev/)

## Repository Structure

This repository contains the built React application files:

- `index.html`: The main HTML file
- `static/`: Directory containing JavaScript, CSS, and other static assets
- `asset-manifest.json`: Manifest file for the built assets

## Development

This repository is for deployment purposes only. For development:

1. The source code is maintained in a private GitLab repository.
2. Changes should be made in the GitLab repository.
3. The GitLab CI/CD pipeline automatically builds and deploys changes to this repository.
