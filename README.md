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

- [@arj03](https://github.com/arj03)
- [@christianbundy](https://github.com/christianbundy)
- [@mixmix](https://github.com/mixmix)
- [@soapdog](https://github.com/soapdog)
- [@staltz](https://github.com/staltz)

## Process

### Repositories

- There MUST be one Git repository for governance and one for each project.
- The 'SSB-JS namespace' refers to the SSB-JS organizations on GitHub and npm.
- Repositories and build artifacts must be hosted in the SSB-JS namespace.
- Repositories MUST have a 'main' branch.
- Repositories MUST NOT have any other branches.
- The latest commit on the 'main' branch SHOULD always be versioned and released on npm.

### Projects

- Projects SHOULD be written in JavaScript or TypeScript.
- Projects SHOULD have internally consistent code style.
- Projects SHOULD have documentation of all public APIs.
- Projects SHOULD have automated tests for all target platforms.
- Projects SHOULD have internally consistent contribution guidelines.

### Contributing

- Anyone MUST be able to propose changes to repositories via pull request.
- Anyone who is not a maintainer MUST NOT have the ability to push commits to repositories.
- Maintainers MUST have the ability to push commits to every repository.
- Maintainers SHOULD NOT merge their own pull requests.
- Maintainers SHOULD aim to make contributing a fun and simple experience.
- Maintainers SHOULD merge project pull requests in a fast and friendly manner.
- Maintainers SHOULD merge project pull requests that are net positive and pass tests.
- Maintainers SHOULD NOT suggest small improvements on project pull requests.
- Maintainers SHOULD suggest their improvements by opening their own pull request.
- Maintainers SHOULD close pull requests that are inactive for more than 30 days.

### Governance

- The governance repository MUST be hosted at <https://github.com/ssb-js/ssb-js.git>.
- Maintainers and projects in the SSB-JS namespace MUST match the governance repository.
- Activity in the SSB-JS namespace MUST apply the process from the governance repository.
- Maintainers SHOULD invite project contributors to become maintainers.
- Maintainers who are inactive or fail to apply this process SHOULD be removed.
- Changes to the governance repository MUST NOT be merged unless the latest commit on a pull request is approved by ⅔ of maintainers.
- Maintainers MUST merge changes that are approved.
- Maintainers MUST NOT push any changes that are not approved.
