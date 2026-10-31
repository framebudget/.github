![framebudget](https://raw.githubusercontent.com/framebudget/assets/main/brand/og.png)

**Keep the effects. Lose the stutter.**

At 60 Hz every frame has a 16.7 ms budget. framebudget measures how much budget a device really has and allows only the visual effects that fit, so slow phones never stutter and fast phones keep everything.

[framebudget.dev](https://framebudget.dev) · [API reference](https://framebudget.dev/api) · [Lab](https://framebudget.dev/lab) · [Privacy](https://framebudget.dev/privacy)

## Packages

| Package | What it is | npm |
| --- | --- | --- |
| [`framebudget`](https://www.npmjs.com/package/framebudget) | the core under its short name | [![version](https://img.shields.io/npm/v/framebudget)](https://www.npmjs.com/package/framebudget) ![downloads](https://img.shields.io/npm/d18m/framebudget) |
| [`@framebudget/core`](https://www.npmjs.com/package/@framebudget/core) | the core, without any framework | [![version](https://img.shields.io/npm/v/@framebudget/core)](https://www.npmjs.com/package/@framebudget/core) ![downloads](https://img.shields.io/npm/d18m/@framebudget/core) |
| [`@framebudget/react`](https://www.npmjs.com/package/@framebudget/react) | React hooks: `useBudget`, `useTier`, `BudgetProvider` | [![version](https://img.shields.io/npm/v/@framebudget/react)](https://www.npmjs.com/package/@framebudget/react) ![downloads](https://img.shields.io/npm/d18m/@framebudget/react) |
| [`@framebudget/vue`](https://www.npmjs.com/package/@framebudget/vue) | Vue composables: `useBudget`, `useTier`, `provideBudget` | [![version](https://img.shields.io/npm/v/@framebudget/vue)](https://www.npmjs.com/package/@framebudget/vue) ![downloads](https://img.shields.io/npm/d18m/@framebudget/vue) |
| [`@framebudget/angular`](https://www.npmjs.com/package/@framebudget/angular) | Angular signals: `injectBudget`, `injectTier`, `provideBudget` | [![version](https://img.shields.io/npm/v/@framebudget/angular)](https://www.npmjs.com/package/@framebudget/angular) ![downloads](https://img.shields.io/npm/d18m/@framebudget/angular) |

```sh
npm install framebudget
```

## Repositories

- [core](https://github.com/framebudget/core): the library and its framework packages
- [website](https://github.com/framebudget/website): framebudget.dev, the API reference and the Worker that collects anonymous calibration reports
- [assets](https://github.com/framebudget/assets): brand (logo, fonts, tokens, release card) and the launch video

## Help calibrate it

The thresholds are still provisional. Running the [lab](https://framebudget.dev/lab) on your phone or laptop, or turning on anonymous sharing in your site, feeds real devices into the calibration. No IP, no user agent, no cookies, no URL: [what is sent](https://framebudget.dev/privacy).
