# Click2SMS Test Bench

Static test page for checking SMS URL handoff behavior on iOS and Android.

## Deploy With GitHub Pages

1. Create a new GitHub repository, for example `click2sms-test`.
2. Upload `index.html`, `.nojekyll`, and this `README.md`.
3. Open repository **Settings**.
4. Go to **Pages**.
5. Set source to **Deploy from a branch**.
6. Select branch `main` and folder `/root`.
7. Save and wait for GitHub Pages to publish the URL.

The published page will look like:

```text
https://YOUR_USERNAME.github.io/click2sms-test/
```

## What To Test

- Whether the SMS recipient is prefilled.
- Whether the SMS message body is prefilled.
- Whether the user returns to the landing page automatically.
- Which browser lifecycle events fire when leaving and returning.

The page can track click and return signals, but cannot confirm that the SMS was actually sent.
