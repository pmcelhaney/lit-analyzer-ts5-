# lit-analyzer and TypeScript 5

With TypeScript 5, the no-missing-import rule is not able to resolve dependencies, so it reports false positives.

To reproduce, run `npm ci` and then `npm test`.

To see that it works with previous versions of TypeScript, run `npm i typescript@4` and then `npm test` again.
