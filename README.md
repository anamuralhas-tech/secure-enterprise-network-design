# Secure Enterprise Network Design

This repository documents the design of a secure and redundant enterprise network infrastructure created for a two-site business environment.

The project was developed as a complete network design case study, combining operational requirements, topology analysis, IP planning, equipment selection, segmentation, physical infrastructure, continuity strategy, and investment analysis.

## Project Context

The network was designed for a small to medium-sized business with:

- a headquarters in Lisbon
- a branch office in Porto
- departmental segmentation requirements
- sensitive operational data
- dependency on continuous connectivity
- need for secure inter-site communication
- long-term sustainability and scalability

## Project Focus

This design project covers the following areas:

- requirements analysis
- physical and logical topology selection
- hierarchical network design
- VLAN-based segmentation
- subnetting and IP addressing plan
- site-to-site VPN design
- WAN redundancy
- firewall and switch selection
- server, NAS, and backup strategy
- Wi-Fi guest isolation
- CCTV and access control integration
- structured cabling and rack planning
- security policies based on deny-by-default logic
- CAPEX, OPEX, and five-year investment analysis

## Objectives

The main objective of this project was to design a coherent enterprise network that could support:

- business continuity
- internal segmentation
- secure communication between sites
- protection of sensitive information
- future growth
- operational efficiency
- realistic financial planning

## Technical Scope

### Network Architecture
- hierarchical star topology at headquarters
- simplified local topology at branch office
- logical segmentation by VLAN
- inter-site connectivity through VPN

### Addressing and Segmentation
- private IPv4 addressing plan
- VLAN-based departmental separation
- gateway planning
- structured subnetting

### Active Infrastructure
- perimeter firewalls
- Layer 3 core switching
- PoE+ access switching
- access points
- NAS
- enterprise server platform

### Passive Infrastructure
- Cat6A structured cabling
- fiber backbone
- patch panels
- rack and mini-rack organization
- standards-aligned physical planning

### Security and Continuity
- deny-by-default model
- ACL-oriented segmentation
- ISP redundancy
- UPS planning
- backup retention strategy
- monitoring and event logging

## What This Repository Shows

This repository is intended to demonstrate:

- enterprise network design thinking
- ability to translate business requirements into technical architecture
- understanding of segmentation and secure communication models
- capacity to justify infrastructure choices
- structured technical documentation skills
- awareness of lifecycle, resilience, and investment planning

## Repository Structure

```text
secure-enterprise-network-design/
├── README.md
├── docs/
│   ├── case-study/
│   ├── sanitized-version/
│   └── supporting-notes/
├── images/
│   ├── topology/
│   ├── vlan-design/
│   ├── addressing/
│   ├── physical-layout/
│   └── budget/
└── notes/
    ├── overview.md
    ├── design-decisions.md
    └── technical-scope.md

## Documentation Note

The original academic document contains contextual references that may be revised before full publication. For that reason, this repository is being prepared in stages, starting with a public project overview and technical design structure.

## Status

In progress — public-facing project structure and documentation are being prepared.
