# SampleSkipUnspecifiedVersion

This is the minimal reproduction for https://github.com/renovatebot/renovate/pull/23206 

## Current behavior

The latest version of Fakery (https://github.com/vadymmarkov/Fakery) is 5.1.0, but Renovate skips it and does not create a pull request to update to the latest version 5.1.0.

[mend.log](https://github.com/maoyama/SampleSkipUnspecifiedVersion/files/12000028/mend.log)

## Expected behavior

Renovate should create a pull request to update Fakery to version 5.1.0.
