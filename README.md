# Xcel Energy (xcel-energy)

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

Xcel Energy is a major U.S. electricity and natural gas utility holding company headquartered in Minneapolis, Minnesota, providing service to approximately 3.7 million electricity customers and 2.1 million natural gas customers across eight Midwestern and Western states: Colorado, Minnesota, Texas, New Mexico, North Dakota, South Dakota, Michigan, and Wisconsin. Xcel Energy operates a developer portal at developer-apim.aws.xcelenergy.com that organizes APIs across customer account management, billing, payments, product and service offerings, and request service. The company provides Green Button Connect My Data APIs based on the ESPI (Energy Services Provider Interface) standard developed by NAESB, enabling authorized third-party applications to access customer energy usage data via OAuth 2.0. Xcel Energy also supports IEEE 2030.5 protocol on newer Itron Gen 5 Riva smart meters for direct local-network access to real-time energy data including solar production. Beyond data APIs, Xcel Energy is a Fortune 500 company investing in clean energy, grid modernization, electric vehicle programs, demand response, and renewable energy interconnection.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/xcel-energy/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Electric Utility, Energy, Energy Data, Green Button, Natural Gas, Smart Grid, Smart Meter, Utility, ESPI, IEEE 2030.5

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-03

## APIs

### Xcel Energy Green Button Connect My Data API
Green Button Connect My Data API based on the ESPI (Energy Services Provider Interface) standard developed by NAESB. Enables authorized third-party applications to access customer electricity and natural gas usage data from Xcel Energy smart meters. Supports RESTful access to metered resource data including usage intervals, billing data, and meter readings. Customer authorization is granted via OAuth 2.0 and follows the Green Button Connect specification used by utilities across North America.

**Human URL:** [https://developer-apim.aws.xcelenergy.com/](https://developer-apim.aws.xcelenergy.com/)

#### Tags:

 - Energy Data, Green Button, ESPI, Smart Meter, Usage Data, OAuth 2.0

#### Properties

- [Documentation](https://developer-apim.aws.xcelenergy.com/)
- [DeveloperPortal](https://developer-apim.aws.xcelenergy.com/)
- [Authentication](https://developer-apim.aws.xcelenergy.com/login)
- [OpenAPI](openapi/xcel-energy-green-button-api.yaml)

### Xcel Energy Smart Meter IEEE 2030.5 API
IEEE 2030.5 compliant API server built into Itron Gen 5 Riva smart meters deployed by Xcel Energy. Provides real-time and time-delineated energy usage data including solar production information directly from the meter device on the local network. Supports meter reading, usage monitoring, and demand response integration following the Smart Energy Profile 2.0 (IEEE 2030.5) specification.

**Human URL:** [https://developer-apim.aws.xcelenergy.com/](https://developer-apim.aws.xcelenergy.com/)

#### Tags:

 - IEEE 2030.5, Smart Meter, Energy Usage, Solar, Demand Response, Local Network

#### Properties

- [Documentation](https://developer-apim.aws.xcelenergy.com/)
- [DeveloperPortal](https://developer-apim.aws.xcelenergy.com/)
- [OpenAPI](openapi/xcel-energy-smart-meter-api.yaml)

## Common Properties

- [DeveloperPortal](https://developer-apim.aws.xcelenergy.com/)
- [Portal](https://developer-apim.aws.xcelenergy.com/)
- [SignUp](https://developer-apim.aws.xcelenergy.com/register)
- [Login](https://developer-apim.aws.xcelenergy.com/login)
- [TermsOfService](https://developer-apim.aws.xcelenergy.com/terms)
- [PrivacyPolicy](https://www.xcelenergy.com/privacy_policy)
- [Support](https://www.xcelenergy.com/contact_us)
- [LinkedIn](https://www.linkedin.com/company/xcel-energy)
- [X](https://twitter.com/xcelenergy)
- [YouTube](https://www.youtube.com/user/XcelEnergyVideo)

## Features

| Name | Description |
|------|-------------|
| Green Button Connect My Data | OAuth 2.0 authorized API access to customer electricity and natural gas usage data following the ESPI standard. |
| IEEE 2030.5 Smart Meter API | Direct local-network access to real-time energy data including solar production from Itron Gen 5 Riva meters. |
| Customer Account Management | API category covering customer account profile, preferences, and service management. |
| Billing & Billing Account Management | API category for billing data, statements, and billing account operations. |
| Payments & Payment Services | API category for payment processing and payment service operations against customer accounts. |
| Product & Service Offerings | API category covering Xcel Energy product and service catalog and program enrollment. |
| Request Service & Help | API category for service requests, support workflows, and customer help operations. |
| Smart Meter Data | Interval and billing-quality energy usage data captured from Xcel Energy smart meters across electricity and natural gas. |
| Demand Response Integration | Programs that allow utilities and third parties to coordinate load reduction events with smart meter and DER endpoints. |
| Solar Interconnection Data | Solar production data exposed through smart meter endpoints for customers with on-site photovoltaic systems. |

## Use Cases

| Name | Description |
|------|-------------|
| Energy Management Applications | Third-party apps that help customers track and reduce electricity and natural gas usage. |
| Solar Monitoring | Applications that track on-site solar production and consumption from IEEE 2030.5 smart meters. |
| Home Energy Automation | Smart home and HVAC systems that automate energy use based on real-time meter data. |
| Sustainability Reporting | Commercial customers reporting carbon and energy data for ESG and sustainability disclosures. |
| Building Performance Benchmarking | Whole-building energy benchmarking for ENERGY STAR Portfolio Manager and similar tools. |
| Demand Response Programs | Aggregators and DER providers integrating with utility dispatch signals. |
| Electric Vehicle Charging Optimization | EV charging applications that schedule charging based on time-of-use rates and grid conditions. |
| Research and Policy Analysis | Academic and policy research on energy consumption patterns and decarbonization. |

## Integrations

| Name | Description |
|------|-------------|
| Green Button Alliance | Certified Green Button Connect My Data implementation interoperable with the Green Button ecosystem. |
| NAESB ESPI | Implements the North American Energy Standards Board Energy Services Provider Interface standard for energy usage data. |
| IEEE 2030.5 | Smart Energy Profile 2.0 standard implemented on Itron Gen 5 Riva meters for local device APIs. |
| Itron | Smart meter deployments use Itron Gen 5 Riva devices that host the IEEE 2030.5 server. |
| ENERGY STAR Portfolio Manager | Whole-building benchmarking workflows can consume Green Button data for commercial customers. |
| OAuth 2.0 | Authorization framework used for customer-consented access to Green Button Connect My Data. |

## Solutions

| Name | Description |
|------|-------------|
| Residential Customers | Residential energy usage, billing, and program enrollment across electricity and natural gas service. |
| Business Customers | Commercial and industrial customer programs, rates, and aggregated usage data. |
| Third-Party Service Providers | Authorized energy management, demand response, and sustainability service providers consuming Green Button data. |
| Trade Partners | Contractors, installers, and program partners delivering energy efficiency and renewable installations. |
| Researchers and Policy Analysts | Anonymized and customer-authorized data access for academic and policy research. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
