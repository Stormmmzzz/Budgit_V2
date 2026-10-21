BUDGIT - UPDATED PROJECT

Files:
- index.html: app structure
- script.js: application logic
- sty.css: styling
- fonts/: local Nexa Pro font files

Run locally:
1. Extract the complete project folder.
2. Keep index.html, script.js, sty.css, and fonts/ together.
3. Open index.html with VS Code Live Server for best results.

Updates in this version:
- Savings goal creation is split into focused popup steps.
- Target date uses the browser calendar date picker.
- Check-in time uses a custom-styled hour/minute selector.
- Savings check-ins use an in-app modal with Yes/No and amount entry, not browser confirm/prompt dialogs.
- Insights includes a monthly budget overview and subscription evaluator.
- Subscription details includes an evaluator action.
- Choosing “Save for it” when completing a Decide assessment creates a linked savings goal.
- Budget label says “Money available”.

Notes:
- Exchange rates require internet access. When rates cannot be retrieved, cross-currency totals may be unavailable rather than silently treating currencies as equal.
- Reminder popups work while the app is open. Browser tabs that are fully closed cannot show in-app reminders.
- Please test the new workflows in a browser before replacing your working copy. Back up your current data first.
- Ensure your font files are used according to their licence.
