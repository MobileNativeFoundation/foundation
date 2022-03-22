# Project Lifecycle

This document outlines the lifecycle of the Mobile Native Foundation’s open-source projects: the stages of a project’s life, and the process for adopting projects and moving them between stages.

## Project Stages

**Incubation**

Incubating projects are experimental in nature, and are not production-ready. These projects can graduate to the active stage once they stabilize.

**Active**

Active projects are production-ready, see use in the community, and have engaged maintainers. These projects are under active development, and publish new releases.

**Maintenance**

Projects in the maintenance stage are mature, stable, and see use in the community, but have no roadmap for new features. A project may stay in this stage indefinitely.

**Archived**

Archived projects are not maintained. They should no longer be relied on in production.

## Adoption

Projects that are submitted to the Mobile Native Foundation will be evaluated by the technical steering committee (TSC) according to the following criteria. A project does not need to meet every guideline — adoption is ultimately up to the TSC’s discretion — and a project may be brought in at the incubating, active, or maintenance stage, depending on its level of maturity and use. Adoption of a project and its stage is determined by a TSC vote.

1. **Projects must be open source, ideally under the [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) License.**

    Other licenses (including the MIT or BSD license) may be accepted, at the discretion of the TSC.

2. **Projects should have community interest.**

    Candidate active projects should be relatively well known within the community, and have significant usage or interest. There should be a desire to keep the project alive and functioning for the community. Candidate incubating projects may have no usage, but should have community interest.

3. **Projects should have broad applicability.**

    Projects should solve problems that many teams or companies face.

4. **Projects should be “production ready.”**

    Projects need not be fully mature, but in general:

    1. Code should be of a high quality.
    2. Clear documentation should exist, including a README and deployment/usage instructions.
    3. A comprehensive test suite should exist.
    4. The project should already be used in production by some teams.

    Candidate incubating projects will not be held to the same standard.

5. **Projects must have maintainers.**

    Ideally existing maintainers will commit to continuing in their role. The MNF can also work with existing maintainers to find new maintainers. Maintainers must be documented in a CODEOWNERS file.

## Archiving

Eventually, a project may be archived to indicate that it is no longer maintained and that the MNF no longer recommends its use. The TSC will always discuss a project’s future with its maintainers to determine the best path forward, which could include finding new maintainers for the project.

Good candidates for archiving include:

1. **Projects with no active maintenance**: maintainers may decide to leave a project, or the project may see no new commits on its main branch in a year.
2. **Projects with no active usage**: projects may fall out of use over time. They may have been replaced by first-party tooling, or the community may have adopted a competing solution.

Archived projects will use Github’s “archived” status: code and past releases will still be available.

To archive a project:

1. The TSC will first reach out to the project’s maintainers to discuss the current state of the project.
2. The TSC will start a discussion with the broader MNF community by posting both a proposal on the discussion forum and an issue on the project’s repository. The proposal will be open for at least a month.
    1. Template for Github issue:  \
“This project appears [to not have much usage] [to lack maintainers/contributors]. If that’s the case, it might be a good candidate for archiving (link to this document). If anyone depends on this project and would rather it not be archived, please leave a comment, or just close this issue.”
1. The TSC must vote in favor of archiving the project.
2. The TSC will create a final issue in the project repository indicating that the project will be archived.
3. A week later, the project will be archived.

