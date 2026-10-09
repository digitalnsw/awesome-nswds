# Awesome NSW Government Digital [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Design systems, components and tooling for building New South Wales Government digital products.

The design systems NSW agencies publish, the packages, templates and Figma libraries behind them, and the tools that help designers, developers and content designers put them to work.

Does your agency have a design system, kit or tool that isn't here? [Suggest it](https://github.com/digitalnsw/awesome-nswds/issues/new?template=suggest-a-resource.yml).

## Contents

- [Design Systems](#design-systems)
- [Starter Kits and Templates](#starter-kits-and-templates)
- [Figma and Prototyping](#figma-and-prototyping)
- [Icons and Brand Assets](#icons-and-brand-assets)
- [Typography](#typography)
- [Email](#email)
- [Content Design](#content-design)
- [Accessibility Tools](#accessibility-tools)
- [Data Visualisation](#data-visualisation)
- [CMS and Framework Integrations](#cms-and-framework-integrations)
- [Developer Tools](#developer-tools)
- [Platforms and APIs](#platforms-and-apis)
- [Guidance](#guidance)

## Design Systems

- [NSW Design System](https://designsystem.nsw.gov.au/) - Whole-of-government styles, components and patterns for NSW digital services.
  - [Source Code](https://github.com/NSWGTP/nsw-design-system) - Sass and JavaScript source, issues and releases.
  - [nsw-design-system](https://www.npmjs.com/package/nsw-design-system) - npm package of the Sass source and compiled CSS and JavaScript.
  - [Theming](https://designsystem.nsw.gov.au/get-started/theming.html) - Applying NSW Government colour themes to the design system.
- [@nswds/ui](https://github.com/digitalnsw/nswds-ui) - React component library and shadcn registry for NSW Government applications, from Digital NSW.
  - [@nswds/tokens](https://github.com/digitalnsw/nswds-tokens) - Colour, spacing and typography tokens for CSS, Sass, JavaScript, Tailwind, Figma and DTCG.
- [NSW Education Application Design System](https://designsystem.education.nsw.gov.au/) - Vue 3 and TypeScript components for NSW Department of Education apps (ADS 3).
  - [@nswdoe/doe-ui-core-v3](https://www.npmjs.com/package/@nswdoe/doe-ui-core-v3) - npm package of the ADS 3 component library.
  - [ADS for Vue 2](https://designsystem.dev.education.nsw.gov.au/) - Documentation for the earlier Vue 2 and Vuetify release.
  - [@nswdoe/doe-ui-core](https://www.npmjs.com/package/@nswdoe/doe-ui-core) - npm package of the Vue 2 and Vuetify component library.
- [DCJ Digital Design System](https://designsystem.dcj.nsw.gov.au/) - Department of Communities and Justice components and guidance built on the NSW Design System.
- [Service NSW GEL](https://gel.service.nsw.gov.au/) - Service NSW's design system documentation. Requires a sign-in.

## Starter Kits and Templates

- [NSW Design System HTML Starter Kit](https://github.com/NSWGTP/nsw-design-system/blob/master/HTMLstarterkit.zip) - Compiled design system assets for projects that don't use npm.
- [NSW Design System Templates](https://designsystem.nsw.gov.au/get-started/templates.html) - Page layouts for homepages, articles, forms, search, maps, landing pages and theming.
- [DCJ Templates](https://designsystem.dcj.nsw.gov.au/content/dcj/design-system/design-system-home/templates.html) - Homepage, campaign, landing, content and Easy Read page templates.
- [ADS 3 Template Project](https://designsystem.education.nsw.gov.au/#/specification/template) - Vue 3, Vuetify 3 and TypeScript starter for Education apps, with linting and icons preconfigured. The repository is internal to the department.

## Figma and Prototyping

- [NSW Design System Figma UI Kit](https://www.figma.com/design/PVrERKnckLTlJSPk12gbtS/NSW-Design-System) - Official Figma file of components and styles. Viewing it requires a free Figma account.
- [ADS Figma Library](https://www.figma.com/community/file/1008913654223541218/nsw-doe-application-design-system) - Community Figma file of NSW Education Application Design System components.
- [nsw-design-system Skill](https://github.com/digitalnsw/nswds-skills/tree/main/skills/nsw-design-system) - AI coding agent skill for building prototypes and pages with only NSW Design System components.

## Icons and Brand Assets

- [NSW Government Brand Toolbox](https://branding.nsw.gov.au/) - NSW Government visual identity system and brand guidelines for each brand classification. Requires a sign-in.
- [Material Icons](https://fonts.google.com/icons?icon.set=Material+Icons) - Filled icon set used by the NSW Design System.
- [@nswdoe/app-icons](https://www.npmjs.com/package/@nswdoe/app-icons) - Application icons and colours for NSW Department of Education apps.

## Typography

- [Public Sans](https://public-sans.digital.nsw.gov.au/) - Downloads and usage guidance for the NSW Government masterbrand typeface.
- [@fontsource/public-sans](https://www.npmjs.com/package/@fontsource/public-sans) - Self-hosted Public Sans as an npm package, as recommended by the NSW Design System.

## Email

- [NSW Email Toolkit](https://email.digital.nsw.gov.au/) - Templates, components, standards and guidance for accessible, on-brand government email.

## Content Design

- [Australian Government Style Manual](https://www.stylemanual.gov.au/) - Standard for Australian Government writing and editing.
- [Content Style Guide](https://digital.nsw.gov.au/delivery/digital-service-toolkit/resources-and-guides/writing-content/content-style-guide) - Digital NSW conventions for grammar, punctuation, approved terms and interface text.
- [Easy Read](https://designsystem.nsw.gov.au/methods/easy-read.html) - NSW Design System method for producing Easy Read content.
- [australian-style-manual Skill](https://github.com/digitalnsw/nswds-skills/tree/main/skills/australian-style-manual) - AI agent skill that reviews and edits content against the Style Manual.
- [Creating Accessible Documents](https://digitalnsw.github.io/creating-accessible-documents/) - Self-paced Digital NSW course on making documents everyone can use.

## Accessibility Tools

- [Accessibility Testing Guide](https://digital.nsw.gov.au/delivery/accessibility-and-inclusivity-toolkit/testing/accessibility-testing) - Digital NSW process for automated, manual and screen reader testing, and for prioritising issues.
- [Accessibility Insights for Web](https://accessibilityinsights.io/docs/web/overview/) - Browser extension for automated checks and guided manual assessments.
- [WAVE](https://wave.webaim.org/) - Visual evaluation of a page's accessibility issues.
- [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview) - Automated accessibility, performance and quality audits built into Chrome.
- [NVDA](https://www.nvaccess.org/download/) - Free Windows screen reader for testing.
- [wcag-technical-audit Skill](https://github.com/digitalnsw/nswds-skills/tree/main/skills/wcag-technical-audit) - AI agent skill for evidence-based WCAG audits of pages and user journeys.

## Data Visualisation

- [Charts and Graphs](https://designsystem.nsw.gov.au/methods/charts-and-graphs.html) - NSW Design System method for accessible, on-brand charts.
- [nswtheme](https://digitalnsw.github.io/nswtheme/) - R package for charts and tables in NSW Government colours and typography.
- [doestyle](https://nsw-education.github.io/doestyle/) - R package for brand-compliant charts and tables in NSW Department of Education publications.

## CMS and Framework Integrations

- [Waratah](https://github.com/nswdpc/waratah) - NSW Design System theme for Silverstripe CMS.
- [nsw-design-system-plone6](https://github.com/pretagov/nsw-design-system-plone6) - NSW Design System add-on for Plone 6 Volto sites.
- [ds-nsw](https://packagist.org/packages/previousnext/ds-nsw) - PHP component library implementing the NSW Design System for PreviousNext's Interchangeable Design System.
- [Laravel NSW Components](https://github.com/SCHN-Developers/laravel-nsw-components) - Laravel Blade components for the NSW Design System.

## Developer Tools

- [nswds-skills](https://github.com/digitalnsw/nswds-skills) - AI coding agent skills for NSW Government delivery, from design system builds to dependency and pull request review.
- [@nswds/eslint-config](https://github.com/digitalnsw/nswds-eslint-config) - Shared ESLint flat config for Next.js and framework-free projects.
- [@nswds/prettier-config](https://github.com/digitalnsw/nswds-prettier-config) - Shared Prettier configuration.
- [@nswds/metadata](https://github.com/digitalnsw/nswds-metadata) - Shared Next.js App Router metadata, viewport and web app manifest.

## Platforms and APIs

- [NSW Point](https://point.digital.nsw.gov.au/v3/docs/index.html) - APIs for validating and enriching addresses, coordinates, cadastral parcels and properties. Agencies apply for access.
  - [API Reference](https://point.digital.nsw.gov.au/v3/docs/pages/api-document.html) - Endpoint documentation for each NSW Point service.
  - [Sample Forms](https://point.digital.nsw.gov.au/v3/docs/pages/sample-forms.html) - Interactive forms for trying predictive address, geocoding, parcel and property lookups.
- [Sector Link](https://www.nsw.gov.au/departments-and-agencies/premiers-department/sector-link) - Identity platform that lets government staff sign in to sector-wide applications with their agency credentials and MFA.
- [API.NSW](https://api.nsw.gov.au/) - Catalogue of public NSW Government APIs.
- [Transport for NSW Open Data Hub](https://opendata.transport.nsw.gov.au/) - Real-time and static transport datasets and APIs.
- [Data.NSW](https://data.nsw.gov.au/) - Open data portal for NSW Government datasets.
- [Spatial Collaboration Portal](https://portal.spatial.nsw.gov.au/portal/apps/sites/#/homepage) - Spatial datasets and web mapping services from NSW Spatial Services.

## Guidance

- [NSW Design Standards](https://digital.nsw.gov.au/delivery/digital-service-toolkit/design-standards) - Ten standards for designing and delivering NSW Government digital services.
- [Accessibility and Inclusivity Toolkit](https://digital.nsw.gov.au/delivery/accessibility-and-inclusivity-toolkit) - Guidance on designing, building, buying and testing accessible government services.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first, or [open an issue](https://github.com/digitalnsw/awesome-nswds/issues/new/choose).
