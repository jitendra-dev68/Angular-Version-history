# Angular Version History and Features

## AngularJS (1.x)
- **Initial Release (2010)**:
  - Introduced two-way data binding, dependency injection, directives, and a modular approach to building single-page applications (SPAs).

## Angular 2 (2016)
- **Complete Rewrite**:
  - Introduced a component-based architecture, TypeScript as the primary language, and improved dependency injection.
- **Key Features**:
  - Components replaced controllers and directives.
  - Hierarchical Dependency Injection system.
  - Improved performance and simplified APIs.

## Angular 4 (March 2017)
- **Version Skip**:
  - Angular 3 was skipped to align the version numbers of core modules.
- **Key Features**:
  - Smaller and faster applications.
  - Improved *ngIf and *ngFor with an else clause.
  - Angular Universal support for server-side rendering.
  - Animations package moved to `@angular/animations`.

## Angular 5 (November 2017)
- **Key Features**:
  - Build Optimizer: Enhanced production builds by reducing bundle size.
  - Angular Compiler improvements for faster builds.
  - HttpClient replaced the older `Http` module.
  - Internationalized Number, Date, and Currency Pipes.

## Angular 6 (May 2018)
- **Key Features**:
  - Angular Elements: Allowed Angular components to be used as custom elements outside of Angular apps.
  - Tree Shakeable Providers: Reduced application bundle sizes by eliminating unused services.
  - Bazel: A build system for faster rebuilds and better incremental compilation.
  - `ng update` and `ng add` CLI commands.

## Angular 7 (October 2018)
- **Key Features**:
  - Virtual Scrolling and Drag & Drop in the `@angular/cdk`.
  - Improved performance with faster and smaller builds.
  - Angular Material & CDK: New component additions and accessibility improvements.
  - CLI Prompts: Helped guide developers during the CLI commands execution.

## Angular 8 (May 2019)
- **Key Features**:
  - Differential Loading: Automatically creates two bundles for modern and legacy browsers.
  - Ivy Preview: The new rendering engine aimed at improving compilation and rendering.
  - Lazy Loading with Dynamic Imports.
  - Web Workers support.

## Angular 9 (February 2020)
- **Key Features**:
  - Ivy as the default compiler and runtime.
  - Smaller bundle sizes and faster testing.
  - Improved type checking in templates.
  - New tooling and build errors.

## Angular 10 (June 2020)
- **Key Features**:
  - New Date Range Picker in Angular Material.
  - Updated Default Browser Configurations.
  - Optional Stricter Settings.
  - Warnings for CommonJS Imports.

## Angular 11 (November 2020)
- **Key Features**:
  - Faster Builds with Webpack 5 support.
  - Automatic Inlining of Fonts.
  - Improved Hot Module Replacement (HMR) support.
  - Enhanced CLI and Logging.

## Angular 12 (May 2021)
- **Key Features**:
  - Webpack 5 by Default.
  - Nullish Coalescing (`??`) in Angular Templates.
  - Strict Mode by default.
  - Deprecation of View Engine in favor of Ivy.

## Angular 13 (November 2021)
- **Key Features**:
  - TypeScript 4.4 support.
  - Angular Package Format (APF) Enhancements.
  - Removal of support for IE11.
  - Improved CLI with persistent build cache.

## Angular 14 (June 2022)
- **Key Features**:
  - Standalone Components: Simplified component creation without the need for NgModules.
  - Typed Forms.
  - Extended Template Diagnostics.
  - Improved CLI auto-completion.

## Angular 15 (November 2022)
- **Key Features**:
  - Enhanced Standalone Components: Further simplifying the architecture.
  - Directive Composition API.
  - Improved type safety for reactive forms.
  - New Web API request utilities.

## Angular 16 (May 2023)
- **Key Features**:
  - Signal-based reactive programming.
  - Hydration for server-side rendering (Angular Universal).
  - Reusable Template Fragments.
  - Zone.js optional.
  - Enhanced runtime performance with code optimizations.

## Angular 17 (November 2023)
- **Key Features**:
  - **Angular's New Innovative Site**: A refreshed and more intuitive site experience.
  - **Default Standalone Components**: Enhanced support and simplification for standalone components.
  - **SSR and SSG Support**: Improved Server-Side Rendering (SSR) and Static Site Generation (SSG) capabilities.
  - **Built-in Control Flow**:
    - `@if`: A new directive for conditional rendering.
    - `@else if`, `@else`: Extended support for conditional rendering with else-if and else clauses.
    - `@for`: A directive for iteration in templates.
    - **Automatic Migration**: Seamless migration to the built-in control flow system.
  - **Deferrable Views**: Support for deferring view rendering until necessary.
  - **Build Performance with ESBuild**: Significant performance improvements during builds using ESBuild.

## Angular 18 (May 2024)
- **Key Features**:
  - **Zoneless Change Detection with Signals**: Introduces a more efficient change detection mechanism using signals, eliminating the need for zones.
  - **Function-based Route Redirects**: Allows for more dynamic and flexible route redirection using functions.
  - **Improved Developer Tooling**: Enhancements to the Angular CLI and developer experience tools.
  - **Enhanced Angular Material and CDK**: New components and improved performance for Angular Material and Component Dev Kit (CDK).
  - **Server-Side Rendering (SSR) Enhancements**: Further optimizations and features for SSR in Angular applications.
  - **Improved Internationalization (i18n) Support**: Better support for multi-language applications, with more tools and APIs.
  - **TypeScript 5.4 Support**: Full compatibility with TypeScript 5.4, leveraging its latest features and improvements.

## Angular 19 (November 2024)
- **Key Features**:
  - **Standalone by Default**: `standalone: true` becomes the default for all components, directives, and pipes — non-standalone components require an explicit `standalone: false` flag.
  - **Incremental Hydration**: Inspired by deferrable views, allows parts of a server-side rendered page to be lazily hydrated using the familiar `@defer` syntax and triggers.
  - **Server Route Configuration**: Fine-grained control over rendering strategies (SSR, SSG, CSR) per route directly in the router config.
  - **Event Replay Enabled by Default**: Ensures user interactions that occur before hydration are captured and replayed after the app becomes interactive.
  - **linkedSignal API**: A new writable signal that automatically resets when a source signal changes, simplifying derived state management.
  - **Experimental Resource API**: Introduces asynchronous reactivity with `resource()` for signal-based async data loading.
  - **Stabilized Reactivity APIs**: `input()`, `output()`, and view query APIs (`viewChild`, `viewChildren`, `contentChild`, `contentChildren`) promoted to stable.
  - **Hot Module Replacement (HMR)**: Enabled by default for styles; template HMR introduced as experimental for faster development feedback.
  - **TypeScript 5.6 Support**: Full compatibility with TypeScript 5.6.

## Angular 20 (May 2025)
- **Key Features**:
  - **Zoneless Change Detection — Developer Preview**: The zoneless change detection API moves from experimental to developer preview, marking a major step toward eliminating Zone.js from Angular apps entirely.
  - **Stabilized Signal APIs**: `effect()`, `linkedSignal`, `toSignal`, `toObservable`, and `afterEveryRender` / `afterNextRender` all promoted to stable.
  - **`afterRender` renamed to `afterEveryRender`**: Clarifies the hook's intent and aligns with the stable lifecycle API naming.
  - **httpResource API (Experimental)**: A signal-based HTTP resource that reacts to signal changes and triggers new requests automatically, built on top of `HttpClient`.
  - **rxResource API**: Enables streaming multiple responses using RxJS observables, bridging signals and reactive streams.
  - **Enhanced Template Syntax**: Support for template string literals, the exponentiation operator (`**`), the `in` keyword, and the `void` operator — aligning template expressions closer to standard TypeScript.
  - **Improved Angular Material & CDK**: New components, performance improvements, and better accessibility across Angular Material.
  - **SSR Enhancements**: Further performance and DX improvements to server-side rendering and hydration pipelines.
  - **HammerJS Deprecation**: Official support for HammerJS is deprecated; developers relying on touch gestures are advised to migrate to custom implementations.
  - **TypeScript 5.8 Support**: Full compatibility with TypeScript 5.8.

## Angular 21 (November 2025)
- **Key Features**:
  - **Zoneless by Default for New Apps**: Zone.js is no longer included in new Angular projects by default; schematics are provided to assist existing apps in migrating to zoneless.
  - **Signal Forms (Experimental)**: Introduces a new signal-based approach to forms that is more composable, reactive, and scalable than both Template-Driven and Reactive Forms. Replaces the traditional `FormControl`/`FormGroup` model with signal-based equivalents.
  - **Generic `SimpleChanges`**: `SimpleChanges` is now a generic type, enabling TypeScript to enforce strong type checking inside the `ngOnChanges` lifecycle hook for `@Input()` values.
  - **Angular Aria (Developer Preview)**: A new headless UI component library built with accessibility as a core principle — complements Angular Material and CDK for building WCAG-compliant interfaces.
  - **AI-Powered Development Tooling**: Introduction of the Angular MCP (Model Context Protocol) Server, enabling AI coding assistants to scaffold, generate, and maintain Angular code with deeper framework awareness.
  - **Non-Destructive Hydration Improvements**: Further SSR refinements delivering up to 30% improvement in Time-to-Interactive for server-rendered applications.
  - **Build Performance (esbuild)**: ~25% faster compilation for large codebases compared to Angular 20, with improved incremental rebuild times.
  - **TypeScript 5.7 Support**: Full compatibility with TypeScript 5.7.

## Angular 22 (Expected May 2026)
> ⚠️ *Angular 22 is currently in release candidate / pre-release stage as of May 2026. Features listed below are based on the roadmap, RCs, and community sources and may change at stable release.*

- **Anticipated Key Features**:
  - **HttpClient Included by Default**: Zero-configuration HTTP — new projects get `HttpClient` set up out of the box without manual provider configuration.
  - **Zoneless Production-Ready**: Zone.js removal is fully stabilized; `OnPush` change detection is expected to become the default strategy for newly generated components, aligning with the signals-first architecture.
  - **Signal Forms Progression**: Signal Forms mature significantly toward stable status, positioning them as the recommended approach for all form management in Angular going forward.
  - **Selectorless Components (Experimental)**: Components can be imported and used directly in templates without defining string selectors, improving refactorability and type safety.
  - **Angular Aria Stable**: The headless accessibility component library introduced in v21 is expected to reach stable status.
  - **Vitest as Default Test Runner**: The Angular CLI adopts Vitest as the default testing solution for new projects, replacing Karma. Existing projects can migrate via schematics.
  - **`provideWebMcpTools` API**: New API enabling Angular apps to expose their own MCP tools for AI-assisted workflows, building on the MCP Server introduced in v21.
  - **Enhanced Template Type Checking**: Improved type checking and language service support for host bindings and listener expressions.
  - **TypeScript 5.9 Support**: Full compatibility with TypeScript 5.9, leveraging its latest type-checking improvements.
  - **Build Optimizations**: Continued esbuild improvements targeting 25–40% smaller production bundles compared to pre-v21 baselines.
  - **Node.js 26 Support**: Compatibility with Node.js 26.
