<!-- TITLE/ -->

# The Definitive List of Text Extensions

<!-- /TITLE -->

<!-- BADGES/ -->

<span class="badge-githubworkflow"><a href="https://github.com/diotoborg/eveniet-eaque-fugit/actions?query=workflow%3Abevry" title="View the status of this project's GitHub Workflow: bevry"><img src="https://github.com/diotoborg/eveniet-eaque-fugit/workflows/bevry/badge.svg" alt="Status of the GitHub Workflow: bevry" /></a></span>
<span class="badge-npmversion"><a href="https://npmjs.org/package/@diotoborg/eveniet-eaque-fugit" title="View this project on NPM"><img src="https://img.shields.io/npm/v/@diotoborg/eveniet-eaque-fugit.svg" alt="NPM version" /></a></span>
<span class="badge-npmdownloads"><a href="https://npmjs.org/package/@diotoborg/eveniet-eaque-fugit" title="View this project on NPM"><img src="https://img.shields.io/npm/dm/@diotoborg/eveniet-eaque-fugit.svg" alt="NPM downloads" /></a></span>
<br class="badge-separator" />
<span class="badge-githubsponsors"><a href="https://github.com/sponsors/balupton" title="Donate to this project using GitHub Sponsors"><img src="https://img.shields.io/badge/github-donate-yellow.svg" alt="GitHub Sponsors donate button" /></a></span>
<span class="badge-thanksdev"><a href="https://thanks.dev/u/gh/bevry" title="Donate to this project using ThanksDev"><img src="https://img.shields.io/badge/thanksdev-donate-yellow.svg" alt="ThanksDev donate button" /></a></span>
<span class="badge-patreon"><a href="https://patreon.com/bevry" title="Donate to this project using Patreon"><img src="https://img.shields.io/badge/patreon-donate-yellow.svg" alt="Patreon donate button" /></a></span>
<span class="badge-liberapay"><a href="https://liberapay.com/bevry" title="Donate to this project using Liberapay"><img src="https://img.shields.io/badge/liberapay-donate-yellow.svg" alt="Liberapay donate button" /></a></span>
<span class="badge-buymeacoffee"><a href="https://buymeacoffee.com/balupton" title="Donate to this project using Buy Me A Coffee"><img src="https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg" alt="Buy Me A Coffee donate button" /></a></span>
<span class="badge-opencollective"><a href="https://opencollective.com/bevry" title="Donate to this project using Open Collective"><img src="https://img.shields.io/badge/open%20collective-donate-yellow.svg" alt="Open Collective donate button" /></a></span>
<span class="badge-crypto"><a href="https://bevry.me/crypto" title="Donate to this project using Cryptocurrency"><img src="https://img.shields.io/badge/crypto-donate-yellow.svg" alt="crypto donate button" /></a></span>
<span class="badge-paypal"><a href="https://bevry.me/paypal" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>
<br class="badge-separator" />
<span class="badge-discord"><a href="https://discord.gg/nQuXddV7VP" title="Join this project's community on Discord"><img src="https://img.shields.io/discord/1147436445783560193?logo=discord&amp;label=discord" alt="Discord server badge" /></a></span>
<span class="badge-twitch"><a href="https://www.twitch.tv/balupton" title="Join this project's community on Twitch"><img src="https://img.shields.io/twitch/status/balupton?logo=twitch" alt="Twitch community badge" /></a></span>

<!-- /BADGES -->

<!-- DESCRIPTION/ -->

A package that contains an array of every single file extension there is for text files

<!-- /DESCRIPTION -->


## Usage

[Complete API Documentation.](http://master.@diotoborg/eveniet-eaque-fugit.bevry.surge.sh/docs/)

```typescript
import list from '@diotoborg/eveniet-eaque-fugit'
console.log(list)
```

```javascript
const list = require('@diotoborg/eveniet-eaque-fugit').default
console.log(list)
```

JSON also available via `@diotoborg/eveniet-eaque-fugit/list.json`

CDN access available via https://unpkg.com/@diotoborg/eveniet-eaque-fugit/list.json

Missing an extension? [Send a pull request!](https://github.com/diotoborg/eveniet-eaque-fugit/edit/master/source/index.ts)

Want a definitive list of binary extensions? Check out [bevry/binaryextensions](https://github.com/bevry/binaryextensions)

Want to detect if a file is text or binary? Check out [bevry/istextorbinary](https://github.com/bevry/istextorbinary)

<!-- INSTALL/ -->

## Install

### [npm](https://npmjs.com "npm is a package manager for javascript")

-   Install: `npm install --save @diotoborg/eveniet-eaque-fugit`
-   Import: `import pkg from ('@diotoborg/eveniet-eaque-fugit')`
-   Require: `const pkg = require('@diotoborg/eveniet-eaque-fugit').default`

### [Deno](https://deno.land "Deno is a secure runtime for JavaScript and TypeScript, it is an alternative for Node.js")

``` typescript
import pkg from 'https://unpkg.com/@diotoborg/eveniet-eaque-fugit@^6.11.0/edition-deno/index.ts'
```
### [Skypack](https://www.skypack.dev "Skypack is a JavaScript Delivery Network for modern web apps")

``` html
<script type="module">
    import pkg from '//cdn.skypack.dev/@diotoborg/eveniet-eaque-fugit@^6.11.0'
</script>
```
### [unpkg](https://unpkg.com "unpkg is a fast, global content delivery network for everything on npm")

``` html
<script type="module">
    import pkg from '//unpkg.com/@diotoborg/eveniet-eaque-fugit@^6.11.0'
</script>
```
### [jspm](https://jspm.io "Native ES Modules CDN")

``` html
<script type="module">
    import pkg from '//dev.jspm.io/@diotoborg/eveniet-eaque-fugit@6.11.0'
</script>
```
### [Editions](https://editions.bevry.me "Editions are the best way to produce and consume packages you care about.")

This package is published with the following editions:
-   `@diotoborg/eveniet-eaque-fugit` aliases `@diotoborg/eveniet-eaque-fugit/index.cjs` which uses the [Editions Autoloader](https://github.com/bevry/editions "You can use the Editions Autoloader to autoload the appropriate edition for your consumers environment") to automatically select the correct edition for the consumer's environment
-   `@diotoborg/eveniet-eaque-fugit/source/index.ts` is [TypeScript](https://www.typescriptlang.org/ "TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.") source code with [Import](https://babeljs.io/docs/learn-es2015/#modules "ECMAScript Modules") for modules
-   `@diotoborg/eveniet-eaque-fugit/edition-browsers/index.js` is [TypeScript](https://www.typescriptlang.org/ "TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.") compiled against [ES2022](https://en.wikipedia.org/wiki/ES2022 "ECMAScript 2022") for web browsers with [Import](https://babeljs.io/docs/learn-es2015/#modules "ECMAScript Modules") for modules
-   `@diotoborg/eveniet-eaque-fugit/edition-es2022/index.js` is [TypeScript](https://www.typescriptlang.org/ "TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.") compiled against [ES2022](https://en.wikipedia.org/wiki/ES2022 "ECMAScript 2022") for [Node.js](https://nodejs.org "Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine") 6 || 8 || 10 || 12 || 14 || 16 || 18 || 20 || 21 with [Require](https://nodejs.org/dist/latest-v5.x/docs/api/modules.html "Node/CJS Modules") for modules
-   `@diotoborg/eveniet-eaque-fugit/edition-es5/index.js` is [TypeScript](https://www.typescriptlang.org/ "TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.") compiled against ES5 for [Node.js](https://nodejs.org "Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine") 4 || 6 || 8 || 10 || 12 || 14 || 16 || 18 || 20 || 21 with [Require](https://nodejs.org/dist/latest-v5.x/docs/api/modules.html "Node/CJS Modules") for modules
-   `@diotoborg/eveniet-eaque-fugit/edition-es2022-esm/index.js` is [TypeScript](https://www.typescriptlang.org/ "TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.") compiled against [ES2022](https://en.wikipedia.org/wiki/ES2022 "ECMAScript 2022") for [Node.js](https://nodejs.org "Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine") 12 || 14 || 16 || 18 || 20 || 21 with [Import](https://babeljs.io/docs/learn-es2015/#modules "ECMAScript Modules") for modules
-   `@diotoborg/eveniet-eaque-fugit/edition-types/index.d.ts` is [TypeScript](https://www.typescriptlang.org/ "TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.") compiled Types with [Import](https://babeljs.io/docs/learn-es2015/#modules "ECMAScript Modules") for modules
-   `@diotoborg/eveniet-eaque-fugit/edition-deno/index.ts` is [TypeScript](https://www.typescriptlang.org/ "TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.") source code made to be compatible with [Deno](https://deno.land "Deno is a secure runtime for JavaScript and TypeScript, it is an alternative to Node.js")

<!-- /INSTALL -->

<!-- HISTORY/ -->

## History

[Discover the release history by heading on over to the `HISTORY.md` file.](https://github.com/diotoborg/eveniet-eaque-fugit/blob/HEAD/HISTORY.md#files)

<!-- /HISTORY -->

<!-- BACKERS/ -->

## Backers

### Code

[Discover how to contribute via the `CONTRIBUTING.md` file.](https://github.com/diotoborg/eveniet-eaque-fugit/blob/HEAD/CONTRIBUTING.md#files)

#### Authors

-   [Benjamin Lupton](https://balupton.com) — Accelerating collaborative wisdom.

#### Maintainers

-   [Benjamin Lupton](https://balupton.com) — Accelerating collaborative wisdom.

#### Contributors

-   [Benjamin Lupton](https://github.com/balupton) — [view contributions](https://github.com/diotoborg/eveniet-eaque-fugit/commits?author=balupton "View the GitHub contributions of Benjamin Lupton on repository bevry/@diotoborg/eveniet-eaque-fugit")
-   [Brian Lukoff](https://github.com/brianlukoff) — [view contributions](https://github.com/diotoborg/eveniet-eaque-fugit/commits?author=brianlukoff "View the GitHub contributions of Brian Lukoff on repository bevry/@diotoborg/eveniet-eaque-fugit")
-   [Connor Chen](https://github.com/connorjchen) — [view contributions](https://github.com/diotoborg/eveniet-eaque-fugit/commits?author=connorjchen "View the GitHub contributions of Connor Chen on repository bevry/@diotoborg/eveniet-eaque-fugit")
-   [Felipe Beline](https://github.com/fbeline) — [view contributions](https://github.com/diotoborg/eveniet-eaque-fugit/commits?author=fbeline "View the GitHub contributions of Felipe Beline on repository bevry/@diotoborg/eveniet-eaque-fugit")
-   [Jamy Timmermans](https://github.com/JamyDev) — [view contributions](https://github.com/diotoborg/eveniet-eaque-fugit/commits?author=JamyDev "View the GitHub contributions of Jamy Timmermans on repository bevry/@diotoborg/eveniet-eaque-fugit")
-   [Jason Caldwell](https://github.com/jaswrks) — [view contributions](https://github.com/diotoborg/eveniet-eaque-fugit/commits?author=jaswrks "View the GitHub contributions of Jason Caldwell on repository bevry/@diotoborg/eveniet-eaque-fugit")
-   [Joshua Evans](https://github.com/TheJoshuaEvans) — [view contributions](https://github.com/diotoborg/eveniet-eaque-fugit/commits?author=TheJoshuaEvans "View the GitHub contributions of Joshua Evans on repository bevry/@diotoborg/eveniet-eaque-fugit")
-   [Kaan Barmore-Genç](https://github.com/SeriousBug) — [view contributions](https://github.com/diotoborg/eveniet-eaque-fugit/commits?author=SeriousBug "View the GitHub contributions of Kaan Barmore-Genç on repository bevry/@diotoborg/eveniet-eaque-fugit")
-   [LvChengbin](https://github.com/LvChengbin) — [view contributions](https://github.com/diotoborg/eveniet-eaque-fugit/commits?author=LvChengbin "View the GitHub contributions of LvChengbin on repository bevry/@diotoborg/eveniet-eaque-fugit")
-   [monsterkodi](https://github.com/monsterkodi) — [view contributions](https://github.com/diotoborg/eveniet-eaque-fugit/commits?author=monsterkodi "View the GitHub contributions of monsterkodi on repository bevry/@diotoborg/eveniet-eaque-fugit")

### Finances

<span class="badge-githubsponsors"><a href="https://github.com/sponsors/balupton" title="Donate to this project using GitHub Sponsors"><img src="https://img.shields.io/badge/github-donate-yellow.svg" alt="GitHub Sponsors donate button" /></a></span>
<span class="badge-thanksdev"><a href="https://thanks.dev/u/gh/bevry" title="Donate to this project using ThanksDev"><img src="https://img.shields.io/badge/thanksdev-donate-yellow.svg" alt="ThanksDev donate button" /></a></span>
<span class="badge-patreon"><a href="https://patreon.com/bevry" title="Donate to this project using Patreon"><img src="https://img.shields.io/badge/patreon-donate-yellow.svg" alt="Patreon donate button" /></a></span>
<span class="badge-liberapay"><a href="https://liberapay.com/bevry" title="Donate to this project using Liberapay"><img src="https://img.shields.io/badge/liberapay-donate-yellow.svg" alt="Liberapay donate button" /></a></span>
<span class="badge-buymeacoffee"><a href="https://buymeacoffee.com/balupton" title="Donate to this project using Buy Me A Coffee"><img src="https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg" alt="Buy Me A Coffee donate button" /></a></span>
<span class="badge-opencollective"><a href="https://opencollective.com/bevry" title="Donate to this project using Open Collective"><img src="https://img.shields.io/badge/open%20collective-donate-yellow.svg" alt="Open Collective donate button" /></a></span>
<span class="badge-crypto"><a href="https://bevry.me/crypto" title="Donate to this project using Cryptocurrency"><img src="https://img.shields.io/badge/crypto-donate-yellow.svg" alt="crypto donate button" /></a></span>
<span class="badge-paypal"><a href="https://bevry.me/paypal" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>

#### Sponsors

-   [Andrew Nesbitt](https://nesbitt.io) — Software engineer and researcher
-   [Balsa](https://balsa.com) — We're Balsa, and we're building tools for builders.
-   [Codecov](https://codecov.io) — Empower developers with tools to improve code quality and testing.
-   [Poonacha Medappa](https://poonachamedappa.com)
-   [Rob Morris](https://github.com/Rob-Morris)
-   [Sentry](https://sentry.io) — Real-time crash reporting for your web apps, mobile apps, and games.
-   [Syntax](https://syntax.fm) — Syntax Podcast

#### Donors

-   [Andrew Nesbitt](https://nesbitt.io)
-   [Armen Mkrtchian](https://mogoni.dev)
-   [Balsa](https://balsa.com)
-   [Chad](https://opencollective.com/chad8)
-   [Codecov](https://codecov.io)
-   [dr.dimitru](https://veliovgroup.com)
-   [Elliott Ditman](https://elliottditman.com)
-   [entroniq](https://gitlab.com/entroniq)
-   [GitHub](https://github.com/about)
-   [Hunter Beast](https://cryptoquick.com)
-   [Jean-Luc Geering](https://github.com/jlgeering)
-   [Michael Duane Mooring](https://mdm.cc)
-   [Michael Harry Scepaniak](https://michaelscepaniak.com)
-   [Mohammed Shah](https://github.com/smashah)
-   [Mr. Henry](https://mrhenry.be)
-   [Nermal](https://arjunaditya.vercel.app)
-   [Pleo](https://pleo.io)
-   [Poonacha Medappa](https://poonachamedappa.com)
-   [Rob Morris](https://github.com/Rob-Morris)
-   [Robert de Forest](https://github.com/rdeforest)
-   [Sentry](https://sentry.io)
-   [ServieJS](https://github.com/serviejs)
-   [Skunk Team](https://skunk.team)
-   [Syntax](https://syntax.fm)
-   [WriterJohnBuck](https://github.com/WriterJohnBuck)

<!-- /BACKERS -->

<!-- LICENSE/ -->

## License

Unless stated otherwise all works are:

-   Copyright &copy; [Benjamin Lupton](https://balupton.com)

and licensed under:

-   [Artistic License 2.0](http://spdx.org/licenses/Artistic-2.0.html)

<!-- /LICENSE -->
