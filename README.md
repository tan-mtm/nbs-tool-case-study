# NbS Tool

**Product leadership and quality assurance for an end-to-end Nature-based Solutions platform**

[Live product](https://nbstool-beta.scenecoalition.org/) · [Backend analysis source](https://github.com/g-adzan/nbstool_v3) · [LinkedIn](https://www.linkedin.com/in/intan-nilaputri/)

## Overview

NbS Tool helps frontline organisations in Southeast Asia move from early site screening to a structured, monitorable Nature-based Solutions project. The product connects geospatial scoping, baseline analysis, pathway selection, project documentation, portfolio management, and measurement, reporting, and verification (MRV) in one workflow.

The platform was developed under the SCeNe Coalition's ASEAN-NbS Tool project with the aim of making climate, nature, and community project data more usable and defensible.

## My role

**Product Lead and Quality Assurance — World Resources Institute**

I worked at the intersection of users, domain experts, designers, and engineers to help turn a complex technical methodology into a coherent digital product. My responsibilities included:

- Shaping the product scope and end-to-end user journey.
- Translating programme and domain requirements into product requirements and acceptance criteria.
- Coordinating priorities and feedback across stakeholders.
- Reviewing product behaviour, usability, and workflow consistency.
- Planning and executing QA across core user journeys.
- Tracking defects, validating fixes, and supporting release readiness.
- Helping ensure the experience communicated technical results clearly without overstating recommendations.

## The product challenge

Nature-based Solutions projects often require teams to move between disconnected mapping tools, datasets, spreadsheets, narrative documents, and monitoring systems. This creates friction for frontline organisations and makes project evidence harder to review, compare, and maintain.

NbS Tool addresses that fragmentation by carrying one project boundary through a connected workflow:

1. **Scope** — locate a site, explore thematic layers, and define an Area of Interest.
2. **Analyse** — establish environmental and social baselines and examine relevant threats.
3. **Select** — evaluate conditional Protect, Manage, or Restore pathways for supported ecosystems.
4. **Document** — turn structured analysis into standardised project documentation.
5. **Manage** — organise projects, collaborators, files, and project status in one portfolio.
6. **Monitor** — define indicators, record evidence, and track progress through an MRV dashboard.

## Product capabilities

- Interactive geospatial exploration and Area of Interest creation.
- Baseline analysis across climate, nature, and people dimensions.
- Threat profiling for issues such as deforestation, fire, and flooding.
- Conditional pathway selection for forest, mangrove, and peatland interventions.
- Standardised document generation for project development workflows.
- Multi-project portfolio and collaboration features.
- Monitoring plans, indicator tracking, evidence capture, and reporting.
- Methodology documentation connecting results to their underlying logic.

## QA focus

Quality assurance for this product required more than checking individual screens. The core risk was preserving meaning and continuity as project information moved through a long, data-dependent workflow. My QA focus included:

- End-to-end journey validation from map exploration through MRV.
- Functional and regression testing of critical workflows.
- Validation of handoffs between analysis stages and user-facing outputs.
- Edge-case testing for geospatial inputs, empty states, incomplete data, and conditional pathways.
- Review of terminology, units, labels, and explanatory content.
- Cross-browser and responsive experience checks.
- Defect triage and fix verification with the delivery team.

## Technical context

The public backend analysis repository uses Python and Jupyter notebooks for geospatial screening. Its documented stack includes Rasterio/GDAL, GeoPandas, Shapely, Pandas, and NumPy. The analysis accepts an Area of Interest, intersects it with configured raster and vector layers, and produces structured results for downstream product experiences.

I am presenting this work as the Product Lead and QA contributor. Engineering implementation is credited to the project team and repository contributors.

## Links and attribution

- Product: [nbstool-beta.scenecoalition.org](https://nbstool-beta.scenecoalition.org/)
- Public backend repository: [g-adzan/nbstool_v3](https://github.com/g-adzan/nbstool_v3)
- Organisation: [World Resources Institute](https://www.wri.org/)
- Coalition: [SCeNe Coalition](https://scenecoalition.org/)
