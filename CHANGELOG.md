# wyw-in-js

## 0.2.3

### Patch Changes

- Bump versions

## 0.2.2

### Patch Changes

- e1701d5: Fix the regression from callstack/linaria#1373 that messed up with namespaces in CSS.
- 740e336: Fix regression from #19 that kills some exports.
- a8e5da0: Improved shaker strategy for exports fixes some of `undefined` errors.
- 3b91afe: CLI didn't work because of the wrong glob version.

## 0.2.1

### Patch Changes

- Bump versions

## 0.2.0

### Minor Changes

- ca5c2e7: All Linaria-related things were renamed.

### Patch Changes

- 4b869aa: Fixtures generator and enhanced support of different transpilers.

## 0.1.1

### Patch Changes

- 334833c: Plugin for Vite.
- 6f8ae08: Plugin for Rollup.
- 45c0206: https://wyw-in-js.dev/
- 6166aa6: Plugin for esbuild.

## 0.1.0

### Minor Changes

- 02973e1: `@linaria/webpack5-loader` has been moved and renamed into `@wyw-in-js/webpack-loader`. Support for Webpack 4 has been dropped.
- e02d5d2: `@linaria/babel-preset` and `@linaria/shaker` have been merged into `@wyw-in-js/transform`.
