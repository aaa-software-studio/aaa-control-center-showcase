# AAA Control Center
### WordPress & WooCommerce Management Dashboard

A standalone PHP/JavaScript dashboard built by AAA Software Studio for one administrator managing multiple WordPress and WooCommerce site projects.

**Status:** Development preview · One administrator per installation  
**Download:** [0.13.0-preview2 — Self-hosted Technical Preview](https://github.com/aaa-software-studio/aaa-control-center-showcase/releases/tag/v0.13.0-preview2)  
**Version shown in images:** v0.12.0  
**Repository purpose:** Product showcase, documentation, and release downloads

## Download and Installation

Download **AAA-Control-Center-0.13.0-preview2-self-hosted.zip** from the release Assets. GitHub's automatic **Source code** ZIP/TAR downloads contain this showcase repository, not the application installer.

The package requires an isolated Linux/POSIX environment, PHP CLI/SSH or hosting Terminal, the documented PHP extensions, an empty MySQL/MariaDB database, and HTTPS. Read `INSTALL.md` inside the package. Only `public/` belongs in the web document root; private application files, configuration and the separate encryption key must remain outside it.

Each installation starts with its own administrator and no configured site projects. Supply your own site credentials and optional Gemini key. **Do not extract the package over an existing personal installation.**

This is not a Windows installer. Native Windows, WSL/Docker packages and general hosting compatibility have not been validated. Distributed connectors reject localhost/private-network CMS targets.

## Dashboard Preview — English

![AAA Control Center English dashboard with FA and EN language controls and sample project data](exec-5eaffbb8-0ee8-4de9-aea7-37303f1eed05.png)

*AI-edited portfolio preview based on the v0.12.0 application interface. Project details and timestamps have been replaced or removed for privacy. This image illustrates the interface, not verified execution of every visible feature.*

## Products Preview — English

![AAA Control Center products interface with fictional products, prices, stock, and permalinks](exec-9111b301-b37a-4893-91e8-cd1591f95133.png)

*AI-edited v0.12.0 preview using fictional product names, prices, identifiers, and example.com URLs. This image is not evidence of successful write operations.*

## Implemented Scope

- Manage multiple site projects within one administrator's installation.
- Read and edit supported WooCommerce product fields.
- Read and edit supported WordPress content and slugs.
- Preview and approve changes in supported workflows.
- Switch between English and Persian with EN/FA; English is the default, and the browser remembers the selection.
- Store connection credentials encrypted, with the encryption key outside the public web root.
- Configure an optional owner-supplied Gemini key, discover models and run a fixed-message connection test.

Implementation and verification coverage vary by module. A basic visual editor and HTML mode are included; TinyMCE and the custom font are excluded from the redistributable package.

## Test Evidence and Limits

The developer's preview1 report records an independent installation, authentication checks, real WordPress/WooCommerce reads, and one approved short-description change to a fictional simple product, confirmed by a separate read. Invalid and repeated approvals were rejected. This local test used temporary transport adaptations in a disposable copy; it was not an unmodified internet-host deployment.

Preview2 changes licensing, documentation and build identifiers. Runtime logic is unchanged. Independent rebuild checks covered archive integrity/manifests, version-normalized runtime equivalence, JSON parsing, 19 JavaScript/CJS syntax checks, and package privacy scans. PHP/integration acceptance tests were not rerun during that rebuild.

Real hosting, full browser/mobile acceptance, broader CMS writes, live Gemini, full restore, load testing and an independent security audit remain outstanding. See the release notes and the package's `docs/TEST-REPORT.md`, `docs/CMS-TEST-REPORT-preview1.md` and `docs/RELEASE-VALIDATION.md`.

This is a development preview. Hosted multi-user registration, subscriptions and AI article generation are not implemented. Multiple site projects do not imply isolated user accounts.

## Technology

PHP, JavaScript, HTML/CSS, and MySQL/MariaDB. WordPress connections use REST API Application Passwords; WooCommerce uses its REST API credentials. Installation requires PHP CLI; there is no public web installer.

## License and Privacy

The installer includes **AAA Control Center Preview Use License 1.0** in `LICENSE.md`. Authorized internal use and private maintenance modifications are permitted, including management of authorized client websites. Resale, public redistribution and hosted access require separate permission. This is not an open-source license; third-party rights remain applicable.

The development source archive and private review bundles are not release assets. The installer contains readable PHP/JavaScript needed to run the application.

Package scans found no known personal-site markers, recognizable credential patterns, runtime configuration, saved connections or nonempty secret fields in JSON. These checks are not an independent security audit.

Public previews use fictional data. A public interactive demo is not currently available.

## About the Studio

Built from the creator's own idea with AI assistance as part of [AAA Software Studio](https://github.com/aaa-software-studio), documenting practical work in WordPress tooling, SEO workflows, and automation.
