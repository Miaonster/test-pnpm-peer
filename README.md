## Reproduce

1. remove `pnpm-lock.yaml`
2. `pnpm install` and check, peer dependency `graphql` is installed
3. remove `node_modules`
4. `pnpm install` again and check, peer dependency `graphql` is missing
