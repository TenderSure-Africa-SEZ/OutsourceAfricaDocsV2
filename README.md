# Trific User Guide

Trific (operated by TenderSure Africa SEZ Limited) is a B2B services marketplace that connects **Clients** (companies that need work done) with vetted **Service Providers** who deliver it, with **Management** overseeing the platform end to end.

This guide is organized around the three roles that use the platform day to day:

- **[Client](client/README.md)**: post work, review proposals, manage contracts, and pay for delivered services.
- **[Service Provider](service-provider/README.md)**: get vetted, find and apply to jobs, deliver work, and get paid.
- **[Management](management/README.md)**: Trific's internal team, who approve projects and contracts, oversee every account on the platform, and manage commission and payments for both Trific and its partner TenderSure.

## How the pieces fit together

The whole platform revolves around one lifecycle:

```
Client creates a Project
        │
        ▼
Management reviews and approves the Project
        │
        ▼
A Contract is created (amount, start/end dates)
        │
        ▼
Management approves the Contract
        │
        ▼
Client pays (deposit); Payment Status becomes "Paid"
        │
        ▼
Management creates a Job against the approved, paid Project
        │
        ▼
Service Providers browse the open Job and submit Proposals
        │
        ▼
Management closes the Job and picks a winning Service Provider from the Proposals
        │
        ▼
Management creates a Contract specific to that Service Provider (with Milestones)
        │
        ▼
The Service Provider accepts the Contract and starts work
        │
        ▼
The Service Provider submits a Milestone for review
        │
        ▼
Management reviews and approves the Milestone
        │
        ▼
The Client gives final sign-off on the Milestone
        │
        ▼
Management creates a Payment Batch for the approved Milestone
        │
        ▼
The Payment Batch is approved
        │
        ▼
Management downloads the batch CSV and pays it through the bank's internet banking portal
```

The first "Contract" in this chain (created right after project approval, and what the Client pays a deposit against) is a general commercial agreement at the **Project** level, and it doesn't yet name a Service Provider. The second Contract, created later once Management has picked a winner from the Job's Proposals, is the one that's actually **specific to a Service Provider** and carries the Milestones that get delivered and paid.

Every role's guide is written around this lifecycle from that role's point of view: start with [Client → Creating a Project](client/creating-a-project.md) to see the whole thing begin, then follow the same example through [Management → Reviewing Projects and Contracts](management/reviewing-projects-and-contracts.md) and [Management → Jobs & Create Job](management/jobs-and-create-job.md).

## A note on scope

Service provider **vetting/prequalification** (verifying a company's compliance documents such as tax compliance certificates, business permits, and registration papers before they can take on work) is handled on a separate **TenderSure Admin** portal, not covered in this guide. The Service Provider guide covers *submitting* vetting documents, but review and approval happens elsewhere.
