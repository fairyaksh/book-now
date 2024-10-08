# BookNow

This is an example sentence that provides a quick summary of the project.

## Outcome(s)

Insert more detail regarding the aims and outcomes of the project.

- [DGC](https://bookwhen.com/dgcdance#focus=ev-szo3-20240815190000)
- [Studio 808](https://bookwhen.com/studio808#focus=ev-s5fd-20240815190000)
- [KMDC](https://bookwhen.com/kpopinlondonmin#focus=ev-s220-20240815190000)

## Stack

- Vite
- Pinia
- Vitest
- Cypress
- ESLint

## Testing

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```
