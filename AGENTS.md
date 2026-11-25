# Development conventions

## Structure and boundaries

- Put applications in `apps/`, backend services in `services/`, reusable
  libraries and contracts in `packages/`, standalone utilities in `tools/`, and
  project documentation in `docs/`.
- Give each substantial component its own directory and README. Document real
  setup, run, build and verification commands as they become available.
- Keep component dependencies explicit. Share code through a package or a
  documented interface rather than importing another application's internals.
- Choose technology to suit the component. Do not impose a repository-wide
  framework, dependency manager or release process without a concrete need.

## Changes and verification

- Keep changes focused on the requested outcome and follow the conventions of
  the component being changed.
- Run existing checks relevant to the change. Add tests for meaningful behavior
  when implementation warrants them; do not add empty tests or workflows to
  this starter structure.
- When shared logic or contracts change, check the affected consumers as well.
- Keep documentation aligned with actual behavior. State which checks ran and
  identify any checks that could not run.

## Portability and repository hygiene

- Support Windows and macOS where practical. Avoid hard-coded absolute paths
  and document platform-specific setup when needed.
- Keep credentials, local environment files, generated output and runtime data
  out of version control. Use documented configuration names and synthetic or
  suitably sanitized examples.
- Keep large datasets and model artifacts outside source control; document
  their retrieval and versioning when a component needs them.
