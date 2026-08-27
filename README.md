# ICS-VTIMEZONE files

This repository provides VTIMEZONE-files for each release of the IANA Timezone-Database

The project was born out of the need for these files and the missing download functionality for **all** of the files
from https://tzurl.org.

This is an addition to that project, in no way a replacement!

The license is the same as of the used VZIC tool

## Release

To create a new release, do the following:

* modify the file `tzdb_version` to contain the new version the release shall represent
* commit a PR of the change
* Merge the PR
* create a new tag from the merge-commit on the main branch. The tag name should just be the timezone-database release-version.
* Push that tag to the repository

Everything else then happens automatically
