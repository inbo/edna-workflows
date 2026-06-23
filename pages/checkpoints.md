---
title: Data checkpoints
description:
background:
  img: /assets/images/checkpoints_banner.jpg
  by: CHUTTERSNAP
  href: https://unsplash.com/photos/five-green-plants-UmncJq4KPcA
permalink: /checkpoints/
toc: true
editor_options: 
  markdown: 
    wrap: sentence
---

## Overview

![checkpoints]({{ '/assets/images/overview_checkpoints.png' \| relative_url }})

## Preparation

{:.alert .alert-info .mt-3}

\- Has the DMP been started?\
- Is the team aware of the naming convention & folder structure?\
- Are one or more team members responsible for each data checkpoint?\
- Is it known who the data owner is?
Are there any existing obligations regarding openness and/or FAIRness of the data?\
- Which database/repository uploads are required by the reporting?\
- Is there an agreed metadata approach?

### Has the DMP been started?

It's always a good idea to start a DMP at the conceptual stage of the eDNA research workflow.

### Is the team aware of the naming convention & folder structure?

These aspects should be agreed upon at either a team, project, or laboratory level before the project begins and documented somewhere, for example, in a lab Standard Operating Procedures (SOP) or a project DMP.
It must be compatible with the Collection Management System (CMS) where samples/data are located & how they are named/labelled.

### Are one or more team members responsible for each data checkpoint?

This can be noted in the DMP or another file, e.g. a spreadsheet.

### Is it known who the data owner is? Are there any existing obligations regarding openness and/or FAIRness of the data?

There may be multiple data owners.
It may be that, according to agreements with partners, funders, etc., the data can never be shared *openly* or *FAIRly*, or conversely, it must be shared *openly* and *FAIRly*.
If this is already agreed upon before the research begins, the data can be managed from the start with this in mind.
The situation must also be explained in the DMP.

### Which database/repository uploads are required by the reporting?

Different data types generated throughout the workflow are typically deposited in different repositories.
It is already insightful at this stage to keep these in mind, as many repositories have specific metadata requirements.
Starting with the correct metadata format from the beginning will save considerable effort later.
Common repositories used in accordance with eDNA data are:

- Raw sequence data –\> internal back-up drive and publicly through ENA or SRA

- Occurrence data –\> GBIF (via IPT or Darwin Core Archive)

- Reference databases, scripts, downstream processed data (from OTU/ASV tables to extended and statistically analysed datasets to answer particular research questions) –\> Zenodo

- Protocols –\> publicly available institute or project website or wiki page

- DNA specimens, or other physical samples –\> Institute collection [insert section on CMS here?]

- DMP —\> institute RIMS (Research Information Management System)

  More details are presented in the Output/Publication section.

## Sample collection

{:.alert .alert-info .mt-3}

\- Have the sampling techniques been written down?
\
- Have the sampling techniques been archived?
\
- Is it clearly noted in the sampling sheet where data and samples are stored or kept?
\
- Have the agreed naming convention & folder structure been followed?
\
- Has the sampling sheet been backed up?
\
- Is it necessary to update the DMP?

### Have the sampling techniques been written down?

The description of the sampling techniques does not need to be highly detailed.
Reference to documentation (e.g., SIP, SAP, SOP, SVP) or mentioning, for example, filter method, volumes, etc., in the field forms of the sampling sheet is often sufficient.
Alternatively, include the description in the DMP.
If there is a deviation from the described sampling techniques, e.g., for practical reasons, note this in the DMP as well.

### Have the sampling techniques been archived?

Pay attention to document and apply version control and use already existing templates where possible.
Deposit this documentation in online repositories, e.g. on an institute or project-specific webportal (INBO archive, INBO protocol helper), or wikipage, or in absence of such, on a readily available repository like [zenodo](https://zenodo.org/).
If it is described in the DMP, ensure that the DMP is deposited in the RIMS of your institute (INBO's [PURE](https://pureportal.inbo.be/nl/)).

### Is it clearly noted in the sampling sheet where data and samples are stored or kept?

Bringing samples to the lab follows an agreed intake procedure.
At INBO, samples are brought to the genetics laboratory in consultation with the lab team.
Upon intake, a registration form (Google Forms) must be completed, specifying the storage conditions required: room temperature, cold room, or freezer.
Each sample receives a checklist number, which is physically labelled on the sample and registered in the central overview (Google Forms Response Sheet, i.e. sampling sheet), linking all relevant metadata to the sample for both physical and digital traceability via the CMS.

After processing, a storage decision must be made: samples kept for less than 5 years, and those intended for longer-term archiving are stored at different locations.

If a storage decision has not yet been made upon sample collection, ensure this is followed up and updated both in the sampling sheet (recording sample metadata) and the CMS before moving towards the next step.

### Have the agreed naming convention & folder structure been followed?

The sample ID must follow a convention, ideally established before the project begins and as streamlined over multiple projects as possible.
The naming convention can further be noted in the project SOP or DMP.
What matters, is that these sampling IDs are consistent and compatible with the CMS.
\
\
For eDNA samples at INBO, the following convention is used:

`E[year][filtertype][4-digit tracking number][handling steps with umpact on physical sample]`, e.g.
`E2026STF1009PC`

Conventions:

\- `E` indicates an eDNA sample\
- `year` is the full 4-digit year\
The sample ID must be lowercase \
- The `year` must be in full \
- The `samplenumber` must always consist of three digits as we never expect 1000 or more samples per location \
- `sitecode` can be an acronym, a number, or a combination of both and can be agreed per project.
\
- The `project` can be the project acronym, or the project acronym + the ID provided by the used Project Management System (PMS).
This should be agreed upon generally.

### Has the sampling sheet been backed up?

As the sampling sheet is the key to understanding and using the data, it is crucial to back up a copy of it regularly, for example, on another drive.

### Is it necessary to update the DMP?

Have you changed something about the sampling techniques or conventions?
Then the answer to the question is a fully YES: you need to **update** the DMP!

## Lab analyses

{:.alert .alert-info .mt-3} - Have all relevant lab protocol(s) been written down?
- Have copies of the lab protocol(s) been archived?
- Have the samples all been named and stored as they should be?
- Will the DNA specimens be deposited in a collection?
- Has the sampling sheet been backed up?
- Has the raw (DNA) data been archived?
- Have the agreed naming convention & folder structure been followed?
- Is it necessary to update the DMP?

### Have all relevant lab protocol(s) been written down?

For example, the DNA extraction protocol.
Use version control, e.g. git and GitHub.

Some protocols could be manufacturer specific.

### Have copies of the lab protocol(s) been archived?

**For reviewers: this text is the same as the one in previous chapter (Sample collection).**

Pay attention to document and apply version control and use already existing templates where possible.
Deposit this documentation in online repositories, e.g. [zenodo](https://zenodo.org/), or institute specific tools (INBO archive, INBO protocol helper) or cloud storage drives (INBO Google drive).
If it is described in the DMP, ensure that the DMP is deposited in the Research Information Management System (RIMS) of your institute (INBO's [PURE](https://pureportal.inbo.be/nl/)).

### Have the samples all been named and stored as they should be?

The sampling sheet must be checked at this stage.

### Will the DNA specimens be deposited in a collection?

This steps requires that the institute has a samples collection for DNA specimens, providing the right infrastructure to store DNA specimens for the long term.
INBO has such an archive and can be used for any project where INBO has been involved, provided the samples meet the agreed minimum quality requirements: - The sample collections is well-documented - The sample was ethically and legally obtained - The sample is relevant to Flemish biodiversity.

If the residual fraction of the eDNA sample needs to be archived after analysis, it is an added value to archive it as early as possible.
The sample can be stored at -20°C or -80°C and is centrally managed by INBO from the moment the information is submitted.

There may be an embargo on releasing the data, which allows analyses to be finished before the sample appears in the online (accessible) inventory.

### Has the sampling sheet been backed up?

**For reviewers: copy from previous chapter?**

### Has the raw (DNA) data been archived?

As soon as possible, after the completion of the analyses, archive the raw (DNA) data, e.g. in a cloud storage drives (INBO Google drive).
Raw data files can be very large.
Make sure you have sufficient storage space available.

### Have the agreed naming convention & folder structure been followed?

**Not present in original document.** This step is important to automatise workflows and avoid mistakes in the next steps.

### Is it necessary to update the DMP?

Are there aspects of the DMP that have changed and/or need to be expanded?
If there is a deviation from this workflow and/or the protocol(s) used, **update** the DMP.

## Bioinformatics

{:.alert .alert-info .mt-3} - Have the analysis protocols/steps been written down?
- Have the analysis protocols/steps been archived?
- Have the used reference database(s) been archived OR has their version/publication date been noted?
- Have the “operational data” been archived?
- Is it useful to also archive other data?
- Have the agreed naming convention & folder structure been followed?
- Is it necessary to update the DMP?

### Have the analysis protocols/steps been written down?

Examples: - A standard set of steps to demultiplex - A step-by-step protocol of the analysis

At INBO, we try to document these steps on GitHub for version control.
See the code base in repository [`inbo/edna-metabarcoding`](https://github.com/inbo/edna-metabarcoding).
The development documentation and tutorials are versioned at confluence-eDNA-bodem.

**For reviewers. confluence-eDNA-bodem: confluence is not used by INBO anymore. But if the page is still available and open, please add link waiting for alternative. Otherwise, update the text as wished**.

### Have the analysis protocols/steps been archived?

**For reviewers: this text is the same as the one in previous chapter (Sample collection).**

Pay attention to document and apply version control and use already existing templates where possible.
Deposit this documentation in online repositories, e.g. [zenodo](https://zenodo.org/), or institute specific tools (INBO archive, INBO protocol helper) or cloud storage drives (INBO Google drive).
If it is described in the DMP, ensure that the DMP is deposited in the Research Information Management System (RIMS) of your institute (INBO's [PURE](https://pureportal.inbo.be/nl/)).

### Have the reference database(s) been archived OR has their version/publication date been noted?

Deposit on [zenodo](https://zenodo.org/) the reference database(s).
Archive the used reference database(s) also internally if possible (**internal archive option added by me!**).
Note the version/date used and provide a link to the zenodo deposit.
If the internal multihit list was used, also note the version/date of it.

### Have the “operational data” been archived?

This about archiving the ‘outputs’ of this step, e.g., the Operation Taxonomic Units (OTU) tables.

### Is it useful to also archive other data?

Per project, consider whether there are ‘savepoints’ during the bioinformatics step, e.g., demultiplexed data, data coming from a time-consuming step for which it is worth archiving a copy as a backup, data being supplied to clients/partners, data used for other internal projects and which must be published later.
Ensure there is a clear `README` with all savepoints, including the script/steps taken to reach that point.

### Have the agreed naming convention & folder structure been followed?

**Not present in original document.** This step is important to automatise workflows and avoid mistakes in the next steps.

### Is it necessary to update the DMP?

**Note: the same as in previous chapters.** Are there aspects of the DMP that have changed and/or need to be expanded?
If there is a deviation from this workflow and/or the protocol(s) used, **update** the DMP.

## Dataprocessing

{:.alert .alert-info .mt-3} - Has the data analysis been written down?\
- Have the analysis protocols/steps been archived?
- Have the “operational data” been archived?
- Is it useful to also archive certain data?
- Have the agreed naming convention & folder structure been followed?
- Is it necessary to update the DMP?

### Has the data analysis been written down

Examples: - A standard set of steps to perform a specific statistical analysis - Relevant scripts and phyloseq objects

Note also the necessary extra information to make the dataprocesiing reproducible (e.g., in R, use `{Renv}` package, or at least document the package and Opearting System versions used, e.g. by writing down the output of `sessionInfo()`).
Use version control, e.g. via git and GitHub.

### Have the analysis protocols/steps been archived?

**For reviewers: this text is the same as the one in previous chapter (Sample collection).**

Pay attention to document and apply version control and use already existing templates where possible.
Deposit the data analysis scripts in online repositories, e.g. [zenodo](https://zenodo.org/), or institute specific tools (INBO archive, INBO protocol helper) or cloud storage drives (INBO Google drive).
If it is described in the DMP, ensure that the DMP is deposited in the Research Information Management System (RIMS) of your institute (INBO's [PURE](https://pureportal.inbo.be/nl/)).

### Have the “operational data” been archived?

When a dataset is ‘ready’ (i.e., will not be further edited), it might be a good moment to archive it.

### Is it useful to also archive certain data?

**For reviewers: this text is the same as the one in previous chapter (Bioinformatics).**

Per project, consider whether there are ‘savepoints’ during the bioinformatics step, e.g., demultiplexed data, data coming from a time-consuming step for which it is worth archiving a copy as a backup, data being supplied to clients/partners, data used for other internal projects and which must be published later.
Ensure there is a clear `README` with all savepoints, including the script/steps taken to reach that point.

### Have the agreed naming convention & folder structure been followed?

**Not present in original document.** This step is important to automatise workflows and avoid mistakes in the next steps.

### Is it necessary to update the DMP?

Are there aspects of the DMP that have changed and/or need to be expanded?
If there is a deviation from this workflow and/or the protocol(s) used, **update** the DMP.

## Output/data publication

{:.alert .alert-info .mt-3} - Is the DMP in order?
Have all necessary actions been carried out?
- Have the samples been correctly entered into the CMS?
- Is all relevant metadata in order?
- Have the agreed naming convention & folder structure been followed?
- Is it useful and/or necessary to also archive a copy of certain data?
- Is the dataset mentioned in relevant outputs/publications?

### Is the DMP in order? Have all necessary actions been carried out?

Add an annex to the DMP with the data publication workflow.

Are there aspects of the DMP that have changed and/or need to be expanded?
**Update** the DMP!

If the research outputs/data publication is deposited in the Research Information Management System (RIMS) of your institute (INBO's [PURE](https://pureportal.inbo.be/nl/)), do not forget to add alink to the DMP.

### Have the samples been correctly entered into the CMS?

This is more a kind of final double check.
We suggest to perform a random check of a subset of the used samples.

### Is all relevant metadata in order?

Sometimes, multiple datasets are generated from the same workflow: check the metadata of all of them.

### Have the agreed naming convention & folder structure been followed?

Examples: - Check the folder structure - Are there still "loose" undocumented scripts or files?
- Are there poorly named files?

### Is it useful and/or necessary to also archive certain data?

Think about archiving e.g., data supporting an output/publication.

Per project/publication, consider which data needs to be archived.
Consider archiving on the institute's cloud storage drive (INBO Archive Google drive) and/or an online data repository e.g., [zenodo](https://zenodo.org/).
Follow your institute's Archive Policy if any.

### Is the dataset mentioned in relevant outputs/publications?

Follow your institute open data and open access policy if any.
At INBO, it means keeping an eye on on the embargo period, which cannot be longer than 6 months.
More details at the [INBO open data](https://www.vlaanderen.be/inbo/en-gb/open-data-policy/) and [open access](https://www.vlaanderen.be/inbo/en-gb/open-access-policy/) policies.
