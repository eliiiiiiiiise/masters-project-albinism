# Human rights observatory: albinism in Africa

## Overview

This project involved the design and development of an online platform to explore publicly available documents reporting human rights violations against people with albinism in Africa. Developed independently over three months, the project combined data collection, natural language processing (NLP), and interactive application development.

## Methodology

1. Requirements Analysis and Design

Conducted stakeholder and market analyses, defined functional and non-functional requirements, designed platform wireframes, and established the development methodology.

2. Data Collection and NLP Pipeline

Retrieved relevant documents from the web using a search API.

Used Google's Gemini model to extract document metadata and relevant quotations.

Applied a zero-shot classification model (MoritzLaurer/deberta-v3-large-zeroshot-v2.0) to assign predefined thematic categories to quotations.

Used spaCy's en_core_web_sm model for named-entity recognition and country extraction.

Cleaned and consolidated the extracted information into a structured dataset containing document metadata, quotations, countries, and associated themes.

The code associated with this is available on this repository.

3. Platform Development and Evaluation

Developed an interactive Streamlit application based on the collected dataset and initial wireframes. Evaluated the platform against the predefined functional requirements and assessed usability using the System Usability Scale (SUS).

The platform is available [here](https://dissertation-edx6nvbixxuceasazfc8xc.streamlit.app/)

[This repository](https://github.com/eliiiiiiiiise/dissertation) contains the platform code.

## Technologies

Python · NLP · Zero-shot Classification · Named-Entity Recognition · spaCy · Transformers · Gemini API · Streamlit

## Key Deliverables

A structured dataset of relevant documents and quotations.

An interactive platform for exploring the collected information.

A usability evaluation based on the System Usability Scale (SUS).
