# REDMOON - MIT Fashion Survey

This project is a "no-build" interactive survey application built with React and TypeScript. It is designed to be hosted directly on a static hosting service like GitHub Pages or Netlify without requiring a complex build process.

## How to Deploy to GitHub Pages

Follow these steps precisely to ensure your survey is deployed correctly.

### Step 1: Push Your Code to GitHub

Make sure all your files, including `index.html`, the `images` folder, and all `.tsx` and `.ts` files, are committed and pushed to your GitHub repository.

### Step 2: Configure GitHub Pages Settings

1.  In your GitHub repository, go to the **Settings** tab.
2.  In the left sidebar, click on **Pages**.
3.  Under the "Build and deployment" section, for the **Source**, select **Deploy from a branch**.
4.  Under "Branch", select your `main` (or `master`) branch and make sure the folder is set to `/ (root)`.

    

5.  Click **Save**.

### Step 3: Wait for Deployment

GitHub will now start deploying your site. It may take a minute or two. Once it's complete, you will see a green banner at the top of the Pages settings with the URL to your live site, like `https://<your-username>.github.io/<your-repo-name>/`.

**That's it!** Your site is now live.

### Troubleshooting

*   **White Screen Error:** This is almost always caused by an incorrect path or a failed script. The changes in this commit (making all asset paths relative, e.g., `./images/...`) are designed to fix this.
*   **404 Not Found:** If you see a "404 Not Found" page, double-check that your GitHub Pages settings are pointing to the correct branch and the `/ (root)` folder.
*   **Images Not Loading:** Ensure the `images` folder exists in the root of your repository and that all paths in the code are relative (`./images/...`).
