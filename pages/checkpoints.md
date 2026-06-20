---
title: Data checkpoints
description:
background:
  img: /assets/images/checkpoints_banner.jpg
  by: CHUTTERSNAP
  href: https://unsplash.com/photos/five-green-plants-UmncJq4KPcA
permalink: /checkpoints/
toc: true
---

## Overview

![checkpoints]({{ '/assets/images/overview_checkpoints.png' | relative_url }})

## Preparation

{:.alert .alert-info .mt-3}
- Has the DMP been started?
- Is the team aware of the naming convention & folder structure?
- Are one or more team members responsible for each data checkpoint?
- Is it known who the data owner is? Are there any existing obligations regarding openness and/or FAIRness of the data?
- Which database/repository uploads are required by the reporting?
- Is there an agreed metadata approach?

### Is the team aware of the naming convention & folder structure?

These aspects should be agreed upon at either a team, project, or laboratory level before the project begins and documented somewhere, for example, in a lab Standard Operating Procedures (SOP) or a project DMP.
It must be compatible with the Collection Management System (CMS) where samples/data are located & how they are named/labelled.

### Are one or more team members responsible for each data checkpoint?

This can be noted in the DMP or another file, e.g. a spreadsheet.

### Is it known who the data owner is? Are there any existing obligations regarding openness and/or FAIRness of the data?

There may be multiple data owners. It may be that, according to agreements with partners, funders, etc., the data can never be shared _openly_ or _FAIRly_, or conversely, it must be shared _openly_ and _FAIRly_. If this is already agreed upon before the research begins, the data can be managed from the start with this in mind.
The situation must also be explained in the DMP.

### Which database/repository uploads are required by the reporting?

Open question - Can a general approach be decided upon (e.g., one database per type of data, etc.)?
If there is a required metadata standard for a required database, consider whether it is logical to use this metadata standard from the very beginning and note it in the DMP.


## Sample collection

{:.alert .alert-info .mt-3}
- Have the sampling techniques been written down?
- Have the sampling techniques been archived?
- Is it clearly noted in the sampling sheet where data and samples are stored or kept?
- Have the agreed naming convention & folder structure been followed?
- Has the sampling sheet been backed up?
- Is it necessary to update the DMP?

### Have the sampling techniques been written down?

The description of the sampling techniques does not need to be highly detailed. Reference to documentation (e.g., SIP, SAP, SOP, SVP) or mentioning, for example, filter method, volumes, etc., in the field forms of the sampling sheet is often sufficient. Alternatively, include the description in the DMP.
If there is a deviation from the described sampling techniques, e.g., for practical reasons, note this in the DMP as well.

### Have the sampling techniques been archived?

Pay attention to document and apply version control and use already existing templates where possible. Deposit this documentation in online repositories, e.g. [zenodo](https://zenodo.org/), or institute specific tools (INBO archive, INBO protocol helper) or cloud storage drives (INBO Google drive). If it is described in the DMP, ensure that the DMP is deposited in the Research Information Management System (RIMS) of your institute (INBO's [PURE](https://pureportal.inbo.be/nl/)).

### Is it clearly noted in the sampling sheet where data and samples are stored or kept?

So far, there is no official physical INBO archive for water samples, filters, or soil samples in cold storage. This means that the agreement is that matrix samples are only kept for the short term (<5 years). Usually, the samples are deposited at a place agreed upon with the laboratory technician, pending processing in the lab.
Most details about this can be included in the sampling sheet. This sampling sheet is must be compatible with the CMS and ensures that the eDNA samples can be imported into the database if a decision is made to archive them.

### Have the agreed naming convention & folder structure been followed?

The sample ID must follow a convention. At INBO we use the following: `year_project_sitecode_samplenumber`, e.g. `2024_dissco17748_kattenbeek03_005`.

Conventions:
- The sample ID must be lowercase
- The `year` must be in full
- The `samplenumber` must always consist of three digits as we never expect 1000 or more samples per location
- `sitecode` can be an acronym, a number, or a combination of both  and can be agreed per project.
- The `project` can be the project acronym, or the project acronym + the ID provided by the used Project Management System (PMS). This should be agreed upon generally.

### Has the sampling sheet been backed up?

As the sampling sheet is the key to understanding and using the data, it is crucial to back up a copy of it regularly, for example, on another drive.

### Is it necessary to update the DMP?

Have you changed something about the sampling techniques or conventions? Then the answer to the question is a fully YES: you need to **update** the DMP!

## Lab analyses

{:.alert .alert-info .mt-3}
- Have all relevant lab protocol(s) been written down?  
- Have copies of the lab protocol(s) been archived?
- Have the samples all been named and stored as they should be? 
- Will the DNA specimens be deposited in a collection?
- Has the sampling sheet been backed up?
- Has the raw (DNA) data been archived?
- Have the agreed naming convention & folder structure been followed? 
- Is it necessary to update the DMP?

## Bioinformatics

{:.alert .alert-info .mt-3}
- Have the analysis protocols/steps been written down?
- Have copies of the analysis protocols/steps been archived?
- Have copy/copies of the reference database(s) been archived OR has their version/publication date been noted? 
- Have copy/copies of the “operational data” been archived?
- Is it useful to also archive other data?
- Have the agreed naming convention & folder structure been followed?  
- Is it necessary to update the DMP?

## Dataprocessing

{:.alert .alert-info .mt-3}
- Have the analysis protocols/steps been written down?   
- Have copies of the analysis protocols/steps been archived?
- Have copy/copies of the “operational data” been archived?
- Is it useful to also archive a copy of certain data?
- Have the agreed naming convention & folder structure been followed? 
- Is it necessary to update the DMP?

## Output/data publication

{:.alert .alert-info .mt-3}
- Is the DMP in order? Have all necessary actions been carried out?   
- Check by the scientist (e.g., sample check) - have the samples been correctly entered into the CMS?
- Is all relevant metadata in order?
- Have the agreed naming convention & folder structure been followed?
- Is it useful and/or necessary to also archive a copy of certain data?
- Is the dataset mentioned in relevant outputs/publications?

