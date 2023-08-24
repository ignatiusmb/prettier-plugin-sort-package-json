# prettier-plugin-sort-package-json

A [Prettier](https://prettier.io/) plugin to sort the `package.json` file in a consistent and opinionated way, this ensures that your `package.json` file is always well-organized and easy to read.

-   🌟 Set and forget
-   🔌 Zero-dependency
-   🔧 Zero-configuration
-   🛠️ Auto-fix with Prettier
-   🚀 No extra commands needed
-   🧹 Lint together with Prettier

## Usage

To install `prettier-plugin-sort-package-json`, run the following command:

```bash
pnpm add -D prettier-plugin-sort-package-json
```

To use `prettier-plugin-sort-package-json` with the CLI, use the `--plugin` parameter:

```diff
- prettier --write .
+ prettier --write . --plugin=prettier-plugin-sort-package-json
```

If you have a configuration file, you can also add this to the `"plugins"` list:

```json
{
	"plugins": ["prettier-plugin-sort-package-json"]
}
```

You can then run Prettier as usual, and your `package.json` files will be sorted automatically.
