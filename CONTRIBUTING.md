# Contributing to SauceDemo tests

Thank you for your help. Bug reports and ideas are the most useful help.

## Report a bug or suggest an idea

1. Open [a new issue](https://github.com/dheekshithsnewjourney-crypto/saucedemo-playwright/issues/new/choose).
2. Choose "Bug report" or "Idea".
3. Fill in the form. Do not paste private data; issues are public.

For a security problem, follow [SECURITY.md](./SECURITY.md) instead.

## Change the code

1. Fork the repository and make a branch from `main`.
2. Set it up:
   ```bash
   npm install
   npx playwright install
   ```
3. Make your change. Keep it small and about one thing.
4. Run the checks:
   ```bash
   npm run test:chromium
   ```
5. Open a pull request and fill in the template.

## Rules for every change

- A new test checks one behaviour, has a clear name, and uses the helpers in `tests/helpers.ts`.
- Do not weaken or skip a test to make it pass.
- Never put secrets in code or in git history.
- Use `data-test` locators or roles, never CSS paths that break when the layout changes.

## Code of conduct

Everyone who takes part follows the [code of conduct](./CODE_OF_CONDUCT.md).
