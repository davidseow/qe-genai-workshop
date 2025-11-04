# GenAI workshop for Product Quality Engineers

This repository contains materials and resources for the GenAI workshop tailored for Product Quality Engineers. The workshop aims to provide insights into how applications that uses Generative AI can be built, tested, and deployed.

## Product Description Sanitiser (Data Quality Check)
For the purpose of this workshop, we will focus on building a simple application that leverages a Large Language Model (LLM) to enhance product description quality.

Application Goal: A script that takes a product's raw description text (which might contain typos, inconsistent formatting, or even irrelevant marketing fluff) and a pre-defined style guide for the retail brand. The app uses the LLM to check and refine/flag the description against the rules.

### Features
- Input: Raw product description text and a style guide.
- Processing: Use an LLM to analyze the description for:
  - Spelling and grammar errors
  - Consistency with brand tone and style
  - Relevance and clarity of information
- Output: A refined product description that adheres to the style guide, along with a report highlighting any issues found.


