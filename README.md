# Poker

A Texas Hold'em poker table UI built with React and TypeScript.

> **Archived.** Built in 2018–2019 and no longer maintained. Kept for reference.

This is the client-side table only — card rendering, hand models and layout.
There is no game server and no opponent logic.

```
src/cards/        card and deck rendering
src/models/       hand and table models
src/constants/    suits, ranks, table configuration
src/test/         unit tests
```

## Running locally

```bash
yarn install
yarn start
```

Built on `react-scripts-ts` (React 16, TypeScript 2.9), the TypeScript fork of
Create React App that predated CRA's own TypeScript support. It will not build
against current toolchains without migration.

## Licence

[MIT](LICENSE)
