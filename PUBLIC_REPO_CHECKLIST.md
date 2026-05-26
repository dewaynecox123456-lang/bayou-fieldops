# Public Repository Checklist

Run this checklist before pushing or publishing a public Bayou FieldOps repository.

## Required Public-Safe Content

- Product overview is public-safe.
- Feature list is high level only.
- Privacy statement does not expose internal implementation details.
- Commercial licensing statement is present.
- Purchase/support link points to https://bayoufinds.com.
- Screenshots are redacted and public-safe.
- Changelog is public-safe.
- Issue guidance warns users not to post sensitive data.

## Must Not Be Public

- Local paths or usernames.
- Customer data.
- Payhip, order, or license details.
- Seller ledger files or ledger instructions.
- Issued licenses.
- Internal docs.
- Private runbooks.
- Generated release folders.
- Stale build artifacts.
- Private support notes.
- Credentials, tokens, keys, or support access files.

## Scan Before Publish

Search for risky terms and review every match:

- `license_key`
- `payhip`
- `customer_email`
- `seller_ledger`
- local home paths
- private usernames
- `private`
- `issued`
- `order_id`

Any match in customer records, private docs, generated folders, release artifacts, or licensing workflow files should be removed from the public repo or kept only in the private/paid FieldOps version.
