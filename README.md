# NDC Data

This repo contains a version of the data files published by the [US National Drug Code Directory](https://www.fda.gov/drugs/drug-approvals-and-databases/national-drug-code-directory).

The published version only contains drugs that are _currently_ marketed; historic drugs are not included.

This makes the database incomplete with respect to projects that analyse historic prescribing data.

This repo uses Github Actions to fetch the data each day.

The diffs for these files will therefore contain products as they are removed and added.

I have also made a FOIA request to get historic data going back to 2009. If/when I get a response, I will update this repo.