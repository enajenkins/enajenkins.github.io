# enajenkins.github.io

## Steps to deploy a Gatsby site to GitHub Pages:

1. Create a new repository on GitHub. Name the repository `"yourusername.github.io"` (replace `"yourusername"` with your GitHub username).

2. Install Gatsby by running `npm install -g gatsby-cli` in your terminal.

3. Create a new Gatsby site by running `gatsby new my-gatsby-site` in your terminal (replace `"my-gatsby-site"` with the name of your site).

4. Change into the new directory by running `cd my-gatsby-site`.

5. Edit the `gatsby-config.js` file to add your site metadata and plugins.

6. Build your site by running `gatsby build`.

7. Create a new branch in your repository by running `git checkout -b gh-pages`.

8. Move the built files to the new branch by running `git add public && git commit -m "Initial commit"`.

9. Push the new branch to GitHub by running `git push --set-upstream origin gh-pages`.

10. Navigate to the `Settings` tab in your repository.

11. Scroll down to the `GitHub Pages` section.

12. Select `"gh-pages"` as your source branch.

13. Click `"Save"` to publish your website.

14. Wait a few minutes for GitHub to build your site, then navigate to `"yourusername.github.io"` in your web browser to view your website.