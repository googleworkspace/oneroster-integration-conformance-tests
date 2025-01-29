# OneRoster Integration Conformance Tests

## Overview
This repository contains test suites that will validate if your product meets the Google OneRoster consumption requirements.

*Note: This is separate from [1EdTech’s conformance testing](https://www.1edtech.org/standards/oneroster/conformance-testing) and does not grant any certification for conformance.*

## OneRoster Versions
Only ONE version is necessary. **Strong preference** for OneRoster 1.2 if possible. Please email us if that is not feasible.

### OneRoster 1.2
[Google Colab Direct Link](https://colab.research.google.com/github/googleworkspace/oneroster-integration-conformance-tests/blob/main/oneroster_1_2_test_suite.ipynb)

[OneRoster 1.2](https://www.imsglobal.org/spec/oneroster/v1p2) Specification

### OneRoster 1.1
[Google Colab Direct Link](https://colab.research.google.com/github/googleworkspace/oneroster-integration-conformance-tests/blob/main/oneroster_1_1_test_suite.ipynb)

[OneRoster 1.1](https://www.imsglobal.org/node/151081) Specification

## How to run

Before you begin, you will need:

* Token URL to retrieve OAuth 2 credentials
* One Roster URL ending in /ims/oneroster/v1p2 or /ims/oneroster/v1p1
* Client ID
* Client secret
* A teacher email address

### Test Structure

All sections are **required** unless otherwise stated.

The notebook is structured so that each cell can be run and tested individually for easy development. However, when you are ready to submit results to Google, it is preferable to run all of the tests at once for a fully generated test report. Both Jupyter notebook and Colab allow you to run all cells.

## How to submit results
Once you have a fully generated test report, download or screenshot the results. Email the downloaded file or screenshot to [classroom-sis-external@google.com](mailto:classroom-sis-external@google.com). 
