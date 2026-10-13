# SI-Agent public website

Public information and legal pages for the independent, owner-controlled SI-Agent personal AI assistant.

This repository is **public and contains only static website files**. The application source code and deployment configuration remain in the separate **private** `Wickedly/SI-Agent` repository.

## Files

- `index.html` — public SI-Agent overview
- `privacy.html` — privacy policy (Google Gmail and Calendar data practices)
- `terms.html` — terms of use
- `styles.css` — responsive styling
- `.nojekyll` — serve static assets without Jekyll processing

## GitHub Pages publishing

1. Open [Settings → Pages](https://github.com/Wickedly/SI-agent-Public/settings/pages).
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then **Save**.
4. After GitHub deploys the site, check:
   - Home: https://wickedly.github.io/SI-agent-Public/
   - Privacy: https://wickedly.github.io/SI-agent-Public/privacy.html
   - Terms: https://wickedly.github.io/SI-agent-Public/terms.html

## Google OAuth review notes

- GitHub Pages is not a guarantee of Google OAuth domain ownership verification. Google may require a domain that the developer can verify in Search Console.
- A published static privacy policy **does not itself** move an OAuth app out of Testing, waive Gmail restricted-scope verification, or authorize new permissions.
- Review the policy text against the real enabled scopes and data flow before publishing OAuth branding.
- Replace the GitHub-profile contact link with a dedicated accessible support/privacy email address if Google requests one.
- Do not place any private SI-Agent source code, credentials, personal Gmail messages, server addresses or logs in this repository.
