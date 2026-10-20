# Gram M2 disposable public smoke fixture

This repository exercises a source-only coding repair with Node 24.
The single test asserts that `increment(1)` equals `2`.

`npm test` discovers the real assertion, `npm run lint` checks syntax, and
`npm run build` strips TypeScript types into `dist/counter.js` and checks the output.

The fixture is first published with a passing implementation and real successful CI.
Before main protection is enabled, a single source line is seeded with an intentional
bug. A subsequent Gram task must repair that line and pass the required `verify` job.

This public disposable repository does not satisfy issue #77's private-repository condition.
