# Project Overview
Aimed to build a serverless pipeline using AWS CDK to analyze the finance data from 3 different sources. The historical stock data is stored in an Amazon RDS database, the historical FOREX data(Foreign Exchange Market) is stored in an AWS S3 bucket in JSON format, and the intraday stock data comes from the Alpha Vantage API. Used AWS serverless technologies like Amazon Lambda and Amazon Glue to process and transform the data from the three data sources. We also use Amazon Athena and Quicksight to analyze and visualize the transformed data.

## Alpha Vantage
From the Alpha Vantage website: "Alpha Vantage provides enterprise-grade financial market data through a set of powerful and developer-friendly data APIs and spreadsheets. From traditional asset classes (e.g., stocks, ETFs, mutual funds) to economic indicators, from foreign exchange rates to commodities, from fundamental data to technical indicators, Alpha Vantage is your one-stop-shop for real-time and historical global market data delivered through cloud-based APIs, Excel, and Google Sheets."

## AWS CDK
The AWS Cloud Development Kit (AWS CDK) is an open-source software development platform for defining cloud architecture in code and provisioning it using AWS CloudFormation. It provides a high-level object-oriented framework for defining AWS resources with the capability of current programming languages. You can quickly include AWS best practices in your infrastructure definition and publish it without worrying about boilerplate logic using CDK's library of infrastructure components

## Tech Stack
Language: Python

Services: AWS CDK, AWS S3, AWS Lambda, Amazon RDS, AWS Glue, Amazon Athena, Quicksight


***Note: The .env file provided lists environment variables that need to be inputted before deploying***
