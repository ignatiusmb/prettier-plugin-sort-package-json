# prettier-plugin-sort-package-json

A [Prettier](https://prettier.io/) plugin to automatically keep `package.json` consistently tidy, sorted, and stress-free.

- 🔌 Zero dependencies
- ⚙️ No config, no hassle
- 🧹 Auto-lint with Prettier
- 🚀 Auto-sort with Prettier
- 🌟 Set once and forget

## Installation

This example use `pnpm`, but this works with any package manager

```bash
pnpm add -D prettier-plugin-sort-package-json
# or
npm install -D prettier-plugin-sort-package-json
```

## Usage

Use like [any other Prettier plugin](https://prettier.io/docs/plugins), load it with the CLI via `--plugin` or include it in your [config file](https://prettier.io/docs/configuration) via `"plugins"` list:

```json
{
	"plugins": ["prettier-plugin-sort-package-json"]
}
```

If you need to sort a `package.json`-like file, you can use the custom `parser` option:

```json
{
	"plugins": ["prettier-plugin-sort-package-json"],
	"overrides": [
		{
			"files": ["pkg.json", "template.json"],
			"options": {
				"parser": "sort-package-json"
			}
		}
	]
}
```

That's it. No mental overhead.
