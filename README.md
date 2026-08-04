# Clearwave (clearwave-intake)

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

Clearwave is a patient revenue-cycle and self-service engagement platform for healthcare practices, covering online scheduling, self-service registration and intake, multi-factor insurance eligibility verification, and patient payments. The platform powers self-service patient check-in across kiosk, tablet, and mobile, and is used by thousands of multi-specialty healthcare locations nationwide.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/clearwave-intake/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/clearwave-intake/refs/heads/main/apis.yml)

## Access Model — Partner-Gated (No Public Developer API)

Clearwave does **not** publish an open, self-service developer API. There is no public developer portal, no downloadable OpenAPI definition, and no documented public WebSocket API. Instead, Clearwave connects to more than 50 electronic health record (EHR) and practice management (PM) systems through **formal, partner-gated API license and integration agreements**. As Clearwave states on its integrations page, it "has formal application program interface (API) license or partnership agreements with the following leading electronic health record companies."

Integration partners include athenahealth, NextGen Healthcare, eClinicalWorks, Modernizing Medicine (ModMed), Veradigm, Nextech, Greenway, Compulink, AdvancedMD, and Unlimited Systems, among others. Appointments, patient demographics, eligibility results, and payments flow bidirectionally between Clearwave and the practice's EHR/PM in real time, with no manual re-entry.

To integrate with Clearwave you must engage their team directly; there is no public sign-up or key issuance. Pricing is quote-based (contact sales), typically structured around practice size, patient volume, and selected engagement features, plus implementation and onboarding fees.

The APIs listed below are **logical capability areas modeled** from Clearwave's public product documentation. They are marked `endpointsModeled: true` and do **not** represent publicly documented endpoints, base URLs, or request/response schemas. No OpenAPI, Postman collection, plans, rate-limit, or FinOps artifacts are included because no public, sourced technical surface exists to describe.

## Tags

- Healthcare
- Patient Access
- Revenue Cycle
- Patient Check-In
- Insurance Eligibility
- Scheduling
- Patient Payments
- EHR Integration
- Partner API

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## APIs (Modeled Capability Areas)

### Clearwave Check-In API

Self-service patient check-in and registration — kiosk, tablet, and mobile intake that captures demographics, consent forms, and identity, then writes the completed registration back to the practice's EHR/PM.

- **Human URL:** [https://www.clearwaveinc.com/patient-check-in-system/](https://www.clearwaveinc.com/patient-check-in-system/)
- **Endpoints:** Modeled (partner-gated; no public endpoints documented)

### Clearwave Eligibility API

Multi-factor insurance eligibility and benefits verification run automatically as part of check-in, returning coverage status, plan details, and patient responsibility.

- **Human URL:** [https://www.clearwaveinc.com/health-insurance-eligibility-verification/](https://www.clearwaveinc.com/health-insurance-eligibility-verification/)
- **Endpoints:** Modeled (partner-gated; no public endpoints documented)

### Clearwave Scheduling API

Online and self-service appointment scheduling where every booking, cancellation, and reschedule syncs automatically to the practice management system and EHR.

- **Human URL:** [https://www.clearwaveinc.com/patient-scheduling/](https://www.clearwaveinc.com/patient-scheduling/)
- **Endpoints:** Modeled (partner-gated; no public endpoints documented)

### Clearwave Patients API

Bidirectional patient demographic and record synchronization between Clearwave and 50+ EHR/PM systems, keeping patient data consistent across the practice's systems in real time.

- **Human URL:** [https://www.clearwaveinc.com/integrations/](https://www.clearwaveinc.com/integrations/)
- **Endpoints:** Modeled (partner-gated; no public endpoints documented)

### Clearwave Payments API

Point-of-service and self-service patient payment capture tied to eligibility-derived patient responsibility, posting balances and payments back to the practice's revenue-cycle systems.

- **Human URL:** [https://www.clearwaveinc.com/patient-engagement-platform/](https://www.clearwaveinc.com/patient-engagement-platform/)
- **Endpoints:** Modeled (partner-gated; no public endpoints documented)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/clearwave-corporation)
- [Website](https://www.clearwaveinc.com/)
- [Documentation](https://www.clearwaveinc.com/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
