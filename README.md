# TS Node Boilerplate

This is a quite simple boilerplate which aims to deal with scalable applications with pre-intalled tools to make the development process straightforward and enjoyable.

## Tools

- Typescript
- Prettier
- ESLint
- TS-Node
- Jest

## Commands

To build

```
npm run build
```

To start dev (will be executed through ts-node-dev with respawn option)

```
npm run start:dev
```

To start prod (will execute the index file inside dist folder)

```
npm start:prod
```

To list files to be fixed by eslint

```
npm run lint
```

To fix files with eslint

```
npm run lint:fix
```

To list files to be fixed by prettier

```
npm run format:check
```

To fix files with prettier

```
npm run format:fix
```
