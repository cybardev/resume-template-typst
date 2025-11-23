# Typst Resume Template

Basic resume template in Typst with a GitHub Actions workflow to generate PDFs and publish to a GitHub Pages website.

## Usage

- [Click this link](<https://github.com/new?template_name=resume-template-typst&template_owner=cybardev>) or the big green <kbd>Use this template</kbd> button near the top-right corner of this page and select <kbd>Create a new repository</kbd>.
- Continue to your own newly created repository. A copy of this README will be ready for you there.
- Enable GitHub Actions in your repository settings ([docs link](<https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository>)).
- Set the publishing source for your GitHub Pages site to GitHub Actions workflow ([docs link](<https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow>)).
- In your own newly created repository, copy [`example.typ`](./example.typ) to [`src/`](./src/) and rename it to what you want.
- Edit the newly renamed file to contain your information. You can use whatever functions are available in [`lib/`](./lib/).
- Edit the `AUTHOR` env var in [`.github/workflows/publish.yml`](./.github/workflows/publish.yml) to your desired name, and
- Stage, Commit, and Push. Then you'll have an action running to publish your site in a few minutes.
