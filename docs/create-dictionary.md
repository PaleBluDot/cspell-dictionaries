---
order: 800
icon: book
---

# Create Dictionary

## Getting Started

1. `npm i`
2. `lerna bootstrap`
3. `lerna create <packageName>`
4. `cp template/** dictionaries/<packageName>/`

## Templates Variables

The templates files have these places holders to make updates using find/replace simple.

- `<%= packageName %>`
  - ex. `example`
- `<%= fullPackageName %>`
  - ex. `@palebludot/cspell-example`
- `<%= friendlyName %>`
  - ex `example`
- `<%= name %>`
  - ex `example`
- `<%= description %>`
  - ex `Example dictionary for CSpell.`
- `<%= command %>`
  - ex `compile`
- `<%= local %>`
  - ex `*`
- `<%= languageId %>`
  - ex `en-US`
- `<%= dstFileName %>`
  - ex `example.txt`
- `<%= srcFile %>`
  - ex `example.txt`

## Final Steps

1. `lerna run prepare`
   - Prepare the files as if they were ready to build
2. `lerna run test`
3. `lerna publish`
