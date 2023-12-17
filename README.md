# Liquidity-Adjusted CAPM Replication Study

## Description
This repository is dedicated to replicating the empirical results of the seminal paper on the Liquidity-Adjusted Capital Asset Pricing Model (CAPM) by Acharya and Pedersen. This groundbreaking study has significantly contributed to financial economics by integrating liquidity risk into the traditional CAPM framework.

## Objective
The project aims to replicate the study's results, which analyze the impact of liquidity risk on asset pricing. It involves sourcing historical stock prices, trading volumes, and book-to-market ratios for stocks listed on NYSE and AMEX between July 1, 1962, and December 31, 1999, from the CRSP and COMPUSTAT databases.

## Methodology
The analysis will be carried out using Python, leveraging its extensive libraries for data manipulation and statistical modeling. The stages of the project include:

1. **Data Access**:
   - Retrieve necessary financial data from CRSP and COMPUSTAT.

2. **Data Preprocessing**:
   - Clean and preprocess the data to align with the original study's framework.

3. **Model Implementation**:
   - Implement the Liquidity-Adjusted CAPM in Python.
   - Compute liquidity measures.
   - Construct the market portfolio.
   - Perform regression analysis to identify the liquidity premium on asset returns.

4. **Analysis**:
   - Analyze the results and compare them with the findings of the original paper.
   - Discuss deviations and articulate potential explanations.

## Goals
The project aims to validate the replication of the original findings and explore the practical aspects of empirical financial research.

## Usage
The code and data within this repository are structured to provide a clear replication of the Liquidity-Adjusted CAPM. Users can follow the step-by-step analysis, from data retrieval to final results interpretation.

## Acknowledgments
- Acknowledgment to the authors Acharya and Pedersen for their seminal work in the field.
- Thanks to CRSP and COMPUSTAT for providing the data that made this study possible.
- Appreciation to the Python community for the wide range of tools that support such analyses.
