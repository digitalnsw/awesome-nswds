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
- [Other Australian Design Systems](#other-australian-design-systems)
- [International Government Design Systems](#international-government-design-systems)
- [Service Manuals and Toolkits](#service-manuals-and-toolkits)
- [Learning and Capability](#learning-and-capability)
- [NSW Government Sites That Inspire Me](#nsw-government-sites-that-inspire-me)
- [Other Australian Government Sites That Inspire Me](#other-australian-government-sites-that-inspire-me)
- [International Government Sites That Inspire Me](#international-government-sites-that-inspire-me)
- [Guidance](#guidance)
- [Contacts](#contacts)

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
- [NSW Design System Accelerator](https://nswds.dsforce.dev/s/) - Salesforce Lightning Web Components for Experience Cloud and OmniStudio, including an address picker backed by NSW Point.
  - [Source Code](https://github.com/SalesforceLabs/gps-design-systems-lwc) - Security-vetted Salesforce Labs repository, which also covers other governments' design systems.

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

## Other Australian Design Systems

- [Ripple](https://ripple.sdp.vic.gov.au/) - Victorian Government design system and Vue component library from the Single Digital Presence team.
- [Queensland Government Design System](https://www.designsystem.qld.gov.au/) - Queensland's design system, with Bootstrap 5 and web component implementations.
  - [qgds-web-components](https://github.com/qld-gov-au/qgds-web-components) - Framework-agnostic Lit web components.
  - [qgds-bootstrap5](https://github.com/qld-gov-au/qgds-bootstrap5) - Bootstrap 5 implementation.
- [Agriculture Design System](https://design-system.agriculture.gov.au/) - React design system from the federal Department of Agriculture, Fisheries and Forestry, building on the original Australian Government Design System.
- [CivicTheme](https://www.civictheme.io/) - Open-source design system and Drupal theme built for government compliance. Made by a vendor rather than an agency.

## International Government Design Systems

- [GOV.UK Design System](https://design-system.service.gov.uk/) - Styles, components and patterns for UK government services.
  - [GOV.UK Prototype Kit](https://prototype-kit.service.gov.uk/) - Tool for building realistic HTML prototypes of government services.
- [Home Office User-Centred Design Manual](https://design.homeoffice.gov.uk/) - UK Home Office design system, content style guide and accessibility standard.
- [Department for Education Design](https://design.education.gov.uk/) - UK Department for Education design standards, guidance and DfE Frontend.
- [HMRC Design Resources](https://design.tax.service.gov.uk/) - Styles, components and patterns for HMRC services, consistent with GOV.UK.
- [Intelligence Community Design System](https://design.sis.gov.uk/) - Styles, components and patterns for apps across the UK intelligence community.
- [NHS Design System](https://service-manual.nhs.uk/design-system) - Components and patterns for NHS websites and services.
- [Scottish Government Design System](https://designsystem.gov.scot/) - Components and patterns for the Scottish Government and public sector, with a React version and prototype templates.
- [U.S. Web Design System](https://designsystem.digital.gov/) - Components and guidance for US federal government websites.
- [VA.gov Design System](https://design.va.gov/) - US Department of Veterans Affairs components and patterns for VA.gov.
- [CMS Design System](https://design.cms.gov/) - US Centers for Medicare and Medicaid Services components for Section 508 compliant websites.
- [GC Design System](https://design-system.canada.ca/) - Government of Canada web components for building digital products.
- [Canada.ca Design](https://design.canada.ca/) - Styles, templates and patterns for Government of Canada services on Canada.ca.
- [Ontario Design System](https://designsystem.ontario.ca/) - Design and coding standards, web components and npm packages for Government of Ontario products.
- [Système de design gouvernemental du Québec](https://design.quebec.ca/) - Québec government web standards and components. In French.
- [NL Design System](https://nldesignsystem.nl/) - Dutch government collection of design systems and shared components, built in the open. In Dutch.
- [Système de Design de l'État](https://github.com/GouvernementFR/dsfr) - French government design system. Documentation is in French.
- [KERN](https://www.kern-ux.de/) - Open-source UX standard and design system for German administration, from local to federal level. In German.
- [Designers Italia](https://designers.italia.it/design-system/) - Design system for the Italian public administration. In Italian.
- [GOV.IE Design System](https://github.com/ogcio/govie-ds) - Irish Government design system source and documentation.
- [GOV.GR Design System](https://guide.services.gov.gr/) - Styles, components and patterns for services consistent with GOV.GR.
- [Ágora Design System](https://mosaico.gov.pt/ferramentas/agora-design-system) - Portuguese government patterns and components for gov.pt services. In Portuguese.
- [TEDI](https://www.tedi.ee/) - Estonian Government Design System.
  - [X-Road](https://x-road.global/) - Open-source software for secure data exchange between organisations, used in Estonia's digital government.
- [Suomi.fi Design System](https://designsystem.suomi.fi/) - Finnish government components, design patterns and principles for digital services. In Finnish.
  - [suomifi-ui-components](https://github.com/vrk-kpa/suomifi-ui-components) - React component library.
- [Det Fælles Designsystem](https://designsystem.dk/) - Danish shared design system for self-service on borger.dk and Virk. In Danish.
- [Designsystemet](https://designsystemet.no/en/) - Norwegian shared toolbox of UI components, guidelines and patterns for digital services.
- [Ísland.is Design System](https://island.is/s/stafraent-island/honnunarkerfi) - Icelandic government design system, published openly in Figma. In Icelandic.
  - [Ísland UI](https://ui.devland.is/) - Storybook for the component library that implements the design system.
- [Design systém gov.cz](https://designsystem.gov.cz/) - Czech government UI component library for public administration projects. In Czech.
- [Vlaanderen Design System](https://www.vlaanderen.be/vlaanderen-design-system) - Flemish government components, design guidelines and best practices for websites, web apps and mobile apps. In Dutch.
- [Europa Component Library](https://ec.europa.eu/component-library/) - European Commission design system for EU websites.
  - [Source Code](https://github.com/ec-europa/europa-component-library) - Europa Component Library repository.
- [Helsinki Design System](https://hds.hel.fi/) - City of Helsinki guidelines, design assets and component libraries for its digital services.
- [Amsterdam Design System](https://designsystem.amsterdam/) - City of Amsterdam components, icons, design tokens and templates for its digital services.
- [Singapore Government Design System](https://www.designsystem.tech.gov.sg/) - Frontend framework and components for Singapore Government websites.
- [Malaysia Government Design System](https://design.digital.gov.my/) - Design foundation and pre-built components for official Malaysian government websites.
- [Digital Agency Design System](https://design.digital.go.jp/dads/) - Japanese Digital Agency design language, components and guidance, in beta. In Japanese.
- [New Zealand Government Design System](https://design-system-alpha.digital.govt.nz/) - Elements, components and patterns for NZ public sector websites. Currently an alpha.

## Service Manuals and Toolkits

- [Digital Experience Toolkit](https://www.digital.gov.au/policy/digital-experience/toolkit/service-design-and-delivery-process) - Australian Government service design and delivery process, from the Digital Transformation Agency.
- [Victorian Digital Guides](https://www.vic.gov.au/digital-guides) - Victorian Government best practice guidance for digital teams.
- [National AI Centre](https://www.ai.gov.au/) - Australian Government guidance, tools and resources to help businesses use AI safely.
- [GOV.UK Service Manual](https://www.gov.uk/service-manual) - Guidance for UK government teams creating and running services that meet the Service Standard.
- [Digital Scotland Service Manual](https://servicemanual.gov.scot/) - Guidance for delivering digital projects in the Scottish public sector.
- [Scottish Parliament Digital Service Toolkit](https://www.parliament.scot/digital-service-toolkit) - Content style guide, content strategy, brand guidelines and accessibility guidance.
- [Digital.gov](https://digital.gov/) - Guidance on building better digital services in US government.
  - [Communities of Practice](https://digital.gov/communities) - Cross-government communities sharing resources on digital experience.
- [Digital Standards Playbook](https://www.canada.ca/en/government/system/digital-government/government-canada-digital-standards.html) - Government of Canada digital standards and how to apply them.
- [Digital.govt.nz](https://www.digital.govt.nz/) - New Zealand Government standards, guidance and resources for digital services.
- [Suomi.fi for Service Developers](https://kehittajille.suomi.fi/frontpage) - Finland's national digital solutions, good practices and guidelines for service developers.
- [Servicestandard](https://digitalservice.bund.de/en/projects/servicestandard) - German federal requirements, guidance and support for building high-quality online services.

## Learning and Capability

- [Digital Academy](https://innovationnetwork.vic.gov.au/digital-academy) - Victorian Government learning programs for building a digital-ready public sector.
- [GovAI](https://www.govai.gov.au/) - Australian Government service for building AI capability across the APS.

## NSW Government Sites That Inspire Me

- [NSW Government](https://www.nsw.gov.au/) - Central website for NSW Government information and services.
- [iCanQuit](https://www.icanquit.com.au/) - Cancer Institute NSW support for quitting smoking and vaping.
- [Neon Marketplace](https://www.neonmarketplace.nsw.gov.au/) - Business-to-business hub connecting artists, suppliers and business partners to grow NSW's 24-hour economy districts.
- [transportnsw.info](https://transportnsw.info/) - Trip planner, timetables, travel alerts and Opal fares for public transport across NSW.
- [Destination NSW](https://www.destinationnsw.com.au/) - NSW Government tourism and major events agency.
- [Visit NSW](https://www.visitnsw.com/) - Official NSW tourism website for towns, events, road trips and places to stay.
- [Museums of History NSW](https://mhnsw.au/) - NSW museums, historic houses and the State Archives Collection.

## Other Australian Government Sites That Inspire Me

## International Government Sites That Inspire Me

## Guidance

- [NSW Design Standards](https://digital.nsw.gov.au/delivery/digital-service-toolkit/design-standards) - Ten standards for designing and delivering NSW Government digital services.
- [Accessibility and Inclusivity Toolkit](https://digital.nsw.gov.au/delivery/accessibility-and-inclusivity-toolkit) - Guidance on designing, building, buying and testing accessible government services.

## Contacts

- [NSW Design System](mailto:designsystem@customerservice.nsw.gov.au) - Team behind designsystem.nsw.gov.au, its components and Figma UI kit.
- [Digital NSW](mailto:digital@customerservice.nsw.gov.au) - Owners of the digitalnsw GitHub organisation, the @nswds packages, the NSW Email Toolkit and Public Sans. For application support, email [appsupport@customerservice.nsw.gov.au](mailto:appsupport@customerservice.nsw.gov.au).
- [NSW Education Application Design System](mailto:ui@det.nsw.edu.au) - Team behind ADS and the @nswdoe packages. Department staff can also use the #ask-ads-app-design-system Slack channel.
- [DCJ Digital Design System](mailto:digitalexperience@dcj.nsw.gov.au) - Department of Communities and Justice digital experience team.
- [NSW Government Branding](mailto:nswgovbranding@customerservice.nsw.gov.au) - Brand Toolbox access and NSW Government branding questions.
- [Accessibility NSW](mailto:digital.accessibility@customerservice.nsw.gov.au) - Team behind the Accessibility and Inclusivity Toolkit.
- [NSW Point](mailto:ss-nswpoint@customerservice.nsw.gov.au) - API access and support for NSW Point.
- [Sector Link Help](https://www.nsw.gov.au/departments-and-agencies/premiers-department/sector-link/sector-link-help-form) - Request form for help with Sector Link.
- [API.NSW Support](https://api.nsw.gov.au/Support) - Support form for problems, quotas and API changes.
- [Transport for NSW Open Data](mailto:OpenDataHelp@transport.nsw.gov.au) - Help with Open Data Hub datasets and APIs.

## Related Lists

- [Global Design Systems for Governments](https://nldesignsystem.nl/community/global-design-system/) - Index of government design systems worldwide, maintained by NL Design System.
- [Government Design Systems List](https://github.com/ctrimm/Government-Design-Systems-List) - Federal, state and municipal government design systems.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first, or [open an issue](https://github.com/digitalnsw/awesome-nswds/issues/new/choose).
