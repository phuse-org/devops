<img align="right" width="250" height="250" src="https://github.com/phuse-org/devops/blob/main/assets/PharmaDevOps.png?raw=true"> 

# PharmaDevOps

Continuous Integration and Continuous Delivery (CICD) tool library for integration testing,
deployment and releases of R and Python codebases for clinical reporting

## Purpose

In 2023 PHUSE released the [Open Source E2E guidance](https://github.com/phuse-org/E2E-OS-Guidance),
providing high level guidance and talking points for using and collaborating on open source code, with a focus
on R packages. This guidance referenced several tools, but stops short of creating an annotated library of
Continuous Integration and Continuous Delivery (CICD) tools to make developers more efficient and code more
robust.

We believe there remains a gap between the numerous tools across gh-actions (a CICD syntax used with
Github), R packages and general recommendations, and what is most relevant to late stage drug development
packages. Work has been done within the pharmaverse to bring the CICD tooling used in Nest to support other
package families like admiral, but this is largely driven based on principles defined and deployed initially by
Roche. There is a fundamental gap in terms of having an inclusive company-independent set of guidance and
off the shelf tooling to apply CICD in the specific context of R and python packages used in clinical reporting.
This is an area where homogeneity would not only improve the reliability of our code and productivity of our
developers, but would also help set the industry on a trajectory that would allow better integration with pan-
company efforts to validate packages used for clinical reporting.

## Project scope

Landscape of what CICD is used today across the pharmaverse, and key pre-named reference
packages outside the pharmaverse used in clinical reporting (e.g. ggplot2, survminer, etc)

- Summarise integration deployment and release pain points within these R packages
- Connect with the R Validation Hub and vendor tooling (e.g. Atorus openvalidate) to understand what key
devops tooling could be applied to packages to accelerate validation
- Deliverable 1: Summarise the state of DevOps in the pharmaverse today, with proposals on key tools
used already, and where there are gaps.
- Deliverable 2: Develop the existing CICD library used in some pharmaverse R packages (referenced
earlier in this proposal) to:
- Deliver a recommended suite of CICD tools for R and Python packages that improve developer
efficiency, and ensure code is well tested and consistent when merged to branch.
- Provide off the shelf configurations to use tools like managed docker images locally or via Github codespaces to simplify environment management

## Planned deliverables

- 0-6 months - Prepare Deliverable 1, aiming for abstract ready for PHUSE US Connect 2024 (assumption
close is September 2023)
- At 8 months – V1.0 of suite/library of CICD tools released
- 8-12 months - Support adoption across pharmaverse and biostatistics packages where maintainers are
willing to collaborate
- 12 months - Close our V1.0 with hackathon in lead up to PHUSE CSS 2024

## Team

- Dinakar Kulkarni (@cicdguy)
- Ben Straub (@bms63)
- James Black (@epijim)
