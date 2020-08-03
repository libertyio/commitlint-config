Introduction
============

Preferred configuration for commitlint.

Based on [config-angular](https://github.com/conventional-changelog/commitlint/blob/master/@commitlint/config-angular/index.js)
with the following changes:

* replaced `config-angular-type-enum` with `@libertyio/commitlint-config-type-enum`

Development
-----------

How to build:

```
npm run lint
npm run build
```

Commits in this repository are also checked by commitlint. To update the rules,
copy the `rules` object from `src/main.js` to the top of `commitlint.config.js`.
