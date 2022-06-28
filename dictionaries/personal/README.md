# Cspell personal Dictionary

Personal dictionary for CSpell.

This is a pre-built dictionary for use with cspell.

## Installation

Global Install and add to cspell global settings.

```sh
npm install -g @palebludot/cspell-personal
cspell link add @palebludot/cspell-personal
```

## Uninstall from cspell

```sh
cspell link remove @palebludot/cspell-personal
```

## Manual Installation

Manual installation is useful if you want to include this dictionary as part of your CI/CD lint process.

```
npm i @palebludot/cspell-personal
```

The `cspell-ext.json` file in this package should be added to the import section in your `cspell.json` file.

```javascript
{
    // …
    "import": ["@palebludot/cspell-personal/cspell-ext.json"],
    // …
}
```

# Dictionary Development

See: [How to Create a New Dictionary](https://github.com/streetsidesoftware/cspell-dicts#how-to-create-a-new-dictionary)

## License

MIT

> Some packages may have other licenses included.
