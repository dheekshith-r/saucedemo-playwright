# Security policy

## Report a problem in private

If you find a security problem in SauceDemo tests, do not open a public issue.

1. Open the [private report form](https://github.com/dheekshithsnewjourney-crypto/saucedemo-playwright/security/advisories/new).
2. Describe the problem and the steps to see it.
3. Send the report.

You will get an answer within 7 days. When the fix is live, the report can be made public, with credit to you if you want it.

## What is in scope

- The tests and the CI workflow in this repository
- The code in this repository

## Supported versions

Only the live version, built from `main`, gets fixes.

## Notes

- The suite tests public demo sites (saucedemo.com and Restful-Booker). It holds no real accounts or keys.
- The only password in the code, `secret_sauce`, is the public demo password shown on saucedemo.com.
- CI has read-only permissions.
