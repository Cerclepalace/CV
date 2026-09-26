# CV — Agent Instructions

## Project goal
Professional zero-cost landing page / CV site for CerclePalace, with a focus on verifiable work, projects, methodology, and contact.

## Repository rules
- Keep the site lightweight, auditable, and static-first.
- Do not add payments, secrets, credentials, tracking scripts, or unnecessary backend services.
- Prefer GitHub-hosted source and Cloudflare for public delivery when configured.
- Never put API keys or tokens in frontend code.
- Every externally sourced claim must be verifiable before publication.
- Preserve a clear separation between public proof and private infrastructure.

## Content structure
- Hero / positioning
- Projects and verifiable work
- CerclePalace project
- Method: research, architecture, coding, audit, validation
- Lexicon
- Rules / engineering principles
- Contact

## Quality gate
Before deployment, verify:
1. Build succeeds.
2. No secrets are committed.
3. Links resolve.
4. Mobile layout works.
5. Accessibility basics are covered.
6. Metadata and social previews are present.
7. Cloudflare deployment configuration is explicit and reproducible.

## Cloudflare
Use Cloudflare's current agent documentation and Skills/MCP when configuring Cloudflare.
Do not invent account IDs, zones, domains, or bindings. Query the connected account and verify them first.
