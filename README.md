# lint-config-setup

## `@nokon/eslint-config`

### Usage
```sh
    npm install @nokon/eslint-config --dev
```

Create the corresponding files and extend the configurations Eslint (.eslintrc):

```
    {
        "extends": [
            "@nokon/eslint-config"
        ],
    }
```

```
    const eslintConfig = require('@nokon/eslint-config');
```

## `@nokon/prettier-config`

### Usage
```sh
    npm install @nokon/prettier-config --dev
```

Create the corresponding files and extend the configurations Prettier (.prettierrc):

```
    {
        "prettier": "@nokon/prettier-config"
    }
```

```
    const prettierConfig = require('@nokon/prettier-config');

```