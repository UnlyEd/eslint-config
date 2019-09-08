# eslint-config

> ESLint base configuration for projects @Unly
>
> Each language/environment has its own folder/config

# How to use

`yarn add -D eslint`

Run `eslint init` and follow the CLI guide.

It will create a `.eslintrc.yml` file _(we prefer **YAML** over JS/JSON)_

Once created, find the config the most appropriate for your project, and follow its `README.md`.

# Utility scripts to add to the project

> Not required, but comes in handy.

```
"lint": "eslint src/**",
"lint:fix": "eslint src/** --fix",
"lint:fix:preview": "eslint src/** --fix-dry-run",
```

Add those in your `package.json`, under `scripts`.
