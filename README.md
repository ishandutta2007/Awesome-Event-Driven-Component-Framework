# Awesome-Event-Driven-Component-Framework

## Top Event-Driven Component Framework Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Reactive Bindings, Dynamic Interactions & Low-Code App Composition*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Event-Driven Component Frameworks**. These tools enable developers and admins to compose applications where components communicate through events and reactive bindings — creating dynamic, responsive UIs without imperative glue code.



**Examples** include Salesforce Dynamic Interactions, Retool, Appsmith, Superblocks, UI Bakery, Budibase, ToolJet, DronaHQ, Internal, and Lowcoder (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom component libraries, and open event-driven architectures — ideal for platform teams, internal tool builders, and developers seeking transparent, vendor-independent app frameworks.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Dynamic Interactions](https://developer.salesforce.com/docs/platform/lwc/guide/use-config-for-app-builder-dynamic-interactions.html)**  

  Lightning App Builder feature enabling admins to configure interactions between components on a page. Source components expose events via `targetConfig` metadata with `event` and `schema` subtags in the `.js-meta.xml` file . Admins select a source component event and configure target components — no code required after developer exposes the event. Only LWC can be source components; targets can be Aura or LWC. Supported property types: String, Integer, Boolean .



- **[Retool](https://retool.com/)**  

  Low-code platform for internal tools with component-based architecture. Components function like React components with internal state, represented as JavaScript objects . Features global `{{ }}` bindings, event handlers for user interactions, and JavaScript methods for programmatic control (e.g., `textInput1.setValue()`). Custom React/TypeScript components available via `Retool.connectReactComponent()` with `triggerQuery`, `model`, and `modelUpdate` interfaces .



- **[Appsmith](https://appsmith.com/)**  

  Open-source low-code platform with reactive bindings architecture. Widgets (views) respond automatically to changes in queries (controllers) and datasources (models) via MVC-like separation . No imperative event handlers needed — visibility, values, and states are declaratively bound with `{{ }}` expressions. Data flows: Model → Controller → View for reads; View → Controller → Model for writes .



- **[Superblocks](https://superblocks.com/)**  

  Enterprise app platform with hybrid deployment. Control plane and AI inference run in Superblocks cloud; data plane executes inside customer VPC (AWS, GCP, Azure) for production data locality . Production APIs never leave customer network. Outbound-only connectivity — no inbound firewall ports required. Centralized governance with enterprise SSO and RBAC managed from cloud .



- **[UI Bakery](https://uibakery.io/)**  

  Low-code platform with visual component composition. Components expose variables like `{{ui.componentName.value}}` and `{{ui.componentName.selectedRow.data}}` for binding across actions and properties . Action results available as `{{actions.actionName.data}}`. Card component enables layout composition with expand-to-fit behavior for responsive dashboards .



- **[Budibase](https://budibase.com/)**  

  Open-source low-code platform with Blocks — pre-built components combining multiple sub-components (Data Provider, Repeater, Card) . Blocks expose global bindings like `{{ MyFormBlock.Fields.FirstName }}` and can be ejected into constituent components for granular customization. App-level bindings include URL parameters, app state, current user, device, and role .



- **[ToolJet](https://tooljet.com/)**  

  Open-source low-code platform with module-based data flow. Parent-to-module via input parameters (`{{input.userData}}`), module-to-parent via output parameters (`{{components.<moduleName>.submittedFormData}}`) . Queries can be parent-triggered or self-contained within module. Workflow nodes include Start Trigger, JavaScript, If Condition, Loop, and Data Source nodes for event-driven automation .



- **[DronaHQ](https://dronahq.com/)**  

  Low-code platform with container app architecture. Micro-apps run inside native containers (iOS, Android, Windows, Web) with User Management, Micro-app Management, Notification Manager, WebView Runtime, and Security Manager . Widgets for Agent Builder enable AI-generated structured data to render as custom React UI components via JSON Schema .



- **[Internal](https://internal.io/)**  

  Low-code platform with auto-generated functions from connected data sources. Spaces created per datasource for exploring data and creating relationships. No-code configuration with optional custom SQL and JavaScript .



- **[Lowcoder](https://lowcoder.cloud/)**  

  Open-source Retool alternative with drag-and-drop editor. Select/MultiSelect components expose `value`, `selectedIndex`, `selectedLabel` properties and `Change`, `Focus`, `Blur` events . Component methods include `setValue()`, `clearValue()`, `resetValue()`, `setDefaultValue()`. Self-hostable with MongoDB and Redis .



## Open-Source GitHub Projects



- **[Appsmith](https://github.com/appsmithorg/appsmith)**  

  Open-source low-code platform (Apache-2.0) with reactive binding architecture. 45+ widgets, 50+ datasource connectors. Widgets automatically update based on state changes — no imperative event handlers . Self-hostable via Docker. G2 Winter 2026: 89% application deployment satisfaction.



- **[Budibase](https://github.com/Budibase/budibase)**  

  Open-source low-code platform (GPL-3.0) with Blocks system. Pre-built blocks (Cards, Repeater, Form, Chart, Multi-Step Form) combine multiple components . Global bindings scoped by component name. Eject blocks to granular components. Self-hostable with Docker.



- **[ToolJet](https://github.com/ToolJet/ToolJet)**  

  Open-source low-code platform (AGPL-3.0) with module-based composition. Data flow between parent and module via input/output parameters . Workflow automation with Start Trigger, JavaScript, If Condition, Loop, and Data Source nodes . G2 Winter 2026: 94% application deployment satisfaction.



- **[Lowcoder](https://github.com/Nangelov7/lowcoder)**  

  Open-source Retool/Appsmith/ToolJet alternative (AGPL-3.0). 120+ built-in components, native website embedding (no iframe), video meeting components, RBAC, self-hosting . Continues from abandoned Openblocks project. Railway one-click deploy template with MongoDB and Redis.



- **[DronaHQ Self-Hosted](https://github.com/dronahq/dronahq-self-hosted)**  

  Self-hosted edition of DronaHQ low-code platform. Container app architecture with micro-apps, user management, and security modules . Widgets system for AI agent UI rendering .



- **[UI Bakery](https://github.com/uibakery)**  

  Component library and documentation for UI Bakery platform. Components expose variables for cross-component binding . Expand-to-fit and Card container patterns for responsive layouts .



- **[Lowcoder](https://github.com/lowcoder-org/lowcoder)**  

  Open-source low-code platform community edition. Select/MultiSelect components with full property, event, and method API . Self-hosted with MongoDB 7 and Redis 8 .



### Additional Strong Open-Source Options



- **[Refine](https://github.com/refinedev/refine)** — React framework (MIT) for building admin panels and internal tools with headless components.

- **[React Admin](https://github.com/marmelab/react-admin)** — Frontend framework (MIT) for B2B applications on REST/GraphQL APIs.

- **[Baserow](https://github.com/baserow/baserow)** — Open-source no-code database (MIT) with application builder.

- **[NocoDB](https://github.com/nocodb/nocodb)** — Open-source Airtable alternative (AGPL-3.0) with API-first architecture.

- Community **n8n** workflows for component-level automation and event routing.



**Frameworks for building custom systems**: Combine **Appsmith** or **ToolJet** as the low-code app layer with **Budibase** for block-based composition, **Lowcoder** for self-hosted deployment, and **PostgreSQL/MongoDB** for persistence — creating a fully self-hosted, enterprise-grade event-driven component platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Event-driven component frameworks handling business data must comply with data protection regulations (GDPR, CCPA, etc.).

- Self-hosted open-source solutions require proper security hardening, infrastructure provisioning, and ongoing maintenance. Reactive architectures reduce imperative code but require understanding of dependency graphs for debugging complex interactions.



---



**Made for platform engineers, internal tool builders, citizen developers, and organizations building transparent app frameworks.**  

Let's make Event-Driven Component Frameworks more open, data-driven, and reactive.
