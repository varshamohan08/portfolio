# portfolio

[![Owner Avatar](https://avatars.githubusercontent.com/varshamohan08)](https://github.com/varshamohan08)

This repository contains the build folder (docs) of my portfolio website, which is deployed using GitHub Pages. Explore my projects, experiences, and more through this interactive platform.

## Deployment Workflow

The deployment of the static content to GitHub Pages is automated using GitHub Actions. The workflow defined in `.github/workflows/static.yml` ensures that the latest changes are deployed to the `main` branch.

### Workflow Description

- **Name**: Deploy static content to Pages
- **Triggers**: Automatically triggered on push to the `main` branch and manually triggered from the Actions tab.
- **Concurrency**: Allows only one concurrent deployment, skipping runs queued between the run in-progress and latest queued.

## License

This project is licensed under the [MIT License](LICENSE).
