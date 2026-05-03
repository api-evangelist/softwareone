# SoftwareOne

SoftwareOne is a global software and cloud solutions provider that helps organizations acquire, manage, and optimize their technology investments. The SoftwareOne Marketplace Platform is a comprehensive digital marketplace connecting vendors and clients, enabling software procurement, license management, cloud spend optimization, and partner ecosystem integration. The platform exposes REST APIs for clients and partners to automate software purchasing, subscription management, reporting, and catalog operations.

**URL:** [SoftwareOne Platform Documentation](https://docs.platform.softwareone.com/)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Marketplace, Software Procurement, Cloud Management, License Management, SaaS

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-05-02

## APIs

### SoftwareOne Marketplace Platform API
The core API for the SoftwareOne digital marketplace, enabling programmatic access to the product catalog, subscription management, order processing, and billing information for clients and partners.

**Human URL:** [Platform Documentation](https://docs.platform.softwareone.com/)

**Tags:** Marketplace, Catalog, Subscriptions, Orders, Billing

#### Properties

- [Documentation](https://docs.platform.softwareone.com/)
- [Website](https://www.softwareone.com/)

---

### SoftwareOne Cloud Spend Optimization API
APIs for tracking and optimizing cloud spend across AWS, Azure, and Google Cloud environments, providing usage analytics, rightsizing recommendations, and reservation management.

**Human URL:** [Cloud Cost Management](https://www.softwareone.com/en/solutions/cloud/cloud-cost-management)

**Tags:** Cloud Cost Management, FinOps, AWS, Azure, Google Cloud

---

### SoftwareOne Software Asset Management API
APIs for SAM workflows including license inventory, compliance reporting, entitlement reconciliation, and vendor audit preparation across on-premises and cloud software.

**Human URL:** [Software Asset Management](https://www.softwareone.com/en/solutions/software-asset-management)

**Tags:** Software Asset Management, License Management, SAM, Compliance

---

## Common Resources

- [SoftwareOne Website](https://www.softwareone.com/)
- [Platform API Documentation](https://docs.platform.softwareone.com/)
- [Solutions Overview](https://www.softwareone.com/en/solutions)
- [Partner Program](https://www.softwareone.com/en/partners)
- [SoftwareOne Blog](https://www.softwareone.com/en/blog)
- [SoftwareOne on LinkedIn](https://www.linkedin.com/company/softwareone)
- [SoftwareOne on X](https://twitter.com/SoftwareOne)

## Artifacts

### JSON Schema

- [Order Schema](json-schema/softwareone-order-schema.json) — Schema for marketplace orders including client, product lines, and pricing
- [Subscription Schema](json-schema/softwareone-subscription-schema.json) — Schema for active software subscriptions with billing and renewal terms

### JSON Structure

- [Order Structure](json-structure/softwareone-order-structure.json) — Field-level documentation for the Order entity

### JSON-LD

- [SoftwareOne Context](json-ld/softwareone-context.jsonld) — JSON-LD context mapping marketplace vocabulary to schema.org and GoodRelations ontology terms

### Examples

- [Order Example](examples/softwareone-order-example.json) — Sample completed Microsoft 365 purchase order
- [Subscription Example](examples/softwareone-subscription-example.json) — Sample active annual Microsoft 365 E3 subscription

### Vocabulary

- [SoftwareOne Vocabulary](vocabulary/softwareone-vocabulary.yml) — Domain vocabulary covering marketplace concepts, license management, cloud cost optimization, and partner ecosystem terms

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
