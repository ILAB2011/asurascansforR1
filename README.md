# Asura Scans Smooth Reader for Rabbit R1

An optimized web canvas configuration designed to safely stream manga/manhwa chapters directly to the **Rabbit R1 hardware layout** without triggering out-of-memory browser crashes.

## Quick Setup Instructions

1. **Deploy the Site:** Upload the `index.html` file to a public GitHub repository and enable **GitHub Pages** in the repository settings.
2. **Update the Payload:** Open `r1-config.json` and replace `YOUR_GITHUB_USERNAME` and `YOUR_REPO_NAME` with your actual live GitHub Pages URL.
3. **Generate QR:** Copy the final text string inside `r1-config.json` and paste it into any online QR code generator as **Raw Text**.
4. **Scan:** Double-click the physical side button on your R1, point the camera at the QR code, and click to load it onto your card stack.
