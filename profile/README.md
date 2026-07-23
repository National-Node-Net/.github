# National Node Net on GitHub

Welcome to the GitHub organisation for the **National Node Net**, an open-source project stewarded by the **National Digital Twin Programme (NDTP)** within the **Department for Business, Innovation, Science and Trade**.

The National Node Net provides the open-source infrastructure that enables organisations to establish trusted, interoperable data-sharing networks. Designed to be collaborative and community-driven, the project welcomes participation from across government, industry, academia and the wider open-source community.

Our goal is to provide a common foundation for secure, policy-driven data sharing while allowing organisations to retain ownership, governance and control of their own data.

---

## What is the National Node Net?

The National Node Net is an open, federated ecosystem that enables organisations to exchange information securely without requiring data to be centralised.

Rather than creating a single national platform, the National Node Net provides the infrastructure, trust framework and interoperability standards that allow independently operated organisations to participate in governed data-sharing networks.

The project is:

- Open source
- Cloud agnostic
- Deployable using Infrastructure as Code (IaC)
- Built around open standards and interoperability
- Governed through explicit trust relationships
- Designed to scale from local collaboration to national interoperability

---

## Architecture

The National Node Net is built from three complementary concepts.

### Node

A **Node** is the foundational deployment unit operated by an organisation. Nodes enable organisations to:

- Participate in trusted data-sharing networks
- Exchange information securely with other organisations
- Apply governance and policy locally
- Integrate existing business systems without centralising data

Every participating organisation operates one or more Nodes.

### Node Net

A **Node Net** is a governed network of interoperable Nodes operating within a shared trust framework.

Each Node Net establishes:

- Trusted organisational identities
- Common governance rules
- Shared communication standards
- Policy-driven data exchange

Node Nets can be created for individual programmes, sectors, regions or communities with shared information requirements.

### National Node Net

The **National Node Net** connects multiple Node Nets together through a common trust framework, enabling interoperability between independently governed communities while allowing each to retain its own governance arrangements.

This federated approach allows collaboration to scale without introducing a single central authority for operational data.

---

## Core Components

The National Node Net is composed of a collection of open-source components, each maintained within its own repository.

These include:

- **Federator** – Enables trusted communication between Nodes and establishes federated trust relationships.
- **Management Node** – Manages trust domains and governs participation within a Node Net.
- **Connect Extract Components** – Integrate existing organisational systems with a Node.
- **Secure Agent** – Provides secure storage and controlled exposure of shared information.
- **Access Services** – Support organisational identity and policy-based access control.
- **Policy Services** – Enable consistent policy evaluation and enforcement across participating organisations.

Supporting repositories also provide deployment tooling, monitoring, observability, logging, governance utilities and reference implementations.

---

## Deployment

The National Node Net is designed to be cloud agnostic and deployed using Infrastructure as Code.

Reference deployment assets are available for multiple cloud platforms, with reusable deployment templates, configuration guidance and operational documentation provided throughout this organisation.

---

## Documentation

Documentation is inspired by the Diátaxis framework and includes:

- **Getting Started** – Learn the concepts and deploy your first Node.
- **How-to Guides** – Practical deployment and operational guidance.
- **Reference** – Technical documentation, APIs and configuration.
- **Explanation** – Architecture, governance and design decisions.

---

## Contributing

The National Node Net is an open-source project and welcomes contributions from across the public sector, private sector, academia and the wider open-source community.

Whether you're deploying a Node, contributing code, improving documentation or proposing new capabilities, we'd love to hear from you. Repository-specific contribution guidance is available within each project.

---

## Licensing

Unless otherwise stated, source code is released under the **Apache License 2.0**. Documentation and other content are published under the **Open Government Licence v3.0**.
