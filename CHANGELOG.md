# Changelog

All notable changes to this project will be documented in this file. See [commit-and-tag-version](https://github.com/absolute-version/commit-and-tag-version) for commit guidelines.

## 1.9.0 (2026-10-09)


### Features

* add About modal and version tracking functionality ([49ef556](https://github.com/bocan/codex/commit/49ef5561d2074065c1680969c1549496478fd106))
* add favicon SVG with gradient and design elements ([74a86d3](https://github.com/bocan/codex/commit/74a86d3e2f051a69b80f7b6deec10802a5f3a6e4))
* add Link Checker tool for scanning page links and HTTP status codes ([7360592](https://github.com/bocan/codex/commit/736059256f11ea28cc6a802ae62217acd2eac410))
* add Log Cleaner tool for Azure DevOps / GitHub Actions raw logs ([2fc3807](https://github.com/bocan/codex/commit/2fc38072f34600ab131668cc9e15d29a49d9f7d4))
* add Lorem Generator, Timestamp Converter, and UUID Generator tools with respective styles and functionalities ([2fe0e17](https://github.com/bocan/codex/commit/2fe0e17271c737c382b59581dc95759b1be16c93))
* add lucide-react icons and update dependencies ([3b00eb9](https://github.com/bocan/codex/commit/3b00eb94696a228db7df0f56672a1b6052729718))
* add Network Calculator tool ([c3fd5ff](https://github.com/bocan/codex/commit/c3fd5fff71b4dbabe573da31968a2e4548bc178f))
* add OG and Twitter card meta tags with optimised social preview image ([969324f](https://github.com/bocan/codex/commit/969324fd51f559ae7cb95f078fcc0c9a2d0e22e0))
* add version configuration file with commit and compare URL formats ([d1e84c4](https://github.com/bocan/codex/commit/d1e84c4fdbd111afb43a2db5aa34afe7aeb96e70))
* **beautify:** proper XML/RSS formatting via @prettier/plugin-xml ([c2e83b4](https://github.com/bocan/codex/commit/c2e83b4de1af4682b7ef825e430e9bd7c887e5a0))
* **links:** distinguish CORS-hidden links from genuinely dead ones ([6788326](https://github.com/bocan/codex/commit/6788326c88198a3f3a3e0921d0c8fdd34ab0a4a3))


### Bug Fixes

* copy index.html to 404.html at build time for GitHub Pages SPA routing ([2d58aed](https://github.com/bocan/codex/commit/2d58aed402abbfd60b04f45505a1b7b6059c70b9))
* correct syntax errors in GitHub Actions workflow configuration ([4414025](https://github.com/bocan/codex/commit/441402571a8bd1915ff7d1090b8b826becb34ecd))
* **links:** update progress counter to renamed unknown count ([22aba86](https://github.com/bocan/codex/commit/22aba86fe2f240e7e8065bd716e5676cc9a6dee8))
* replace control-char regex with string.includes to fix no-control-regex lint ([f11aa8a](https://github.com/bocan/codex/commit/f11aa8afab303e13b12efdd628bf176de773571a))
* update footer to include link to GitHub repository ([63d9e1b](https://github.com/bocan/codex/commit/63d9e1be17d0f3fd01d2cf1ea5af93fdfdcca2a7))
* update GitHub Actions workflow for improved CI/CD process and version bumping ([7c53368](https://github.com/bocan/codex/commit/7c53368eba36e032af2b23f7ae4699c8dded955d))
* update GitHub Actions workflow to streamline deployment process and improve version handling ([eb89b26](https://github.com/bocan/codex/commit/eb89b26e773e63207346177f8050cb49c74ec3c1))


### Code Refactoring

* standardize quotation marks in eslint configuration ([93ff605](https://github.com/bocan/codex/commit/93ff605f765dfe47dcea25f76dc8204f53b5677e))


### Documentation

* update README with new features and usage instructions ([a4effb9](https://github.com/bocan/codex/commit/a4effb9124ce7dd2859c02486c7533a2d88bda6a))


### Styles

* enhance footer links with underline and color changes on hover ([bc94bae](https://github.com/bocan/codex/commit/bc94bae8cc5853e4ead06b8357017ea406c4da70))


### Chores

* add CLAUDE.md ([78e65cc](https://github.com/bocan/codex/commit/78e65cc531141f88cea038b190dd6dac2a54c54a))
* add dependabot config to enable automated PRs ([c132f2b](https://github.com/bocan/codex/commit/c132f2ba2686b9bfef67301e874c20b84d210cde))
* add release script and update dependencies in package.json ([2035802](https://github.com/bocan/codex/commit/20358022020d6daf3709485435954214deee0379))
* bump dependencies versions ([37890b8](https://github.com/bocan/codex/commit/37890b8f6cb8d2abdffc3c0c03bb6081e90d8b71))
* **deps-dev:** bump @vitejs/plugin-react from 5.2.0 to 6.0.2 ([72bdc4d](https://github.com/bocan/codex/commit/72bdc4d6224cac38fd322e433e9e85c813e52c51))
* **deps-dev:** bump jsdom from 28.1.0 to 29.1.1 ([fd7e5b2](https://github.com/bocan/codex/commit/fd7e5b238a8c0b3f46f5f25286c2a4da5589636d))
* **deps-dev:** bump typescript from 5.9.3 to 6.0.3 ([5411c2a](https://github.com/bocan/codex/commit/5411c2a68b961774cb1b8c75c8de030b97c03b43))
* **deps-dev:** bump vite from 7.3.3 to 8.0.14 ([783f01e](https://github.com/bocan/codex/commit/783f01e468af2b78fd4c971ae27931f689e50080))
* **deps:** bump lucide-react from 0.577.0 to 1.16.0 ([f0eea31](https://github.com/bocan/codex/commit/f0eea3184f3deda07ef7e823cf599a70813bb901))
* fix 19 dependabot security alerts via npm audit fix ([fffef64](https://github.com/bocan/codex/commit/fffef648a7bf0bd0f4f872ce1565ce1bbd4e23d8))
* **release:** 1.0.2 ([0a0d29a](https://github.com/bocan/codex/commit/0a0d29a1a6ba32b5803282e7bf2b8b2604a608a8))
* **release:** 1.1.0 ([597a993](https://github.com/bocan/codex/commit/597a993c74b6ab8500f1a16c705f1a5a0a81807e))
* **release:** 1.2.0 ([72d9ec9](https://github.com/bocan/codex/commit/72d9ec93845507db980815228065953a630a33c1))
* **release:** 1.3.0 ([41cef1d](https://github.com/bocan/codex/commit/41cef1d1dba62f17310ae61c92242934ff9e39a7))
* **release:** 1.3.1 ([adf57b8](https://github.com/bocan/codex/commit/adf57b8bbeb21150da7ec01613f6ad33e24bfcdb))
* **release:** 1.3.2 ([6e65a6b](https://github.com/bocan/codex/commit/6e65a6b951e556d3ad6e4fe8d4a48cc59a1742b6))
* **release:** 1.4.0 ([1c6292e](https://github.com/bocan/codex/commit/1c6292e64cdc3c4e4151a4771f26d060c67ac3dc))
* **release:** 1.4.1 ([fbeec01](https://github.com/bocan/codex/commit/fbeec01400d208feecbf6870aaf3c979e742f879))
* **release:** 1.4.2 ([5633b93](https://github.com/bocan/codex/commit/5633b933b203afde14e4a1504644f6c103e16aa9))
* **release:** 1.5.0 ([c84d6ae](https://github.com/bocan/codex/commit/c84d6ae930131190d3412e99642ce1ae700a6b6c))
* **release:** 1.6.0 ([4fcb1e2](https://github.com/bocan/codex/commit/4fcb1e2752334816e92c2c5f5432e6027bc645bc))
* **release:** 1.7.0 ([df9b5fc](https://github.com/bocan/codex/commit/df9b5fc201ae5af6dc0f15c61786e2ee63c8a29b))
* **release:** 1.7.1 ([51c8f21](https://github.com/bocan/codex/commit/51c8f215bd4a88a606b63c2fa41ac84864473874))
* **release:** 1.8.0 ([0c65acd](https://github.com/bocan/codex/commit/0c65acdf941155678a0282e2658c7a98f24bcd5a))
* **release:** 1.8.1 ([ee43a59](https://github.com/bocan/codex/commit/ee43a593a8cb040ec94d7b0f6b241f7df2c6ef0e))
* update CI workflow and enhance README with project details and screenshot ([e4572e8](https://github.com/bocan/codex/commit/e4572e8f2e88cde423f45570db31dcc031c31f6d))
* update dependencies ([117d6d6](https://github.com/bocan/codex/commit/117d6d605a1e3eee3721b152050183db39c98989))
* update dependencies and add release script ([6ad88ed](https://github.com/bocan/codex/commit/6ad88ed315727e17c470a4385c082c741ea14815))
* update eslint version to ^10.0.3 in package-lock.json ([59230af](https://github.com/bocan/codex/commit/59230af2b924cdf283d99de6b45ff87fed6d5aba))
* update eslint version to ^10.0.3 in package.json ([346f7e7](https://github.com/bocan/codex/commit/346f7e70f0d067fed0e34354c9b81148bb7fc040))
* update GitHub Actions to use latest versions of checkout and setup-node ([681704b](https://github.com/bocan/codex/commit/681704bc2411a0b6d19c07e88c7b5b22226e6a35))


### CI/CD

* fix paths-ignore and add workflow_dispatch ([1545114](https://github.com/bocan/codex/commit/1545114464d6043c3a4338a778e12c578e9f24dd))
* update GitHub Actions to latest versions ([2f37b7a](https://github.com/bocan/codex/commit/2f37b7aee7571cc464a74536b7516560381a7b17))

## [1.8.1](https://github.com/bocan/codex/compare/v1.8.0...v1.8.1) (2026-06-18)


### Chores

* update dependencies ([117d6d6](https://github.com/bocan/codex/commit/117d6d605a1e3eee3721b152050183db39c98989))

## [1.8.0](https://github.com/bocan/codex/compare/v1.7.1...v1.8.0) (2026-06-18)


### Features

* **beautify:** proper XML/RSS formatting via @prettier/plugin-xml ([c2e83b4](https://github.com/bocan/codex/commit/c2e83b4de1af4682b7ef825e430e9bd7c887e5a0))

## [1.7.1](https://github.com/bocan/codex/compare/v1.7.0...v1.7.1) (2026-06-11)


### Chores

* add CLAUDE.md ([78e65cc](https://github.com/bocan/codex/commit/78e65cc531141f88cea038b190dd6dac2a54c54a))

## [1.7.0](https://github.com/bocan/codex/compare/v1.6.0...v1.7.0) (2026-06-11)


### Features

* **links:** distinguish CORS-hidden links from genuinely dead ones ([6788326](https://github.com/bocan/codex/commit/6788326c88198a3f3a3e0921d0c8fdd34ab0a4a3))


### Bug Fixes

* **links:** update progress counter to renamed unknown count ([22aba86](https://github.com/bocan/codex/commit/22aba86fe2f240e7e8065bd716e5676cc9a6dee8))

## [1.6.0](https://github.com/bocan/codex/compare/v1.5.0...v1.6.0) (2026-06-11)


### Features

* add Link Checker tool for scanning page links and HTTP status codes ([7360592](https://github.com/bocan/codex/commit/736059256f11ea28cc6a802ae62217acd2eac410))

## [1.5.0](https://github.com/bocan/codex/compare/v1.4.2...v1.5.0) (2026-05-28)


### Features

* add OG and Twitter card meta tags with optimised social preview image ([969324f](https://github.com/bocan/codex/commit/969324fd51f559ae7cb95f078fcc0c9a2d0e22e0))

## [1.4.2](https://github.com/bocan/codex/compare/v1.4.1...v1.4.2) (2026-05-28)


### Bug Fixes

* copy index.html to 404.html at build time for GitHub Pages SPA routing ([2d58aed](https://github.com/bocan/codex/commit/2d58aed402abbfd60b04f45505a1b7b6059c70b9))


### CI/CD

* fix paths-ignore and add workflow_dispatch ([1545114](https://github.com/bocan/codex/commit/1545114464d6043c3a4338a778e12c578e9f24dd))

## [1.4.1](https://github.com/bocan/codex/compare/v1.4.0...v1.4.1) (2026-05-28)


### CI/CD

* update GitHub Actions to latest versions ([2f37b7a](https://github.com/bocan/codex/commit/2f37b7aee7571cc464a74536b7516560381a7b17))

## [1.4.0](https://github.com/bocan/codex/compare/v1.3.2...v1.4.0) (2026-05-28)


### Features

* add Log Cleaner tool for Azure DevOps / GitHub Actions raw logs ([2fc3807](https://github.com/bocan/codex/commit/2fc38072f34600ab131668cc9e15d29a49d9f7d4))


### Bug Fixes

* replace control-char regex with string.includes to fix no-control-regex lint ([f11aa8a](https://github.com/bocan/codex/commit/f11aa8afab303e13b12efdd628bf176de773571a))

## [1.3.2](https://github.com/bocan/codex/compare/v1.3.1...v1.3.2) (2026-05-27)


### Chores

* **deps-dev:** bump @vitejs/plugin-react from 5.2.0 to 6.0.2 ([72bdc4d](https://github.com/bocan/codex/commit/72bdc4d6224cac38fd322e433e9e85c813e52c51))
* **deps-dev:** bump jsdom from 28.1.0 to 29.1.1 ([fd7e5b2](https://github.com/bocan/codex/commit/fd7e5b238a8c0b3f46f5f25286c2a4da5589636d))
* **deps-dev:** bump typescript from 5.9.3 to 6.0.3 ([5411c2a](https://github.com/bocan/codex/commit/5411c2a68b961774cb1b8c75c8de030b97c03b43))
* **deps-dev:** bump vite from 7.3.3 to 8.0.14 ([783f01e](https://github.com/bocan/codex/commit/783f01e468af2b78fd4c971ae27931f689e50080))
* **deps:** bump lucide-react from 0.577.0 to 1.16.0 ([f0eea31](https://github.com/bocan/codex/commit/f0eea3184f3deda07ef7e823cf599a70813bb901))

## [1.3.1](https://github.com/bocan/codex/compare/v1.3.0...v1.3.1) (2026-05-27)


### Chores

* add dependabot config to enable automated PRs ([c132f2b](https://github.com/bocan/codex/commit/c132f2ba2686b9bfef67301e874c20b84d210cde))
* bump dependencies versions ([37890b8](https://github.com/bocan/codex/commit/37890b8f6cb8d2abdffc3c0c03bb6081e90d8b71))

## [1.3.0](https://github.com/bocan/codex/compare/v1.2.0...v1.3.0) (2026-05-27)


### Features

* add Network Calculator tool ([c3fd5ff](https://github.com/bocan/codex/commit/c3fd5fff71b4dbabe573da31968a2e4548bc178f))


### Chores

* fix 19 dependabot security alerts via npm audit fix ([fffef64](https://github.com/bocan/codex/commit/fffef648a7bf0bd0f4f872ce1565ce1bbd4e23d8))

## [1.2.0](https://github.com/bocan/codex/compare/v1.1.0...v1.2.0) (2026-03-09)


### Features

* add About modal and version tracking functionality ([49ef556](https://github.com/bocan/codex/commit/49ef5561d2074065c1680969c1549496478fd106))

## [1.1.0](https://github.com/bocan/codex/compare/v1.0.2...v1.1.0) (2026-03-09)


### Features

* add version configuration file with commit and compare URL formats ([d1e84c4](https://github.com/bocan/codex/commit/d1e84c4fdbd111afb43a2db5aa34afe7aeb96e70))

## [1.0.2](https://github.com/bocan/ultraformat/compare/v1.0.1...v1.0.2) (2026-03-09)

### Features

* add version tracking and release scripts
