# typescript and javascript monorepo with IDE support

`lib` is a TypeScript library. `main` is a javascript project consuming `lib`.

- Everything is wired together using lerna.
- Your IDE will be able to discover the typings provided by `lib`.
- All duplicate dependencies are hoisted into the root project by lerna.

## Requirements

- `node` >= 10

## Setup

- `npm run bootstrap`
- `cd main; npm start`

