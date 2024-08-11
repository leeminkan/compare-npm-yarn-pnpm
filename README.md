# Ref:

- https://refine.dev/blog/pnpm-vs-npm-and-yarn/#why-not-npm-or-yarn
- https://www.raulmelo.me/en/blog/making-the-switch-to-pnpm
- yarn pnp
- https://pnpm.io/benchmarks
- Not working with PNPM - https://github.com/vercel/next.js/issues/16471
- Pnpm seems to be consistently slower than yarn (classic) - https://github.com/pnpm/pnpm/issues/6447

# Let's go

- npm

```
cd npm-example
npm install --save express
node debug.js
npm install debug@2.6.9
npm install debug@2.6.8
```

- yarn

```
cd yarn-example
yarn add express
node debug.js
yarn add debug@2.6.9
yarn add debug@2.6.8
```

- pnpm

```
cd pnpm-example
pnpm install --save express
node debug.js
pnpm install debug@2.6.9
pnpm install debug@2.6.8
```

- Check disk usage

```
du -hd1
```

# Summary

```

3.8M ./yarn-example
3.9M ./npm-example
3.5M ./pnpm-example

```
