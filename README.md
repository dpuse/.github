# DPUse (.github)

Documents the common concepts, standards, and practices shared across DPUse projects. This is a special GitHub organization-level repository.

## Repositories Schematic

This schematic presents a high-level view of the repositories in the DPUse project and their relationships to one another.

![Data Positioning Repositories Schematic](Repositories%20Schematic.svg 'Data Positioning Project Repositories')

### Development Repositories

The following repositories exist solely to support the development process and are not used in production or distributed in any form.

| Name                | Type             | Notes                                                                       |
| ------------------- | ---------------- | --------------------------------------------------------------------------- |
| dpuse-development   | utilities (node) | A library of utilities for managing the Data Positioning repositories.      |
| eslint-config-dpuse | eslintConfig     | Base ESLint configuration used by all Data Positioning (@datapos) projects. |

### Production Repositories

The following repositories contain production-ready code and are used in live environments and/or distributed as part of the final product.

| Name                                 | Visibility | Type       | Notes                                                                                          |
| ------------------------------------ | ---------- | ---------- | ---------------------------------------------------------------------------------------------- |
| dpuse-api                            | private    | api        |                                                                                                |
| dpuse-app                            | private    | app        |                                                                                                |
| dpuse-engine                         | private    | engine     |                                                                                                |
| dpuse-resources                      | private    | assets     |                                                                                                |
| dpuse-shared                         | public     | primitives | Common constants, interfaces, types and utilities shared across all Data Positioning projects. |
| dpuse-connector-application-emulator | public     | connector  |                                                                                                |
| dpuse-connector-dexie-js             | public     | connector  |                                                                                                |
| dpuse-connector-file-store-emulator  | public     | connector  |                                                                                                |
| dpuse-connector-rxdb                 | public     | connector  |                                                                                                |
| dpuse-context-default                | public     | context    |                                                                                                |
| dpuse-presenter-default              | public     | presenter  |                                                                                                |
| dpuse-tool-highcharts                | public     | tool       |                                                                                                |
| dpuse-tool-presenter                 | public     | tool       |                                                                                                |

## Software, Services & Tools

The following services are used to support the production environment.

| Name                                      | License    | Notes                                                                       |
| ----------------------------------------- | ---------- | --------------------------------------------------------------------------- |
| [Checkly](https://www.checklyhq.com/)     | Commercial | Response time monitoring. Uptime & heartbeat monitoring.                    |
| [Cloudflare](https://www.cloudflare.com/) | Commercial | Domain registration, application hosting, file storage and state messaging. |
| [Cronitor](https://cronitor.io/)          | Commercial | Uptime & heartbeat monitoring.                                              |
| [Hanko](https://www.hanko.io/)            | Commercial | Authentication and user management.                                         |

The following services and tools are used to support the development environment.

| Name                                         | License    | Notes                                 |
| -------------------------------------------- | ---------- | ------------------------------------- |
| [1Password](https://1password.com/)          | Commercial |                                       |
| [BadgeApp](https://www.bestpractices.dev/en) |            | OpenSSF best practices badge program. |
| [Boxy SVG Editor](https://boxy-svg.com/)     | Commercial | SVG image editor.                     |
| [Draw.io](https://drawio-app.com/)           |            |                                       |
| [git](<>)                                    |            |                                       |
| [GitGuardian](https://www.gitguardian.com/)  |            | Security management.                  |
| [GitHub](https://github.com/home)            |            | Source code management.               |
| [Copilot](<>)                                | Commercial |                                       |
| [node](<>)                                   |            |                                       |
| [npm](https://www.npmjs.com/)                |            | Package deployment                    |
| [Shields.io](https://shields.io/)            |            | Badges.                               |
| [Tolgee](https://tolgee.io/)                 |            | Language translation.                 |
| [VS Code](<>)                                |            |                                       |

The following dependencies...

| Product/Vendor                                       |                                   | License | Notes                                                |
| ---------------------------------------------------- | --------------------------------- | ------- | ---------------------------------------------------- |
| [Blockly](<(https://developers.google.com/blockly)>) | blockly visual programming editor |         |                                                      |
| [Cytoscape.js](https://js.cytoscape.org/)            |                                   |         |                                                      |
| [Hanko](<>)                                          | hanko frontend sdk                |         | [@teamhanko/hanko-frontend-sdk](<>)                  |
| [Micromark](<>)                                      | micromark parser                  |         | [micromark](https://www.npmjs.com/package/micromark) |
|                                                      | micromark gfm table extension     |         | [micromark-extension-gfm-table ](<>)                 |
| [Nanoid](<>)                                         | nanoid                            |         | [nanoid](<>)                                         |
| [Vue](<>)                                            | vue                               |         | [vue](<>)                                            |
|                                                      | vue pinia                         |         | [pinia](<>)                                          |
|                                                      | vue router                        |         | [vue-router](<>)                                     |
| [Speed Highlight](<>)                                | @speed highlight core             |         | [@speed-highlight/core ](<>)                         |
| [TanStack Virtual](<>)                               | tanstack vue virtual              |         | [@tanstack/vue-virtual](<>)                          |

The following dependencies...

| Product/Vendor                |                               | License | Notes                                                                                                                                 |
| ----------------------------- | ----------------------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| [ESLint](<>)                  | eslint                        |         | [eslint](https://eslint.org/)                                                                                                         |
|                               | eslint nuxt                   |         | [@nuxt/eslint](<>)                                                                                                                    |
|                               | eslint typescript parser      |         | [@typescript-eslint/parser](https://www.npmjs.com/package/@typescript-eslint/parser)                                                  |
|                               | eslint typescript plugin      |         | [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin)                                    |
|                               | eslint config datapos         |         | [eslint-datapos-import](https://www.npmjs.com/package/@datapos/eslint-config-datapos)                                                 |
|                               | eslint plugin import          |         | [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)                                                            |
|                               | eslint plugin security        |         | [eslint-plugin-security](https://www.npmjs.com/package/eslint-plugin-security),                                                       |
|                               | eslint plugin security types  |         | [@types/eslint-plugin-security](https://www.npmjs.com/package/@types/eslint-plugin-security)                                          |
|                               | eslint plugin sonarjs         |         | [eslint-plugin-sonarjs](https://www.npmjs.com/package/eslint-plugin-sonarjs)                                                          |
|                               | eslint plugin unicorn         |         | [eslint-plugin-unicorn](https://www.npmjs.com/package/eslint-plugin-unicorn)                                                          |
| [Icônes](<>)                  | Lucide                        |         | [Lucide by Lucide Contributors](https://icones.js.org/collection/lucide)                                                              |
|                               | Pictogrammers                 |         | [Material Design Icons by Pictogrammers](https://icones.js.org/collection/mdi)                                                        |
|                               | Streamline                    |         | [Ultimate Free Icons by Streamline](https://icones.js.org/collection/streamline-ultimate)                                             |
| [jiti](<>)                    | jiti                          |         | [jiti](<>)                                                                                                                            |
| [License Report](<>)          | license report                |         | [license-report](<>)                                                                                                                  |
|                               | license report check          |         | [license-report-check](<>)                                                                                                            |
|                               | license report recursive      |         | [license-report-recursive](<>)                                                                                                        |
| [Nanoid](<>)                  | nanoid                        |         | [nanoid](<>)                                                                                                                          |
| [Node](<>)                    | node types                    |         | [@types/node](<>)                                                                                                                     |
| [npm](<>)                     | npm check updates             |         | [npm-check-updates](npm-check-updates)                                                                                                |
| [Nuxt](<>)                    | nuxt test utils               |         | [@nuxt/test-utils](<>)                                                                                                                |
| [OWASP Dependency Check](<>)  | owasp dependency check        |         | [owasp-dependency-check](<>)                                                                                                          |
| [Playwright](<>)              | playwright                    |         | [playwright](<>)]                                                                                                                     |
| [Prettier](<>)                | prettier                      |         | [prettier](https://prettier.io/)]                                                                                                     |
|                               | prettier tailwind plugin      |         | [prettier-plugin-tailwindcss](<>)                                                                                                     |
| [Rust](<>)                    |                               |         |                                                                                                                                       |
| [Tailwind](<>)                |                               |         | ?Where is this being referenced from? Would be could to include for doco purposes even if nuxt/ui or something else is installing it. |
| [TypeScript](<>) (JavaScript) | typescript                    |         |                                                                                                                                       |
|                               | type fest                     |         | [type-fest](https://www.npmjs.com/package/type-fest)                                                                                  |
| [Vite](<>)                    | vite                          |         | [vite](https://vite.dev/)                                                                                                             |
|                               | vite dts plugin               |         | [vite-plugin-dts](https://www.npmjs.com/package/vite-plugin-dts)                                                                      |
|                               | vite pwa assets generator     |         | [@vite-pwa/assets-generator](<>)                                                                                                      |
|                               | vite visualizer rollup plugin |         | [rollup-plugin-visualizer](<>)                                                                                                        |
| [Valibot](<>)                 | valibot                       |         | [valibot](<>)                                                                                                                         |
| [Vitest](<>)                  | vitest                        |         | [vitest](https://vitest.dev/)                                                                                                         |
| [Wrangler](<>)                | wrangler                      |         | See datapos-api & datapos-app-nuxt.                                                                                                   |

## Tasks

[Configure Development Computer](<./documents/Configure Laptop.md>)
