# ABTesting

**Table of content**

- [ABTesting](#abtesting)
  - [Overview](#overview)
  - [Requirements](#requirements)
  - [Install](#install)
  - [Features](#features)
    - [Data Exploration](#data-exploration)
    - [Classical A/B Testing](#classical-ab-testing)
    - [Sequential A/B Testing](#sequential-ab-testing)
    - [ML A/B Testing](#ml-ab-testing)
    - [Scripts](#scripts)
    - [Test](#test)

## Overview
A/B testing allows comparing two or more versions of a given service against each other to find out which variation performs better. 

This repository contains an implementation of AB testing for the Classical, Sequential, and ML approaches. I have used data collected by an Advertising company running an online ad for a client to increase brand awareness. To increase its market competitiveness, the advertising company provides a further service that quantifies the increase in brand awareness as a result of the ads it shows to online users. 

The main objective is to design a reliable hypothesis testing algorithm to test if the ads that the advertising company runs resulted in a significant lift in brand awareness. Through this, we will explore Classical, Sequential, and ML approaches to A/B testing,

## Requirements
Python 3.5 and above, Pip and MYSQL
## Install
```
git clone https://github.com/eandualem/abtest-mlops
cd abtest-mlops
pip install -r requirements.txt
```
## Features

### Data Exploration
  - The notebook for Data Exploration is inside the notebooks folder in the file classical-ab-testing.ipynb.

### Classical A/B Testing
  - The notebook for Classical A/B Testing is inside the notebooks folder in the file classical-ab-testing.ipynb.

### Sequential A/B Testing
  - The notebook for Sequential A/B Testing is inside the notebooks folder in the file sequential-ab-testing.ipynb.

### ML A/B Testing
  - ML A/B Testing is not implemented here. It can be found here in (abtest-mlops)[https://github.com/eandualem/abtest-mlops]

### Scripts
  - `df_helper`: helper class for reading csv and saving csv files
  - `plot`: 
  - `stat`: 


### Test
  - There is a test file for df_helper inside the tests folder.