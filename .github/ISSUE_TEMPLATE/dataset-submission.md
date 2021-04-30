---
name: Dataset Status Tracker
title: Dataset ID/Title
about: Track dataset status
labels: enhancement
---

ERDDAP: ERDDAP [link]()
CKAN: CKAN [link]()

# CIOOS Dataset Workflow
Nominal workflow steps/stages are listed below. Please fill in as many details as possible. It is expected that most datasets will follow similar path from submission to completion. \
Note: All 'Essential' stages will need to be completed for dataset to be marked as 'Complete'

## Initial Submission
- [x] Essential - CIOOS dataset submission process initiated (Generated this issue)
- [ ] Essential - Create CKAN record using [metadata entry form](https://cioos-siooc.github.io/metadata-entry-form)

## Create ERDDAP Dataset
- [ ] Optional - Transform data into ERDDAP compatible format
- [ ] Essential - Create <dataset_id>.xml for ERDDAP
- [ ] Essential - Test dataset on dev. ERDDAP server

## Create CKAN Record
- [ ] Essential - Review metadata record on dev/test server (https://pac-dev1.cioos.org/ckan/)

## Review CKAN and ERDDAP record
- [ ] Essential - Reviewed by [Reviewer name/ID and link to issues]
- [ ] Essential - Translations reviewed by [Reviewer name/ID and link to issues]
- [ ] Optional - Dataset and Metadata Reviewed by data provider

## Dataset Completion
- [ ] Essential - Push CKAN record to production server
- [ ] Essential - Push ERDDAP to production server
- [ ] COMPLETED
