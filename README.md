# airport-stack

A shared workspace for reusable airport software: websites, mobile apps,
calculators, operational tools, analytics and forecasting.

This repository currently contains the project structure and contribution
guidance. No applications or services have been implemented yet.

## Repository structure

| Directory | Purpose |
| --- | --- |
| [`apps/`](apps/README.md) | Web and mobile applications |
| [`services/`](services/README.md) | APIs, backend services and hosted analytics |
| [`packages/`](packages/README.md) | Reusable libraries, schemas and shared contracts |
| [`tools/`](tools/README.md) | Standalone calculators, command-line tools and utilities |
| [`docs/`](docs/README.md) | Architecture, project guides and design decisions |

Related components share this repository so their changes can be reviewed
together. Each component can use its own technology, dependencies and release
process.

## Getting started

There is no repository-wide installation or build command yet. When a component
is added, its README should explain its purpose, setup, configuration and how to
run and verify it.

Start with the directory that fits your component. Keep reusable logic separate
from application-specific code, and introduce shared packages when there is a
clear need for reuse.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for the development workflow and
[AGENTS.md](AGENTS.md) for repository conventions.

## License

License selection is pending. This repository does not yet include an
open-source license.
