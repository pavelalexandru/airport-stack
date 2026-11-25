# Contributing

`airport-stack` is at the initial repository-structure stage. Component setup and
verification commands will be documented alongside the code as it is added.

## Development workflow

1. Create a branch for a focused change.
2. Choose the appropriate directory and read any component-specific guidance.
3. Implement the change, with relevant documentation and tests where useful.
4. Run the affected component's checks and check any consumers of shared code
   that changed.
5. Open a pull request explaining the problem, the resulting behavior and how
   the change was verified.

For a new component, include a README covering its purpose, prerequisites,
installation, configuration, usage and available verification commands. Include
dependency metadata for that component when it has dependencies.

Use small example inputs that others can reproduce. Keep local configuration,
credentials, generated files and large datasets out of commits.

## Project boundaries

Components may have different languages and release schedules. Reuse shared
libraries and documented contracts where that helps; keep unrelated components
independent. See [AGENTS.md](AGENTS.md) for the repository's development
conventions.

## License status

The project license has not yet been selected. No contributor agreement or
additional licensing terms are established by this starter document.
