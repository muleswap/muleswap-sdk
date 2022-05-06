# Muleswap SDK

Forked from the [Pancakeswap SDK](https://github.com/pancakeswap/pancake-swap-sdk/commit/d2903d4c136cd11eeda0f3f874a838632fd75704).

You can refer to the Pancakeswap SDK documentation [pancakeswap.finance](https://openbase.com/js/@pancakeswap-libs/sdk/documentation).

## Running tests

To run the tests, follow these steps. You must have at least node v12 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/muleswap/muleswap-sdk.git
```

Move into the muleswap-sdk working directory

```sh
cd muleswap-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
