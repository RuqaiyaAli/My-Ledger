# MyLedger — iPhone personal money manager

All amounts are in Pakistani Rupees (PKR), never dollars.

Features:
- Income (tuition fee, extra income, gifts, other)
- Expenses and categories
- Money lent / udhaar given
- Money borrowed
- Repayments and returns
- Monthly reports and transaction history
- JSON backup/restore and CSV export
- PWA install support for iPhone Home Screen

## Important storage note
Entries are saved in the browser's local storage on the device where the app is opened. They do not sync between Windows and iPhone. Clearing browser/site data can erase entries, so export a JSON backup regularly. For the user's stated preference, use the iPhone as the main device for recording entries.

## Host free for iPhone use (GitHub Pages)
A hosted HTTPS link is needed for a reliable iPhone Home Screen app:
1. On Windows, sign in to GitHub and create a **new public repository** named `myledger`.
2. Extract this ZIP. Upload `index.html`, `manifest.json`, and `sw.js` to the repository root (not the ZIP itself).
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait until GitHub Pages gives you an HTTPS site link.
6. On iPhone, open that link in **Safari** (not an in-app browser). Tap Share → Add to Home Screen → Add.
7. Open MyLedger from the new Home Screen icon. Use that same iPhone/Safari-installed app for your real entries.

## Beginner note
No paid plan, bank connection, or App Store publishing is required for this first version. Do not upload personal financial data to GitHub; only upload these app files. The repository contains app code, not your saved transactions.
