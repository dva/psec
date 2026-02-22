**TL;DR**: [Mitigating supply chain attacks](https://pnpm.io/supply-chain-security).

##### Key points:
- Define `pnpm` version in package.json `packageManager` field.
- Keep your `pnpm` version up to date by using [`self-update`](https://pnpm.io/cli/self-update) command.
- Use [`pnpm-workspace.yaml`](https://pnpm.io/settings) file with security settings (consider using [`defaults plugin`](https://github.com/pnpm/plugin-better-defaults)).
- Use `pnpm-lock.yaml` file to lock dependencies.
- Use `pnpm audit` command to check for vulnerabilities.
