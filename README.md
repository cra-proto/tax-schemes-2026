# Tax schemes

*description of the project*

**Timeframe** 2026-05-08 - 2026-08-14

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/tax-schemes-2026](https://cra-test-arc.canada.ca/tax-schemes-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-05-22

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Scams and fraud - CRA)
    node4(Beware of tax schemes that promise to reduce your taxes)
    node1 --x node2
    node2 --> node3
    node3 --> node4
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/corporate/scams-fraud.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/campaigns/tax-schemes.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4 inscope
```
