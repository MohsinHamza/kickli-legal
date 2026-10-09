# Kickli legal pages — draft

Files:
- `index.html` — landing page
- `privacy-policy.html` — privacy policy draft
- `delete-account.html` — account/data deletion draft

IMPORTANT: These pages contain “Verify before publishing” items because the exact backend, analytics/crash SDK, retention rules, and deletion implementation have not been confirmed. Resolve every item before publishing or submitting the links to Google Play.

Suggested GitHub Pages URLs for a repository named `kickli-legal`:
- `https://YOUR-GITHUB-USERNAME.github.io/kickli-legal/`
- `https://YOUR-GITHUB-USERNAME.github.io/kickli-legal/privacy-policy.html`
- `https://YOUR-GITHUB-USERNAME.github.io/kickli-legal/delete-account.html`

Publish:
1. Create a public GitHub repository named `kickli-legal`.
2. Upload these four files to the repository root.
3. Open Settings → Pages.
4. Under Build and deployment, choose “Deploy from a branch”, select `main` and `/(root)`, then Save.
5. Wait for deployment; open the site URL shown in Settings → Pages and test all three URLs in a private/incognito browser.
6. Use the privacy URL in the app's Play Console privacy policy field. In App content → Data safety, answer based on actual SDK and backend behavior. In the account deletion questions, provide the public deletion URL and confirm the in-app deletion path is implemented.
7. Do not submit the draft while unresolved placeholders or non-working deletion steps remain.
