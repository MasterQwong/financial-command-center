# Financial Command Center

A lightweight, mobile-friendly personal finance dashboard.

## Privacy model

This version stores financial data only in the browser using `localStorage`.

- No financial balances are committed to this repository.
- No server or database receives the data.
- Data entered on one device does not automatically appear on another device.
- Clearing browser storage can erase locally saved data.

Do not hard-code personal balances into `index.html` if the repository or website is public.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `.nojekyll`, and this `README.md` to the repository root.
3. Open the repository's **Settings**.
4. Select **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/ (root)` folder.
7. Save. GitHub will show the website address after deployment.

## Local use

Open `index.html` in a modern browser.

## Current limitations

- Data is stored per browser/device.
- There is no sign-in.
- There is no automatic bank connection.
- There is no cloud backup or cross-device sync.

A later private version can add authentication, encrypted cloud storage, statement imports, and device sync.
