---
layout: page
<!--type: cheat_sheet-->
title: Data sharing and long-term preservation
search_exclude: false
contributors: [Svein Høier]
page_id: 5_sharing_preservation
description: Data sharing, archiving, long-term preservation
affiliations: 
sidebar: dmp_knowledge_base
toc: true
---

<!--Science Europe question ID & title-->
## 5a - How and when will data be shared? Are there possible restrictions to data sharing or embargo reasons?

<!--key information-->
### [Science Europe DMP Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862") [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated
> 5a.1\
Explain how the data will be discoverable and shared (for example by deposit in a trustworthy data repository, indexed in a catalogue, use of a secure data service, direct handling of data requests, or use of another mechanism)

Sharing should be read as publishing data in a repository (openly or with controlled access). Unpublished data requires a preservation plan.

> 5a.2\
Outline the plan for data preservation and give information on how long the data will be retained.

In many cases this information should be provided by the data repository.
Relevant certificatoin schemes are e.g. CoreTrustSeal, DIN31644, ISO163638.

> 5a.3\
Explain when the data will be made available. Indicate the expected timely release. Explain whether exclusive use of the data will be claimed and if so, why and for how long. Indicate whether data sharing will be postponed or restricted for example to publish, protect intellectual property, or seek patents.

See also questions on IPR under [4 - Legal and ethical requirements](/4_legal_ethics).

> 5a.4\
Indicate who will be able to use the data. If it is necessary to restrict access to certain communities or to apply a data sharing agreement, explain how and why. Explain what action will be taken to overcome or to minimise restrictions.

See also [4 - Legal and ethical requirements](/4_legal_ethics).

There are different ways of restricting data access: publishing in controlled access repositories or applying reuse limitations (restrictive licenses or tags/ontologies specifying allowed reuse).\
Examples of controlled access repositories in Norway: [SIKT archive](https://sikt.no/en/archiving-research-data), [Federated EGA Norway node](https://ega.elixir.no/)
Examples of restrictive licenses: [CLARIN ACA ('academic use') and CLARIN RES  ('restricted use') licenses](https://www.clarin.eu/content/licenses-and-clarin-categories)

It is crucial to be aware of necessity of access restriction and possibilities to overcome restrictions early in the project, as this is often impossible to implement in retrospect.

#### Sufficiently adressed (DMP Evaluation Rubric)
- Clearly describes how the data and/or metadata will be made discoverable and shared.
- Specifies when data will be shared and under which licence.
- Includes the name of the repository, data catalogue, or registry where data will or could be shared.
- Includes information on how long the data will be retained and gives precision on its timely release.
- Clearly explains, if applicable, why data sharing is limited or not possible, and who can access the data under which conditions (for example, only members of certain communities or via a sharing agreement).
- Explains, where possible, what actions will be taken to overcome or to minimise data sharing restrictions.

```
**Relevant PID**
- PID of archived datasets?

**Interested stakeholder**
- Level 2: Core facility, data archive, research administration (statistics)

**Relevant project phase**
- pre-award:outline
- planning post-award, active phase, final reporting
```

#### [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in dmp]
- [#dataset_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_table): nested, see below

[Properties in dataset]
- [#dataset_id_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_id_tree): identifier, type
- [#distribution_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_tree): Nested, see below e.g. access_url, available_until, byte_size, data_access, description, download_url, format, host, license, title
- [#dataset_preservation](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_preservation): preservation statement [string, free text]
- [#dataset_sensitive_data_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_sensitive_data_tree): yes/no/unknown

[Properties in distribution]
- [#distribution_access_url](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_access_url): A URL of the resource that gives access to a distribution of the dataset. e.g. landing page.
- [#license_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#license_table): license_ref [uri], start_date

Missing:
- measures to overcome sharing restrictions
- detailed information on restricted access

---
<!--additional explanations-->
### Explanations for support staff
- Embargo policies and funder guidelines
- Controlled access repositories
- Ways of limiting data reuse: reuse tags, licenses
- Trustworthy repositories
- Certification schemes: CoreTrustSeal, DIN31644, ISO163638

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Data sharing and reuse]
- How should the data be findable and how should it be shared? Examples may be that they are made available in a certified data repository, are indexed in a catalogue, that you use a secure data service, direct handling of data requests, etc.
- When should the data be shared? If, for example, an exclusive right of control granted by legal law is made that affects the time of sharing and, why and for how long? Examples may be that you wait until a scientific publication is available or that you want to protect intellectual property rights, such as patent law, until you have applied for a patent.

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
[2.2 Making data accssible - Repository]
- Have you explored appropriate arrangements with the identified repository where your data will be deposited
[2.2 Making data accssible - Data]
- Will all data be made openly available? If certain datasets cannot be shared (or need to be shared under restricted access conditions), explain why, clearly separating legal and contractual reasons from intentional restrictions. Note that in multi-beneficiary projects it is also possible for specific beneficiaries to keep their data closed if opening their data goes against their legitimate interests or other constraints as per the Grant Agreement.
- If an embargo is applied to give time to publish or seek protection of the intellectual property (e.g. patents), specify why and how long this will apply, bearing in mind that research data should be made available as soon as possible.
- Will the data be accessible through a free and standardized access protocol?
- If there are restrictions on use, how will access be provided to the data, both during and after the end of the project?
[2.4 Increase data re-use]
- Will your data be made freely available in the public domain to permit the widest re-use possible? Will your data be licensed using standard reuse licenses, in line with the obligations set out in the Grant Agreement?
- Will the data produced in the project be useable by third parties, in particular after the end of the project?
- Will the provenance of the data be thoroughly documented using the appropriate standards?

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
- With respect to licensing: Clearly and explicitly license your data, no matter which access level the data has. Find a suitable license (either standard such as CreativeCommons, or bespoke) and find a repository that supports it on Re3data. Preferably use a standard, machine-readable licence. Include the license information in the metadata.
- With respect to access: Consider and define the access levels of your data early on (public, restricted, embargo, closed, or a combination). Include this information in your metadata, including possible related conditions for reuse.
- With respect to discoverability and preservation planning: Deposit your data in a trustworthy data repository.
- For guidance on trustworthy repositories, see 6a.

---
<!--additional explanations - only keywords-->
### Explanations for users
- sharing as in archiving != sharing with collaborators in the active phase (storage = section 3, consortia agreements in section 4)
- Embargo policies and funder guidelines
- Valid and invalid reasons of access restritions and how to do this in practice
- Identifying repositories, re3data, FairSharing
- Trusted repositories
- Licensing

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [DMP Tuuli](https://zenodo.org/records/5242629) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
What part of the data can be made openly available or published? Where and when will the data, or its metadata, be made available? (5.1) 
 Describe how you will make data available and findable for reuse. If your data or parts of the data cannot be opened, explain why you publish only metadata.
 In the case of sensitive data, which cannot be opened, describe the opening of its metadata. Describe the secured preservation procedure of sensitive data in Section 5.2.
 The openness of research data promotes its reuse.
 Tips for best practices
You can publish a description (i.e., the metadata) of your data without making the data itself openly available, which enables you to restrict access to the data.
Publish your data in a data repository or a data journal.
Check re3data.org (https://www.re3data.org/) to find a repository for your data.
Prefer repositories or publishers, which provide persistent identifiers (PID) to enable access and citation to the data via a persistent link (e.g. DOI, URN).
Remember to check the funder, institutional, disciplinary or national recommendations for data repositories.
It is recommended to make all of the research data, code and software created within a research project available for reuse, for example, under a Creative Commons (https://creativecommons.org/choose/), GNU (https://www.gnu.org/licenses/gpl-3.0.en.html) or MIT license (https://opensource.org/licenses/MIT), or under another relevant license.

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[How do you plan to preserve the research material? Find out what rules your university/organization has for preservation and destruction of research records and decide who in the research team is responsible for making sure that the official records from the project are archived.
 What data will be preserved and/or made accessible, and how do you make that selection? Are there any local regulations? If it is possible to make the data accessible: when, where, and to whom? Will the data be made accessible in a data repository, a subject-specific database, at the university, or by the research group?]
Why is this important? Digital data materials need to be actively administered over time, to make sure that they remain accessible and usable. Research materials that are created at a university/public agency must be archived there, in accordance with the Swedish Archives Act (SFS 1990:782). As a rule, official documents at universities and other higher education institutions shall be archived and it is, in principle, unlawful to destroy official documents unless specifically allowed by law, i.e. if there is a right to dispose of records. Raw data files, ethical approvals, research data documentation, and published results must be archived. If you have questions regarding archiving or destruction of documents, please consult with your organization’s archive.


-----
-----
<!--Science Europe question ID & title-->
## 5b - How will data for preservation be selected, and where will data be preserved long-term (for example a data repository or archive)?

<!--key information-->
### [Science Europe DMP Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862") [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated
> 5b.1\
Indicate what data must be retained or destroyed for contractual, legal, or regulatory purposes.

See also [4 - Legal and ethical requirements](/4_legal_ethics).
Health data would be a typical example where legal obligations for retaining/destroying data exist.

> 5b.2\
Indicate how it will be decided what data to keep. Describe the data to be preserved long-term.

> 5b.3\
Explain the foreseeable research uses (and/or users) for the data.
Indicate where the data will be deposited. If no established repository is proposed, demonstrate in the DMP that the data can be curated effectively beyond the lifetime of the grant. It is recommended to demonstrate that the repositories policies and procedures (including any metadata standards, and costs involved) have been checked.

There may be several rounds of selecting data for preservation in a project. Criteria to consider: quality of the data (e.g. discarding failed experiments), how difficult would it be to re-create the data, technical feasibility/storage costs for retaining large amounts of raw data (e.g. instead keeping only processed data), limited reuse value (e.g. raw data to transparently document the research process with little reuse value).
Particulary if large data volumes are deleted, this should be described.

It is desirable to publish all central datasets in research data repositories by end of the project. Criteria for selection for trustworthy repositories should be applied and it should briefly be lined out how the criteria are met.
If there is unpublished data remaining at the end of the project, a preservation plan needs to line out who is responsible for the data, and where and how long the data will be kept.

#### Sufficiently adressed (DMP Evaluation Rubric)
- Provides details of what data collected or created in the project will be preserved in the long term and clearly indicates for how long. This should be in alignment with funder, institutional, or national policies and/or legislation, or community standards.
- Provides details of which (versions of) data and accompanying documentation will be retained or destroyed, and explains the rationale (for example contractual, legal requirements, or regulatory purposes).
- Provides details of how the selection is made, and what possible interest there would be for re-use (or not).
- Provides details on how the data, accompanying documentation, and any other required technology such as copies of software in specific versions will be archived in the long term.
- Explains how data will be managed in a sustainable way beyond the lifetime of the grant.
- Provides the name of the archive or trustworthy repository – or the way to curate and preserve data – that will be used to make data available for re-use.

```
**Relevant PID**
- none?

**Interested stakeholder**
- Level 2: Core facility, data archive, research administration (statistics), CRIStin/NVA

**Relevant project phase**
- active phase, final reporting
```

#### [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in dmp]
- [#dataset_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_table): nested, see below

[Properties in dataset]
- [#dataset_id_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_data_access_tree): open/shared/closed
- [#distribution_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_tree): nested, see below e.g. access_url, available_until, byte_size, data_access, description, download_url, format, host, license, title
- [#dataset_preservation](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_preservation): preservation statement [string, free text]
- [#dataset_sensitive_data_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_sensitive_data_tree): yes/no/unknown

[Properties in distribution]
- [#license_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#license_table): license_ref [uri], start_date
- [#host_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_tree): nested, see below e.g. availability, backup_frequency, backup_type, certified_with, description, geo_location, pid_system, storage_type, support_versioning, title, url

[Properties in host]
- [#host_certified_with_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_certified_with_tree): din31644, dini-zertifikat, dsa, iso16363, iso16919, trac, wds, coretrustseal [controlled]

Missing:
- Preservation considerations
- Deleted data
- Controlled access specifications (e.g. need for data access committee)
- Dataset logic only partially suited for unpublished datasets

---
<!--additional explanations-->
### Explanations for support staff
- Preservation selection best practice.
- Legal requirements, e.g. health data.
- Selecting repositories, archive catalogues, definition trusted repositories

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Data sharing and reuse]
- How should the data be findable and how should it be shared? Examples may be that they are made available in a certified data repository, are indexed in a catalogue, that you use a secure data service, direct handling of data requests, etc.
- When should the data be shared? If, for example, an exclusive right of control granted by legal law is made that affects the time of sharing and, why and for how long? Examples may be that you wait until a scientific publication is available or that you want to protect intellectual property rights, such as patent law, until you have applied for a patent.

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
[2.2 Making data accssible - Repository]
- Will the data be deposited in a trusted repository?

[2.2 Making data accssible - Metadata]
- How long will the data remain available and findable? Will metadata be guaranteed to remain available after data is no longer available?

[4. Allocation of resources]
- How will long term preservation be ensured? Discuss the necessary resources to accomplish this (costs and potential value, who decides and how, what data will be kept and for how long)? (see also section 6_responsibilities_resources)

[5. Data security]
- Will the data be safely stored in trusted repositories for long term preservation and curation? (see also section 3_storage_backup)

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
- With respect to data destruction: Figure out early on by conferring with research data management and ethics specialists if (parts of) your data need to be destroyed (e.g., after a certain amount of time). If this is the case, include general statements about data destruction in the consent forms you use during your study. Make sure that the repository you deposit your data in can handle such destruction and will continue to maintain your metadata afterwards.
- For guidance on trustworthy repositories, see 6a.

---
<!--additional explanations - only keywords-->
### Explanations for users
- Preservation selection best practice.
- Selecting a trusted repository.
- Why is it important that metadata are preserved even if data is deleted
- Comment Svein: At the planning stage, criteria for selection is relevant - but it might be too early to concretize what will be selected for preservation?
Tuuli guides: "Decisions about preserving data should begin during the data management planning stage, and should take into account e.g. institutional guidance and requirements"

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[Before you preserve the data material and make it accessible, you may want to prepare the material. What file formats are suitable for long-term preservation? What documentation should be included with the data material after the project has ended? Are there any ethical and legal restrictions on the material, which mean that the data need to be processed (e.g. de-identified) before they can be made accessible? Where do you plan to archive and/or make the data accessible? Contact them in good time for assistance in how to prepare the material.]
 Why is this important? Digital file formats run the risk of becoming obsolete. If this should happen, future software may not be able to read and present the information in the files correctly, and valuable research data could be lost. Therefore, you should choose file formats that are more likely to remain usable in the future, i.e. formats that are commonly used, non-proprietary, and have an open technical specification. Another benefit of choosing those formats is that you won’t have to convert the file formats at the end of the project. It isn’t always possible to choose a format that meets all criteria, as specific instruments, analysis tools, or developed software can affect the choice of data formats. If that’s the case, it’s important to plan for how to guarantee that the data material can be preserved.
 When the project is finished and the data material shall be made accessible, it may, due to ethical and legal restrictions, be important to guarantee that the individuals in the study cannot be re-identified (i.e. identified through indirect identifiers in the data material).

#### [DMP Tuuli](https://zenodo.org/records/5242629) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
**Where will data with long-term value be archived, and for how long? (5.2)**
 Briefly describe what part of your data you will preserve, where it is preserved, and for how long. Long term preservation means that data is preserved for as long as necessary, for several decades or even centuries.
 You can categorise your data sets according to the anticipated preservation period:
 A) Data to be destroyed upon the ending of the project
 B) Data to be archived for a verification period, which varies across disciplines, e.g., 5–15 years 
 C) Data to be archived for potential re-use, e.g., for 25 years
 D) Data with long-term value to be archived by a curated facility for future generations for tens or hundreds of years

You will need to decide which of your research data to preserve and dispose of. Data that is unique or difficult to replicate might have long-term value and be fit for preservation. Special long term data repositories should be used for digital preservation. 

**Tips for best practices**
Decisions about preserving data should begin during the data management planning stage, and should take into account e.g. institutional guidance and requirements.
Use data repositories with a commitment to long-term curation, e.g. Fairdata Digital Preservation Service is dedicated for research datasets that have significant value to the organization or on a national level currently and especially also in the future. Contact your home organisation for further information.


-----
-----
<!--Science Europe question ID & title-->
## 5c - What methods or software tools will be needed to access and use the data?

<!--key information-->
### [Science Europe DMP Guidance](https://doi.org/10.5281/zenodo.4915862 "Science Europe. (2021). Practical Guide to the International Alignment of Research Data Management - Extended Edition. https://doi.org/10.5281/zenodo.4915862") [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated
> 5c.1\
Indicate whether potential users need specific tools to access and (re-)use the data. Consider the sustainability of software needed for accessing the data.

Access protocols for controlled access should be described ([see FAIR principles A1.2](https://www.go-fair.org/fair-principles/a1-2-protocol-allows-authentication-authorisation-required/)).

Preferance to open formats should be specified in [1b - What data (for example the kind, formats, and volumes) will be collected or produced?](/1_data_description#1b---what-data-for-example-the-kind-formats-and-volumes-will-be-collected-or-produced).\
Software/computer code generated in the project should be managed as research output.

> 5c.2\
Indicate whether data will be shared via a repository, requests handled directly, or whether another mechanism will be used?

There is few reasons to share data outside of data repositories after completion of the project.

#### Sufficiently adressed (DMP Evaluation Rubric)
- Clearly indicates which specific tools or software (for example specific scripts, codes, or algorithms developed during the project, version of the software) potential users may need to access, interpret, and (re-)use the data. 
- Provides information, if relevant, on any protocol to access the data (for example if authentication is needed or if there is a data access request procedure).

```
**Relevant PID**
- none?

**Interested stakeholder**
- Level 3: Research community (+Standard bodies?)

**Relevant project phase**
- active phase, final reporting
```

#### [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in dmp]
- [#dataset_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_table): nested, see below

[Properties in dataset]
- [#technical_resource_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#technical_resource_tree): description ambiguous?
- [#distribution_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_tree): nested, see below e.g. access_url, available_until, byte_size, data_access, description, download_url, format, host, license, title

[Properties in distribution]
- [#host_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_tree): nested, e.g. availability, backup_frequency, backup_type, certified_with, description, geo_location, pid_system, storage_type, support_versioning, title, url

Missing:
- specification of e.g. software needed to access data


---
<!--additional explanations-->
### Explanations for support staff
- Data provenance
- Persistent file formats
- Dependencies for software code.
- Controlled access systems, some technical understanding of authentification methods.

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Data sharing and reuse]
- Do potential users need specific tools, such as software, to access and (re)use the data? The sustainability of the software for future access to the data should be considered.

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
- Include the tools and/or code needed to reuse your data in the metadata of your dataset, as well as meaningful and explicit links to other kinds of research output (e.g., previous versions, other relevant datasets, related publications, data sources, data creators, data collectors, funding organizations, host institutions) to increase potential for reuse.
- For guidance on access, see 5a.

---
<!--additional explanations - only keywords-->
### Explanations for users
- Data provenance
- Persistent file formats
- Dependencies for software code
- Controlled access archives

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[Will a specific software or tool be required to use the data material? If it is: is it possible to add the software or tool to the data material, and if so, what documentation is required for someone to be able to use it? If it isn’t possible to add the software/tool, what is required to be able to use the data material?]

**Why is this important?**
To make it possible to continue using the data material, it’s important to enter information about what software or tools that are needed, as non-proprietary software isn’t always sufficient. Some tools may also be based on a certain software and, if possible, it’s of great help to include the software with the material, e.g. by open source code.


-----
-----
<!--Science Europe question ID & title-->
## 5d - How will the application of a unique and persistent identifier (such as a Digital Object Identifier (DOI)) to each data set be ensured?

<!--key information-->
### [Science Europe DMP Guidance](https://doi.org/10.5281/zenodo.4915862) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) - annotated
> 5d.1\
Explain how the data might be re-used in other contexts. Persistent identifiers (PIDs) should be applied so that data can be reliably and efficiently located and referred to. PIDs also help to track citations and re-use.

> 5d.2\
Indicate whether a PID for the data will be pursued. Typically, a trustworthy, long-term repository will provide a persistent identifier.

At what granularity are PIDs provided? (collection, dataset, each item in a dataset?)

#### Sufficiently addressed (DMP Evaluation Rubric)
- Specifies how the data can be re-used in other contexts.
- Clearly indicates if and which PIDs are provided for all datasets, individual datasets, data collections, or subsets. If PIDs will not be used, it explains why.
- Clearly presents the approach, and the choice of identifiers is justified and refers to international standards.

```
**Relevant PID**
- PID of all datasets produced

**Interested stakeholder**
- Level 2: Research administration (statistics), CRIStin/NVA

**Relevant project phase**
- active phase, final reporting
```

#### [RDA Common Standard for maDMP](http://doi.org/10.15497/rda00039) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[Properties in dmp]
- [#dataset_table](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#dataset_table): nested, see below

[Properties in dataset]
- [#distribution_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#distribution_tree): nested, see below e.g. access_url, available_until, byte_size, data_access, description, download_url, format, host, license, title

[Properties in distribution]
- [#host_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_tree): nested, e.g. availability, backup_frequency, backup_type, certified_with, description, geo_location, pid_system, storage_type, support_versioning, title, url

[Properties in host]
- [#host_pid_system_tree](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard?tab=readme-ov-file#host_pid_system_tree): ark, arxiv, bibcode, doi, ean13, eissn, handle, igsn, isbn, issn, istc, lissn, lsid, pmid, purl, upc, url, urn, other [controlled]

Missing:
- possibility to specify other PID?


---
<!--additional explanations-->
### Explanations for support staff
- Types of PIDs
- Research catalogues

#### [Guidance from NFR](https://www.forskningsradet.no/en/research-policy-strategy/open-science/research-data/)
[Data sharing and reuse]
Will a persistent identifier (DOI) for the datasets be used? Persistent identifiers should be applied to metadata and datasets so that they can be findable and referenced in a reliable and efficient manner. Using DOI also ensures that citations and reuse can be tracked. A certified data repository will often provide this to (meta)data deposited there.

#### [Horizon Europe DMP Template](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/reference-documents?selectedProgrammePeriod=2021-2027&selectedProgramme=HORIZON)
[2.2 Making data accessible - Repository]
- Does the repository ensure that the data is assigned an identifier? Will the repository resolve the identifier to a digital object

#### [FAIRsFAIR FAIR-Aware Additional Guidance](https://doi.org/10.5281/zenodo.6088215) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
- Choose a data repository to deposit your data in that assigns your desired persistent identifiers (e.g., a DOI, Handle, or ARK for the data, or an ORCID for the researchers). Use Re3data or FAIRsharing to find a suitable repository.


---
<!--additional explanations - only keywords-->
### Explanations for users
- The archives decides for you, types of PIDs

---
<!--recycling possible?-->
### Existing sources that can be reused

#### [SND - Checklist DMP](https://zenodo.org/records/6424769) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[Will the material receive a persistent identifier (PID), and what type of PID? Enter the PID here if you have one, or when you get one.]
**Why is this important?**
A persistent identifier is a unique digital ID that refers to one or more objects, digital or physical. In research, it’s common practise to issue a PID to publications or research data that are preserved for a long time and made accessible through digital resources.
It’s important to enter this information to show funders that you have thought about essential factors around the access to data. As there are different types of PID, depending on e.g. field of research or where the data material is preserved, you may want to explore which PID is most suited for your material. Data that are made accessible through SND receive a persistent identifier called a DOI (Digital Object Identifier).

#### [NTNU - DMP Guidance](https://i.ntnu.no/wiki/-/wiki/English/DMP+guidance)
Persistent identifiers like DOIs are usually issued by data repositories (e.g., Zenodo, NTNU Open Research Data etc.). In most cases, your choice of repository will therefore determine the use of persistent identifiers.