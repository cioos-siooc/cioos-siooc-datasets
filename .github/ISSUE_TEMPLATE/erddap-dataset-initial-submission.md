---
name: ERDDAP Dataset Initial Submission
about: 'This issue template present the general CIOOS dataset submission workflow. '
title: 'Dataset Submission: Dataset ID Here'
labels: Submission
assignees: ''
---

# CIOOS Dataset Workflow
Listed below are the different steps related to the initial submission of a dataset. 
Fill in as many details as possible. It is expected that most but not all datasets will follow similar stages. The workflow is not linear but all 'Essential' stages will need to be completed for dataset to be marked as 'Complete'
## Initial Submission
- [ ] CIOOS dataset submission process initiated
- [ ] CIOOS Metadata form completed

## Create ERDDAP Dataset
- [ ] Transform data into ERDDAP compatible format
- [ ] QARTOD Integration (optional)
- [ ] Create <dataset_id>.xml for ERDDAP
- [ ] Review dataset on ERDDAP
- [ ] Test dataset on dev/test server

## Create CKAN Record
- [ ] Create CKAN record using metadata entry tool []
- [ ] Review record on test/dev server
- [ ] Test dataset on dev/test server

## Dataset Review
- [ ] Dataset Development Branch Revision (Reviewer Label)
    - :green_circle: Reviewer Approved
    - :yellow_circle: Reviewer Minor Revisions
    - :orange_circle: Reviewer Major Revisions

## Dataset Completion
- [ ] Merge Development Dataset to Production Branch 
- [ ] COMPLETED
