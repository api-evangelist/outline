# Outline

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Outline is an open-source team knowledge base and wiki with a fully featured RPC-style REST API for programmatically managing documents, collections, teams, users, groups, comments, shares, attachments, and importing or exporting organizational knowledge. The main application itself is built on the same API it exposes publicly.

**Areas:** Knowledge Base · Wiki · Documents · Collaboration · Open Source · Team · Knowledge Management

## Outline on APIs.io

Everything profiled for Outline is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/outline/](https://apis.io/providers/outline/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [Outline Attachments API](https://apis.io/apis/outline/outline-attachments-api/) — `Attachments` represent a file uploaded to cloud storage. They are created before the upload happens from the client and store all the meta information such…
- [Outline Auth API](https://apis.io/apis/outline/outline-auth-api/) — `Auth` represents the current API Keys authentication details. It can be used to check that a token is still valid and load the IDs for the current user and…
- [Outline Collections API](https://apis.io/apis/outline/outline-collections-api/) — `Collections` represent grouping of documents in the knowledge base, they offer a way to structure information in a nested hierarchy and a level at which…
- [Outline Comments API](https://apis.io/apis/outline/outline-comments-api/) — `Comments` represent a comment either on a selection of text in a document or on the document itself.
- [Outline DataAttributes API](https://apis.io/apis/outline/outline-dataattributes-api/) — `DataAttributes` represent custom metadata fields that can be attached to documents. They allow workspaces to add structured data like status, priority, or…
- [Outline Documents API](https://apis.io/apis/outline/outline-documents-api/) — `Documents` are what everything else revolves around. A document represents a single page of information and always returns the latest version of the…
- [Outline Events API](https://apis.io/apis/outline/outline-events-api/) — `Events` represent an artifact of an action. Whether it is creating a user, editing a document, changing permissions, or any other action – an event is…
- [Outline Groups API](https://apis.io/apis/outline/outline-groups-api/) — `Groups` represent a list of users that logically belong together, for example there might be groups for each department in your organization. Groups can be…
- [Outline OAuthAuthentications API](https://apis.io/apis/outline/outline-oauthauthentications-api/) — `OAuthAuthentications` represent individual scoped authentications between Outline and an `OAuthClient`.
- [Outline Revisions API](https://apis.io/apis/outline/outline-revisions-api/) — `Revisions` represent a snapshot of a document at a point in time. They are used to keep track of editing and collaboration history – a document can also be…
- [Outline Shares API](https://apis.io/apis/outline/outline-shares-api/) — `Shares` represent authorization to view a document without being a member of the workspace. Shares are created in order to give access to documents…
- [Outline Stars API](https://apis.io/apis/outline/outline-stars-api/) — `Stars` represent a favorited document or collection in the application sidebar. Each user has their own collection of starred items.
- [Outline Templates API](https://apis.io/apis/outline/outline-templates-api/) — `Templates` represent reusable document templates that can be used as a starting point when creating new documents. Templates can be scoped to a specific…
- [Outline Users API](https://apis.io/apis/outline/outline-users-api/) — `Users` represent an individual with access to the knowledge base. Users can be created automatically when signing in with SSO or when a user is invited via…
- [Outline Views API](https://apis.io/apis/outline/outline-views-api/) — `Views` represent a compressed record of an individual users views of a document. Individual views are not recorded but a first, last and total is kept per…
- [Outline Access Requests API](https://apis.io/apis/outline/outline-access-requests-api/) — `AccessRequests` represent a request by a user for access to a document they do not currently have permission to view. The request can be approved or…
- [Outline File Operations API](https://apis.io/apis/outline/outline-file-operations-api/) — `FileOperations` represent background jobs for importing or exporting files. You can query the file operation to find the state of progress and any…
- [Outline OAuth Clients API](https://apis.io/apis/outline/outline-oauth-clients-api/) — `OAuthClients` represent OAuth clients that can be used to authenticate users with third-party services.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [outline](https://apis.io/servers/outline/outline/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Outline Agentic Access](https://apis.io/agentic-access/outline/outline-agentic-access/)

#### JSON Schema (38)

The data models the API reads and writes.

- [Ability](https://apis.io/schemas/outline/ability/)
- [AccessRequest](https://apis.io/schemas/outline/accessrequest/)
- [Attachment](https://apis.io/schemas/outline/attachment/)
- [Auth](https://apis.io/schemas/outline/auth/)
- [Collection](https://apis.io/schemas/outline/collection/)
- [CollectionGroupMembership](https://apis.io/schemas/outline/collectiongroupmembership/)
- [CollectionStatus](https://apis.io/schemas/outline/collectionstatus/)
- [Comment](https://apis.io/schemas/outline/comment/)
- [DataAttribute](https://apis.io/schemas/outline/dataattribute/)
- [DataAttributeDataType](https://apis.io/schemas/outline/dataattributedatatype/)
- [DataAttributeOptions](https://apis.io/schemas/outline/dataattributeoptions/)
- [Document](https://apis.io/schemas/outline/document/)
- [DocumentDataAttribute](https://apis.io/schemas/outline/documentdataattribute/)
- [DocumentInsight](https://apis.io/schemas/outline/documentinsight/)
- [Error](https://apis.io/schemas/outline/error/)
- [Event](https://apis.io/schemas/outline/event/)
- [FileOperation](https://apis.io/schemas/outline/fileoperation/)
- [Group](https://apis.io/schemas/outline/group/)
- [GroupMembership](https://apis.io/schemas/outline/groupmembership/)
- [Invite](https://apis.io/schemas/outline/invite/)
- [Membership](https://apis.io/schemas/outline/membership/)
- [NavigationNode](https://apis.io/schemas/outline/navigationnode/)
- [OAuthAuthentication](https://apis.io/schemas/outline/oauthauthentication/)
- [OAuthClient](https://apis.io/schemas/outline/oauthclient/)
- [Pagination](https://apis.io/schemas/outline/pagination/)
- …and 13 more published on APIs.io

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Outline Api Context](https://apis.io/jsonld/outline/outline-api/)
- [Outline Context](https://apis.io/jsonld/outline/outline-context/)

#### Examples (112)

Example requests and responses.

- [Accessrequestsapprove](https://apis.io/examples/outline/accessRequestsApprove/)
- [Accessrequestscreate](https://apis.io/examples/outline/accessRequestsCreate/)
- [Accessrequestsdismiss](https://apis.io/examples/outline/accessRequestsDismiss/)
- [Accessrequestsinfo](https://apis.io/examples/outline/accessRequestsInfo/)
- [Attachmentscreate](https://apis.io/examples/outline/attachmentsCreate/)
- [Attachmentsdelete](https://apis.io/examples/outline/attachmentsDelete/)
- [Attachmentsredirect](https://apis.io/examples/outline/attachmentsRedirect/)
- [Authconfig](https://apis.io/examples/outline/authConfig/)
- [Authinfo](https://apis.io/examples/outline/authInfo/)
- [Collectionsaddgroup](https://apis.io/examples/outline/collectionsAddGroup/)
- [Collectionsadduser](https://apis.io/examples/outline/collectionsAddUser/)
- [Collectionscreate](https://apis.io/examples/outline/collectionsCreate/)
- [Collectionsdelete](https://apis.io/examples/outline/collectionsDelete/)
- [Collectionsdocuments](https://apis.io/examples/outline/collectionsDocuments/)
- [Collectionsexport](https://apis.io/examples/outline/collectionsExport/)
- [Collectionsexportall](https://apis.io/examples/outline/collectionsExportAll/)
- [Collectionsgroupmemberships](https://apis.io/examples/outline/collectionsGroupMemberships/)
- [Collectionsinfo](https://apis.io/examples/outline/collectionsInfo/)
- [Collectionslist](https://apis.io/examples/outline/collectionsList/)
- [Collectionsmemberships](https://apis.io/examples/outline/collectionsMemberships/)
- [Collectionsremovegroup](https://apis.io/examples/outline/collectionsRemoveGroup/)
- [Collectionsremoveuser](https://apis.io/examples/outline/collectionsRemoveUser/)
- [Collectionsupdate](https://apis.io/examples/outline/collectionsUpdate/)
- [Commentscreate](https://apis.io/examples/outline/commentsCreate/)
- [Commentsdelete](https://apis.io/examples/outline/commentsDelete/)
- …and 87 more published on APIs.io

#### Collections (18)

Postman and Open Collection request collections.

- [Outline AccessRequests API](https://apis.io/collections/outline/open-outline-accessrequests-api/)
- [Outline AccessRequests Attachments API](https://apis.io/collections/outline/open-outline-attachments-api/)
- [Outline AccessRequests Auth API](https://apis.io/collections/outline/open-outline-auth-api/)
- [Outline AccessRequests Collections API](https://apis.io/collections/outline/open-outline-collections-api/)
- [Outline AccessRequests Comments API](https://apis.io/collections/outline/open-outline-comments-api/)
- [Outline AccessRequests DataAttributes API](https://apis.io/collections/outline/open-outline-dataattributes-api/)
- [Outline AccessRequests Documents API](https://apis.io/collections/outline/open-outline-documents-api/)
- [Outline AccessRequests Events API](https://apis.io/collections/outline/open-outline-events-api/)
- [Outline AccessRequests FileOperations API](https://apis.io/collections/outline/open-outline-fileoperations-api/)
- [Outline AccessRequests Groups API](https://apis.io/collections/outline/open-outline-groups-api/)
- [Outline AccessRequests OAuthAuthentications API](https://apis.io/collections/outline/open-outline-oauthauthentications-api/)
- [Outline AccessRequests OAuthClients API](https://apis.io/collections/outline/open-outline-oauthclients-api/)
- [Outline AccessRequests Revisions API](https://apis.io/collections/outline/open-outline-revisions-api/)
- [Outline AccessRequests Shares API](https://apis.io/collections/outline/open-outline-shares-api/)
- [Outline AccessRequests Stars API](https://apis.io/collections/outline/open-outline-stars-api/)
- [Outline AccessRequests Templates API](https://apis.io/collections/outline/open-outline-templates-api/)
- [Outline AccessRequests Users API](https://apis.io/collections/outline/open-outline-users-api/)
- [Outline AccessRequests Views API](https://apis.io/collections/outline/open-outline-views-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Outline — jsonschema rules](https://apis.io/rules/outline/outline-jsonschema-spectral-rules/)
- [Outline — openapi rules](https://apis.io/rules/outline/outline-openapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Outline Authentication](https://apis.io/security/outline/outline-authentication/)
- [Outline Domain Security](https://apis.io/security/outline/outline-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Outline Scopes](https://apis.io/scopes/outline/outline-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Outline Plans Pricing](https://apis.io/plans/outline/outline-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Outline Rate Limits](https://apis.io/rate-limits/outline/outline-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Outline Finops](https://apis.io/finops/outline/outline-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.getoutline.com/)
- [Documentation](https://docs.getoutline.com/s/guide)
- [Pricing](https://www.getoutline.com/pricing)
- [Changelog](https://www.getoutline.com/changelog)
- [Blog](https://www.getoutline.com/changelog)
- [GitHub](https://github.com/outline)

## API Evangelist rating

**Kin Score 36.0** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 57.0 |
| Contract governance | 24.2 |
| Operational transparency | 26.3 |
| Developer ergonomics | 23.8 |
| Access clarity | 18.4 |

**Agent readiness 58.7** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/outline/](https://apis.io/providers/outline/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Outline: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/outline/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
