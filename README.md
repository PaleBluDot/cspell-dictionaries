# CSpell Dictionaries

A monorepo of CSpell dictionaries.

## Commands

### `init`

We’ll start by generating a Lerna config with lerna init.

```bash
lerna init
```

If you prefer the independent mode, add --independent to the command.

```bash
lerna init --independent
```

### `list`

List packages.

```bash
lerna ls
```

### `create`

Create a new lerna-managed package.

```bash
lerna create <name> <loc>
```

### `bootstrap`

Download NPM dependencies and cross-link packages in the repository.

```bash
lerna bootstrap
```

### `version`

Push all the changes to the remote repository and creates a Git tag.

```bash
lerna version
```

### `publish`

Publish packages in the current project.

```bash
lerna publish [bump]
```

## Getting Started

1. `npm i`
2. `lerna bootstrap`
3. `lerna create <packageName>`
4. `cp template/** dictionaries/<packageName>/`
5. `lerna run prepare`
6. `lerna run test`
