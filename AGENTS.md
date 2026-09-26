# Shopwell split-package rules

This repository is the generated, independently published `shopwell/storefront` package from `shopwell-shop/shopwell`.

- Preserve UTF-8 and generated assets. Changes belong in the Shopwell platform monorepo and must reach this repository through the documented split release process.
- Shopwell-owned code and `composer.json` use the Apache License 2.0 (`Apache-2.0`); root `LICENSE` contains the standard text.
- Preserve every upstream legal text verbatim in root `NOTICE`; never brand or paraphrase it.
- Outside `NOTICE`, do not reintroduce Shopware branding, packages, repositories, or Actions.
- Dependencies must use stable registry releases, never Git URLs, branches, commits, archives, `dev-*`, `path`, `file`, or `link` fallbacks.
- Do not merge or cherry-pick upstream history, copy upstream tags, edit this generated repository directly, or force-push.
- This repository has no independent upstream checkpoint. Its source, target repository, and Composer publication are audited through the `shopware` monorepo entry.
- Before release completion, run `../sync-upstream/bin/syncctl audit-license shopware` and `../sync-upstream/bin/syncctl audit-upstream-dependencies shopware`. A failed audit blocks completion.
