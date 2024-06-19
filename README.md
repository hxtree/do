# do

This monorepo utilizes Pnpm as the package manager and Nx for monorepo
management. It houses multiple packages used for demonstration purposes.

Install and build all packages.

```zshrc
corepack enable pnpm
pnpm install
pnpm nx run-many -t build --all
```

Scripts from any project can be ran

```zshrc
pnpm nx run @do/is-even:build
```

## Discourse

**NX for Monorepo Management**: NX excels in managing monorepos efficiently.
**Bare Metal**: The repository intentionally avoids Docker to enhance developer
experience on MacOS silicon. **PNPM**: PNPM's single package version usage
minimizes disk space and speeds up installations, making it optimal for
monorepos.

## Third-Party Documentation

[NX Package Based Repo](https://nx.dev/getting-started/tutorials/package-based-repo-tutorial)
