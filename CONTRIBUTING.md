# Contributing to LicenseForge

Thanks for your interest! This guide applies to every repository in the `licenseforge` organization. Repositories may add their own `CONTRIBUTING.md` with build and test instructions.

## Ground rules
- Be kind. All participation is covered by the [Code of Conduct](CODE_OF_CONDUCT.md).
- **Security issues are never reported in public issues.** See [SECURITY.md](SECURITY.md).
- For anything bigger than a small fix, open an issue first so we can agree on the approach.
- Significant design changes are recorded as Architecture Decision Records in `docs/adr/` of the main repository.

## Developer Certificate of Origin (DCO)
All contributions are licensed under the [Apache License 2.0](LICENSE). We don't use a CLA. Instead, every commit must be signed off, certifying the [Developer Certificate of Origin](https://developercertificate.org/):

```
git commit -s -m "Fix activation count on rehost"
```

This adds a line like `Signed-off-by: Jane Doe <jane@example.com>` using your git `user.name` and `user.email`. Pull requests with unsigned commits can't be merged. To sign off previous commits: `git rebase --signoff main`.

## Pull requests
1. Fork and create a branch from `main`.
2. Keep changes focused; one logical change per PR.
3. Add or update tests. Security-sensitive code (signing, verification, authz, tenancy) needs tests that fail without your change.
4. Make sure CI passes.
5. Use clear commit messages: imperative mood, short subject line, details in the body.

## Reporting bugs and requesting features
Use the issue templates. Include versions, environment (Kubernetes version, cloud, air-gapped or not) and steps to reproduce.
