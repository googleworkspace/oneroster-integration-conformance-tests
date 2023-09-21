# OneRoster Integration Conformance Tests

## Overview
This repository contains a test suite that can help validate if your product meets the Google OneRoster consumption requirements. At the moment, only [OneRoster 1.1](https://www.imsglobal.org/node/151081) is testable.

*Note: This is separate from [1EdTech’s conformance testing](https://www.imsglobal.org/ims-oneroster-v11-final-conformance-guide) and does not grant any certification for conformance.*

## How to run
View directly in [Google Colab](https://colab.research.google.com/github/googleworkspace/oneroster-integration-conformance-tests/blob/main/oneroster_1_1_test_suite.ipynb) OR download and run using [Jupyter notebook](https://docs.jupyter.org/en/latest/running.html). 

Before you run the tests, you will need:

* Token URL to retrieve OAuth 2 credentials
* One Roster URL ending in /ims/oneroster/v1p1
* Client ID
* Client secret
* A teacher email address

### Test Structure

There are three main sections: 
* Basic Grade Sync
* Grading Categories (for import)
* Grading Periods (for import)

Basic Grade Sync is **required** while Grading Categories and Grading Periods are optional.

The notebook is structured so that each cell can be run and tested individually for easy development. However, when you are ready to submit results to Google, it is preferable to run all of the tests at once for a fully generated test report. Both Jupyter notebook and Colab allow you to run all cells.

## How to submit results
Once you have a fully generated test report, download or screenshot the results. Email the downloaded file or screenshot to [classroom-sis-external@google.com](mailto:classroom-sis-external@google.com). 
