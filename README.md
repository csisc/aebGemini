# aebGemini
A fun experiment about using LLMs, particularly Gemini API, to enhance language resources for Tunisian

**NOTE:** Please do not take this resource as a serious lexicon for Tunisian.

## Description
aebGemini is an experimental project aimed at testing the use of Large Language Models (LLMs) such as ChatGPT and Gemini for the preprocessing and enhancement of linguistic resources, specifically for the Tunisian dialect. This project focuses on leveraging generative AI tools to improve the quality and accessibility of linguistic datasets like aebWordNet.

## Overview
The main objective of this project is to explore the potential of LLMs to automatically process and enhance linguistic resources, which are often limited or of low quality for underrepresented languages. In this context, we applied different LLMs to handle aebWordNet, a lexicon developed by Nadia Karmani et al. at REGIM Lab, and we evaluated the effectiveness of these models in terms of preprocessing, error correction, and definition generation.

## Approach
The process involves the following steps:

- **XML to Excel Conversion:** The aebWordNet dataset, originally in XML format, was converted into an Excel sheet using ChatGPT 4o. Despite formatting errors in the XML file, the conversion was completed within seconds.

- **Definition Generation Using Gemini API:** We applied Gemini API to process individual entries from aebWordNet. For each term, the model generated a corresponding definition.

- **Results:** While a significant portion of the definitions were accurate, many were incorrect, with some being humorous or completely irrelevant. This shows both the potential and the current limitations of LLMs for resource-poor languages like Tunisian Arabic.

## Key Insights
LLMs can provide partial solutions for the scarcity and poor quality of linguistic resources, especially for languages that have been extensively used to train the models.
However, LLM-generated content still requires human oversight and correction to ensure accuracy and reliability.
The results from this project highlight the importance of continued human involvement in the development of linguistic resources for underrepresented languages.

## Project Structure
- **Source Code:** The Python scripts and necessary files to interact with the ChatGPT API and Gemini API are located in the src folder.
- **Generated Data:** The definitions generated from the LLMs can be found in the output folder, alongside the processed Excel files.
