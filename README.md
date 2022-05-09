# Reproducibility-Project-DL4H

This repository contains code and other materials for reproducing the paper ”Learning
Robust Patient Representations from Multimodal
Electronic Health Records: A Supervised
Deep Learning Approach” by Xianli Zhang et al.

Dependencies:
- pandas
- sklearn
- pytorch

Data download instructions:

Get preprocessed data from [mimic-extract pipeline GCP bucket](https://console.cloud.google.com/storage/browser/mimic_extract)

Requires authorization from physionet and credentials linked to GCP account

Steps to obtain results
1. Run notebook `baselines_dataset_construction` to create artifacts (pkl files containing the data formatted for pytorch dataloaders)
2. Run notebook `baselines` to get results for baselines
3. Run notebook `sdprl_dataset_construction` to create artifacts (pkl files containing the data formatted for pytorch dataloaders)
4. Run notebook `sdprl` to get results for the SDPRL framework

[Results table](https://docs.google.com/spreadsheets/d/1_yVKskNSQTT3xZPzXZ-q0lI_U64Syf7tx4HS0aH9PvY/edit?usp=sharing)
