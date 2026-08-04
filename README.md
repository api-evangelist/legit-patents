# Legit Patents

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Legit (listed by Seedcamp as "Legit Patents", 2016 cohort, legit.ai) was a Cambridge, Massachusetts startup applying natural-language processing to scientific and patent literature, which it developed into an on-demand expert network for the life sciences. Its product let pharmaceutical, biotech and medical-device teams search a corpus the company described as more than two million experts backed by roughly forty million data points, then pay a flat fee per reply to message key opinion leaders directly instead of scheduling calls — marketed for R&D, business development and licensing (BD&L), strategic alliances and integration management.

**Status: defunct.** Substantive legit.ai content disappears from the web archive after 2021, the LinkedIn company page returns HTTP 404, and the legit.ai domain is now parked on GoDaddy/Afternic and listed for sale. No public API, developer portal, documentation or machine-readable specification was ever published.

Because the parking page is a catch-all, every path on legit.ai — including `/.well-known/security.txt`, `/llms.txt` and `/openapi.json` — returns HTTP 200. Those are false positives and were deliberately **not** captured as artifacts. See [review.yml](review.yml) for the full probe record.

Backed by: seedcamp
