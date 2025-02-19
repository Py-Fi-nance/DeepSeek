# DeepSeek vs. OpenAI
### Converting Unstructured Data into Indicator Columns

This repository contains two versions of the same program: one that uses OpenAI models, and another that uses DeepSeek models for comparison.

We found that the OpenAI models are significantly faster, the DeepSeek models are significantly cheaper, and both companies' models commit similar errors.

How did this project come about?

[PyFi](https://pyfi.com) teaches finance professionals how to code in Python. To support our marketing, we analyzed a set of job postings to understand why companies hire finance professionals with Python skills.

As part of our analysis, we asked, "What alternative tools do these job postings list alongside Python?" Our research assistant copied tools into a spreadsheet, but the tool names and list formatting were inconsistent. In order to analyze this unstructured data, we needed to convert it into structured data.

The purpose of the Python program in this repository is to convert the unstructured data in the "Alternatives" column of Job Data.csv into a set of correctly-flagged indicator columns to support PyFi's analysis.
