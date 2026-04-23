# NGI Needs Assessment and Literature Review

This repository contains data from the literature review and the raw and coded interview transcripts from the needs assessment portion of the study: **"Using user-centered design to better understand challenges faced during genetic analyses by novice genomic researchers"**. 

**Paper Link:** [Preprint on bioRxiv](https://www.biorxiv.org/content/10.64898/2026.02.06.704411v1)

## Overview

The study utilized a mixed-methods approach to characterize the barriers faced by novice genomics researchers (NGRs) when using bioinformatics software. This repository focuses on the data generated from both the **literature review**, evaluating existing genomics tools, and the **needs assessment**, semi-structured interviews conducted to query the needs, challenges, and experiences of NGRs.

## Literature Review Methodology

A targeted literature review was conducted to evaluate existing bioinformatics software tools for user-centered design considerations. The search criteria utilized to find relevant literature from different databases are provided below. Except for Pubmed, all other databases were manually filtered for the publication date (post-2003) and English language requirements.

| Database | Search String |
| --- | --- |
| Pubmed | `(("bioinformatic") OR ("biomedical informatic") OR ("genomic") OR ("genetic") OR ("informatic") OR ("gene")) AND (("software") OR ("tool") OR ("platform") OR ("analysis") OR ("user-friendly") OR ("UCD")) AND ("2003"[Date - Publication] : "3000"[Date - Publication]) AND (English[Language])` |
| Web of Science | `(("bioinformatic") OR ("biomedical informatic") OR ("genomic") OR ("genetic") OR ("informatic") OR ("gene")) AND (("software") OR ("tool") OR ("platform") OR ("analysis") OR ("user-friendly") OR ("UCD"))` |
| Medline | `(("bioinformatic") OR ("biomedical informatic") OR ("genomic") OR ("genetic") OR ("informatic") OR ("gene")) AND (("software") OR ("tool") OR ("platform") OR ("analysis") OR ("user-friendly") OR ("UCD"))` |
| Bioinformatics Software DB | Individual Searches: `"genomic"`, `"gene"`, `"user-friendly"`, `"analysis"`, `"GWAS"` |
| Google Scholar | `(("bioinformatic") OR ("biomedical informatic") OR ("genomic") OR ("genetic") OR ("informatic") OR ("gene")) AND (("software") OR ("tool") OR ("platform") OR ("analysis") OR ("user-friendly") OR ("UCD"))` |

## Needs Assessment Methodology

- **Participants**: 12 graduate students from the University of Washington and Tulane University. Participants had prior experience with informatics tools but less than 3 years of experience with genomic analyses.
- **Interviews**: 45-minute semi-structured interviews were conducted, exploring early research experiences, resources utilized, specific software tool attributes, and emotional/cognitive reactions to bioinformatics workflows.
- **Analysis**: Audio recordings were transcribed via HappyScribe. Template analysis was then conducted using ATLAS.ti to identify emergent qualitative themes. The full codebook used for the analysis is provided below:

| Code | Description |
| --- | --- |
| First experiences | describes their first experiences when they got into bioinformatics/genomics research |
| Resources used when getting into field | describes what kinds of resources (textbooks, tutorials, courses) they used to help them get into genomics research and conduct experiments |
| Specific software tool(s) | describes any specific tool or software package used to conduct their experiments/workflows |
| Emotional reaction | describes any emotional reaction to utilizing specific tool (i.e. was satisfied, frustrated because of _______) |
| Cognitive reaction | describes any cognitive reaction to utilizing specific tool (i.e. was not able to understand, understood usage and setup easily) |
| Overall experience | describes any overall experience details that were not captured by the other codes |
| Benefits of specific tool | describes specific benefits in utilizing analysis tool (features, usability, etc.) |
| Barriers of specific tool | describes specific barriers in utilizing analysis tool (shortcomings, usability, etc.) |
| Impact on upkeep/cost | describes any costs on data upkeep or analysis computational costs that were incurred as a result of the tool |
| Overall impact | describes any overall impact details that were not captured by the other codes |
| Suggested improvements | describes what improvements would they like to see in the specific tool or more generally to bioinformatics tools being developed in the future |
| Challenges/concerns with cloud genetics | describes what challenges/concerns exist in the future of performing genomics analysis on the cloud |

## Repository Structure

- `propective_interviews/`: Contains the data and materials for the needs assessment portion.
  - `example_raw_transcripts/`: Subset of anonymized, un-coded transcript files from the participant interviews.
  - `example_coded_transcripts/`: Subset of anonymized transcripts coded using ATLAS.ti, capturing the qualitative themes and hierarchical codes utilized in the study.
  - `Interview_Guide.pdf`: The semi-structured interview guide used to conduct the interviews.
- `retrospective_literature_review/`: Contains the data for the literature review portion.
  - `Existing_Genomics_Tools.xlsx`: Retrospective literature review of existing genomics tools, formatted as an Excel sheet containing one row per tool.
- `Frontiers in Bioinformatics Manuscript.docx`: The manuscript detailing the study's findings.
- `LICENSE`: The license for utilizing this dataset.

## Key Findings from the Needs Assessment

The interviews revealed that NGRs primarily faced widespread adoption challenges due to:
- Poor, convoluted documentation and a lack of readily-accessible layman tutorials.
- Challenges with software installation, dependency coordination, and setup.
- Inconsistent and unclear error messages.
- Difficulties in sharing and reproducing results.

Insights gained from these interviews, combined with a literature review, were ultimately used to develop a standardized evaluation rubric to grade existing and future bioinformatics tools on their user-centered design (UCD) implementations.