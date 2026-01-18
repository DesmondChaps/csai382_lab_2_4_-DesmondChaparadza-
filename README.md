# CSAI 382 Lab 2.4 – Reproducibility and Logging

## Overview
This project demonstrates a reproducible ETL (Extract, Transform, Load) workflow using Pandas. The notebook includes structured logging, fixed random seeds, data integrity checks, and version control using GitHub.

## How to Run
See `RUN.md` for exact step-by-step instructions to reproduce this project.

## Outputs
- Cleaned (tidy) dataset saved in `/outputs`
- Metrics CSV including top items, revenue by category, and busiest hour
- Timestamped log files saved in `/logs`

## Ethics Reflection
Sensitive information such as customer names, payment details, or authentication tokens should not be logged because logs are often widely accessible and retained long-term. Logging such data could lead to privacy violations or security risks. Reproducibility supports accountability by allowing results to be traced back to exact data and code versions. When data-driven systems affect people, reproducible workflows help ensure fairness by making decisions auditable and open to review.
