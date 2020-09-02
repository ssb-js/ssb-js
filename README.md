# SSB-JS

## History

The SSBC is a structureless organization that doesn't adaquately serve the needs
of participants in the Scuttlebutt ecosystem. The SSB-JS namespace is an attempt
to build a healthy organization with reliably maintained software.

Healthy organizations have healthy governance, which requires decision-making
and conflict-resolution practices available to all members. Most decisions
should be made organically from the bottom up, but decisions that change the
SSB-JS organization require discussion and consent.

## Projects

- [Chloride](https://github.com/ssb-js/chloride)
- [Multiserver](https://github.com/ssb-js/multiserver)
- [MuxRPC](https://github.com/ssb-js/muxrpc)
- [SSB-Keys](https://github.com/ssb-js/ssb-keys)
- [SSB-Ref](https://github.com/ssb-js/ssb-ref)
- [SSB-Validate](https://github.com/ssb-js/ssb-validate)
- [Secret-Stack](https://github.com/ssb-js/secret-stack)

## Maintainers

### 2020

- [@arj03](https://github.com/arj03) -- Multiserver, SSB-Ref, and SSB-Validate
- [@christianbundy](https://github.com/christianbundy) -- Multiserver, MuxRPC, and SSB-Validate
- [@mixmix](https://github.com/mixmix) -- Chloride, SSB-Ref, and Secret-Stack
- [@soapdog](https://github.com/soapdog) -- MuxRPC and SSB-Keys
- [@staltz](https://github.com/staltz) -- Chloride, SSB-Keys, and Secret-Stack

## Process

### Repositories

- There MUST be one Git repository for governance and one for each project.
- The 'SSB-JS namespace' refers to the SSB-JS organizations on GitHub and npm.
- The SSB-JS namespace MUST be read-only unless specified otherwise.
- Repositories and build artifacts must be hosted in the SSB-JS namespace.
- Repositories MUST have a 'main' branch.
- Repositories SHOULD NOT have any other branches.
- Repositories MUST allow project discussions via issues.
- Repositories MUST allow patch proposals via pull requests.
- The latest commit on the 'main' branch SHOULD always be versioned and released on npm.

### Projects

- Projects SHOULD be written in JavaScript or TypeScript.
- Projects SHOULD have internally consistent code style.
- Projects SHOULD have documentation of all public APIs.
- Projects SHOULD have automated tests for all target platforms.
- Projects SHOULD have internally consistent contribution guidelines.

### Contributors

- 'Contributors' are anyone who participates in a project.
- Contributors MUST aim to foster an open, welcoming, and harassment-free space.
- Contributors SHOULD recommend changes in the form of patches.
- Contributors who want to be maintainers SHOULD participate consistently and often.

### Maintainers

- 'Maintainers' are contributors trusted to steward a project and vote.
- Maintainers MUST have the 'owner' role on GitHub and NPM.
- Maintainers MUST have 2FA enabled on GitHub and NPM.
- Maintainers SHOULD review and merge outstanding patches for the project they maintain.
- Maintainers MAY review and merge patches for other projects.
- Maintainers SHOULD NOT merge their own pull requests.
- Maintainers SHOULD aim to make contributing a fun and simple experience.
- Maintainers SHOULD merge project pull requests in a fast and friendly manner.
- Maintainers SHOULD merge project pull requests that are net positive and pass tests.
- Maintainers SHOULD NOT suggest small improvements on project pull requests.
- Maintainers SHOULD suggest their improvements by opening their own pull request.
- Maintainers SHOULD close pull requests that are inactive for more than 30 days.
- Maintainers SHOULD invite high-quality contributors to become maintainers.
- Maintainers SHOULD remove anyone who fails to apply this process.

### Governance

- The governance repository MUST be hosted at <https://github.com/ssb-js/ssb-js.git>.
- Roles and repositories in the SSB-JS namespace MUST match the governance repository.
- Activity in the SSB-JS namespace MUST apply the process from the governance repository.
- Patches to the governance repository MUST NOT be merged unless the latest commit on a pull request is approved by ⅔ of active maintainers.
- If there are no active maintainers because their term expired, the previous cohort should be considered 'active maintainers' for the purposes of voting.
- Maintainers MUST merge governance patches that are approved.
- Maintainers MUST NOT merge governance patches that are not approved.
