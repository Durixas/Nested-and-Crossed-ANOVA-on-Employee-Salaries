# Nested-and-Crossed-ANOVA-on-Employee-Salaries

This repository contains coursework on Design of Experiments focusing on the Nested and Crossed ANOVA analysis of employee salaries within Montgomery County.

## Overview

The analysis aims to assess the impact of specific factors—domain, department, division, and gender—on the salaries of permanent employees based on the 2023 dataset released by the government. Prior to analysis, thorough preprocessing will be conducted to ensure data accuracy and consistency, addressing missing values and outliers. The study utilizes a Nested and Crossed ANOVA approach, implementing a sampling method that reflects the hierarchical structure of the data for a nuanced exploration of factor interactions.

## Sampling Methodology

The study involves a hierarchical structure of employees. The sampling process for the experimental design employed stratified and cluster sampling methodologies:

- Stratification: Departments were stratified into 3 domains—Public Safety, Administrative Services, and Community Services. Within each domain, 3 departments were randomly selected.
- Cluster Sampling: Within selected departments, 6 distinct divisions were chosen, and within each division, 6 employees were sampled. Gender representation was balanced within divisions, with equal numbers of male and female employees sampled.

## ANOVA Model

The ANOVA model incorporates Gender ($A$), Domain ($B$), Department ($C$) nested within Domain, and Division ($D$) nested within Department. Gender and Domain effects are considered fixed, while Department and Division effects are treated as random.

## Results Summary

The analysis reveals significant impacts on salaries from department and division factors, highlighting their importance within the studied context. Conversely, gender differences did not manifest as significant predictors of salary outcomes.
