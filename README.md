# Evenly

A Splid-style app for splitting group expenses: groups, people, expenses, payments,
equal / custom-amount / percentage splits, custom currency, balances and suggested payments.

## Files

- `index.html` – standalone version. Works anywhere, including GitHub Pages.
  Data is saved in each person's own browser, so it is not shared between phones.
- `evenly-shared.html` – shared version for people who join from their own phones.
  It uses the claude.ai artifact database, so it only works when published as a
  claude.ai artifact. On GitHub Pages it shows a "storage isn't available" message.

## Publish on GitHub Pages

1. Push these files to a repository.
2. In the repository, open Settings → Pages.
3. Choose the main branch and the root folder, then save.
4. Your app will be at `https://<your-username>.github.io/<repo-name>/`.
