# Repository integration contract

CSOS is the governance source of truth. Project repositories consume exact semantic versions of CSOS, CDS, Starter, and Assets through studio-manifest.yml.

## Rules
- A project records exact semantic versions; latest is prohibited.
- Breaking changes require an ADR and a major version.
- CDS tokens are consumed from generated output, never copied by hand.
- Assets are referenced by registry ID and license status.
- Business data never enters a public project repository.
- Client repositories are separate repositories under the organization.
- A project cannot pass launch without evidence for every mandatory gate.
