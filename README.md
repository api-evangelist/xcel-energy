# Xcel Energy (xcel-energy)
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
