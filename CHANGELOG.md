# intl-lightly

## 1.1.2

### Patch Changes

- Fix the CommonJS `require` export: it pointed at `dist/intl-lightly.umd.js`, but the
  build emits `dist/intl-lightly.umd.cjs` (the package is `"type": "module"`), so
  `require('intl-lightly')` failed with MODULE_NOT_FOUND.

## 1.1.1

### Patch Changes

- Publish through npm Trusted Publishing (OIDC) instead of a long-lived token. No runtime change.

## 1.1.0

### Minor Changes

- fix: Could not find a declaration file when tsconfig moduleResolution is bundler
