# Setup — Debarko Ghosh GitHub Profile

1. Create a public repository named **`devRko`** under the `devRko` GitHub account.
2. Upload the contents of this package and push to `main`.
3. In **Settings → Actions → General → Workflow permissions**, select **Read and write permissions**.
4. Run these workflows manually once from the Actions tab:
   - `🚀 Refresh Developer Profile`
   - `🐍 Generate Contribution Snake`

The profile dashboard refreshes every 6 hours. The snake refreshes every 12 hours and publishes its SVG files to the `output` branch.

The active username is configured in:
- `.github/workflows/profile.yml`
- `.github/workflows/snake.yml`

If your GitHub username or profile repository name changes, update both workflow files and the raw GitHub snake URLs in `README.md`.
