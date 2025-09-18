# Assistmakers Commerce (Shopify Theme)

This repo tracks the Assistmakers Shopify theme.

## Branching model
- `dev`: Preview theme (work in progress)
- `main`: Live theme (production)

## Workflow
1. Create feature branch from `dev`.
2. Commit changes, open Pull Request into `dev`.
3. QA/staging tests.
4. PR into `main` only after approval.

## Release checklist
- [ ] QA on multiple devices
- [ ] Accessibility check
- [ ] Lighthouse performance check
- [ ] SEO metadata updated
- [ ] Donation flow tested

---

## Local development (optional)
- Install Shopify CLI
- Run `shopify theme dev`
