# Profile README Setup

1. Create a **public** GitHub repository named exactly `viniciusbevilaqua` under the `viniciusbevilaqua` account.
2. Upload the contents of this folder to that repository. `README.md` must remain at the repository root.
3. Keep `.github/workflows/snake.yml` in the same location shown here.
4. In the repository, open **Settings → Actions → General** and allow workflows to have **Read and write permissions**. Save the change.
5. Open the **Actions** tab, choose **Generate Contribution Snake**, then select **Run workflow** once.
6. After the workflow finishes, it creates the `output` branch and publishes the Snake SVG. The README will then display it automatically.

The workflow runs again every day. It uses the repository-provided `GITHUB_TOKEN`; no personal access token or additional secret is needed.

