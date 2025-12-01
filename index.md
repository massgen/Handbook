---
layout: default
title: Home
nav_order: 1
description: "MassGen Contributor Handbook - Multi-Agent Scaling System for GenAI"
permalink: /
---

# MassGen Contributor Handbook

Multi-Agent Scaling System for GenAI

Last Updated: November 2025

---

## Welcome to MassGen

Thank you for your interest in contributing to MassGen. This handbook is your comprehensive guide to understanding the project, finding your place in the community, and making meaningful contributions.

Whether you are a researcher with ideas, a developer who loves to code, a writer who can document, or a marketer who builds communities, there is a place for you here.


---


## MassGen team Workflow

The following diagram illustrates  MassGen team workflow.

```mermaid
graph TB
    subgraph "Research Meeting"
        A1[1. Identify and refine<br/>long/short term goals]
        A2[2. Propose case studies<br/>around short term goals]
        A3[3. Propose features<br/>based on case studies]
        A1 --> A2 --> A3
    end

    subgraph "Create Issues"
        B1[Case Study Issues]
        B2[Feature Issues]
        B3[Bug Issues]
    end

    subgraph "Development Pipeline"
        C1[Browse/Claim Issues]
        C2[Fork, Clone, Setup Branch]
        C3[Implement and Test]
        C4[Submit PR]
        C5[Review and Merge to dev]
        C1 --> C2 --> C3 --> C4 --> C5
    end

    A3 --> B1
    A3 --> B2
    B3

    B1 --> C1
    B2 --> C1
    B3 --> C1

    C5 --> D[Update Documentation<br/>on GitHub]
    D --> E[Merge dev to main<br/>Release]
    E --> F[Announcements<br/>X, YouTube, LinkedIn, Discord]

    subgraph "Concurrent Activities"
        G[Daily Sync 5:30pm PT<br/>Track progress]
        H[Marketing<br/>Recruiting, Partnerships<br/>Community building]
    end

    style A1 fill:#e1f5ff
    style A2 fill:#e1f5ff
    style A3 fill:#e1f5ff
    style C2 fill:#fff3e1
    style E fill:#e8f5e9
    style G fill:#f3e5f5
    style H fill:#fff9c4
```


---


## Communication and Collaboration

### Daily Sync Meetings

**When:** 5:30pm-6:00pm PST, every day

**Purpose:**
- Share progress updates from each track owner
- Coordinate across all tracks (research, dev, docs, marketing)
- Identify and address blockers
- Align on priorities for the next day



### Research Meetings

**When:** 6:00pm-7:00pm PST, on demand

**Purpose:**
  - Share well-motivated research problems and intuitive solutions
  - Identify problems for MassGen, propose case studies, and generate features



---

## Getting Started 


1. **Join Discord** - Connect with the community at [discord.gg/VVrT2rQaz5](https://discord.gg/VVrT2rQaz5)
2. **Introduce Yourself** - Post in the #massgen channel and let us know your interests
3. **Join the meeting** - Request meeting link in #massgen channel and attend your first meeting as an observer

---


## Ready to contribute?

4. **Choose Your Track** - Select from Research, Case Studies, Marketing, or Development
5. **Contact Track Owner** - Reach out to the appropriate track owner listed at bottom
6. **Start Contributing** - Follow the specific guide for your chosen track


---


## Roles & Contact

MassGen welcomes contributions across four distinct tracks. Each track has its own workflow, contacts, and contribution style. Pick the one that matches your skills and interests.

| Track | What You Do | Name | Contact (Discord) |
|-------|-------------|------|-------------------|
| **Founder** | Lead project vision and strategy | Chi | sonichi |
| **Research** | Propose features at research meetings | Yu | crinvo |
| **Case Studies** | Document real-world usage examples | Aaron | sealover8336 |
| **Development** | Code, tests, docs, bug fixes | Danrui, Nick | danrui2020, nickcrispino |
| **Documents** | Update documentation before releases | Henry | henry_weiqi |
| **Announcement** | Share releases on social media | Yu | crinvo |
| **Marketing** | Social media, content, partnerships | Justin | justin_zhang |
| **Onboarding** | Help new people become contributors | Justin, Nick, Yu | justin_zhang, nickcrispino, crinvo |


For detailed contact information, communication channels, and response times, see the [Contact Directory](resources#contact-directory)

**Full Team Directory:** See the [Team Spreadsheet](https://docs.google.com/spreadsheets/d/1pNmMOdEmqb6TKOPjhk3NBPJWCWMvTTDaq1FufLfL3j4/edit?gid=0#gid=0)

---

 [Next: Case Studies Guide](case-studies)