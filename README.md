# Hey, I'm Ryan 👋

I'm Ryan Akmal Pasya, a full-stack developer from Aceh, Indonesia. I build web interfaces, APIs, and the workers that connect them.

I work mostly with **TypeScript, React, Node.js, and PostgreSQL**. Lately I've been using **Go** to explore how workers coordinate and recover from failures.

I'm open to remote full-time roles, paid internships, and contract work.

[Portfolio](https://ryanakmall.is-a.dev) · [Email me](mailto:ryan@nylo.me)

## Both sides of the loading spinner

- **[FlowDesk](https://github.com/ryanakml/flowdesk-ai)** is a shared WhatsApp inbox backed by a PostgreSQL message pipeline. It drafts replies from a knowledge base with pgvector. The [worker integration tests](https://github.com/ryanakml/flowdesk-ai/blob/main/apps/worker/src/vertical-slice.integration.test.ts) show how the pipeline handles 100 replays of the same inbound webhook.
- **[Wabrix](https://github.com/ryanakml/wabrix)** is a separate WhatsApp support app built with Next.js, Convex, Clerk, and Cloudflare Workers. It drafts replies from a team's knowledge base and supports operator handoff. [Open the demo](https://wabrix.nylo.me/).
- **[Deadbolt](https://github.com/ryanakml/deadbolt)** is a collaborative Go and PostgreSQL workflow engine in its final release phase. [Worker leases](https://github.com/ryanakml/deadbolt/blob/main/internal/worker/lease.go) track who owns a run so it can recover when a worker disappears. [Open the dashboard](https://deadbolt.nylo.me/).

## Sometimes I fix other people's edge cases

I’ve authored **12 merged pull requests across 11 upstream open-source projects**.

- **[OpenHands #12223](https://github.com/OpenHands/OpenHands/pull/12223)** added loading skeletons to chat and made conversation routing more stable.
- **[Mastra #15346](https://github.com/mastra-ai/mastra/pull/15346)** fixed tool approval rules defined as functions and added regression tests.
- **[Celery #10739](https://github.com/celery/celery/pull/10739)** fixed how spawned workers expand `~` in `--workdir`.

[More merged pull requests](https://github.com/search?q=author%3Aryanakml+is%3Apr+is%3Amerged+-user%3Aryanakml&type=pullrequests)
