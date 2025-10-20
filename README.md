# Dataset for An Empirical Study of Privacy Disclosure in Android Application Logs 

This repository contains the datasets used in our study on **Android application logging and privacy policy consistency**.  
Each folder corresponds to one part of our research analysis (RQ1–RQ3).

> ⚠️ The raw log data contains personal information and therefore will not be displayed. It will be released upon acceptance of the paper.

---

## 📂 Files Overview

- **`RQ1.csv`** – Contains app metadata and logging information, including app source, version, number of log lines, and privacy policy link.  
- **`RQ2.csv`** – Records privacy policy content related to logging, describing what data types are mentioned and for what purposes.  
- **`RQ3_Alignment.csv`** – Summarizes the alignment results between privacy policies and privacy leakage in Android log files.  
- **`RQ3_App_catagory.csv`** – Lists the distribution of analyzed apps have privacy leakage across different Google Play categories.  
- **`RQ3_Privacy_information_list.csv`** – Defines the privacy information types used for leakage detection.  
- **`RQ3_Privacy_leakage_case.csv`** – Contains detected privacy leakage cases from app logs.  
- **`RQ3_Unstated_leakage.csv`** – Lists leakage cases where the leaked data were **not mentioned** in the corresponding **log-related** privacy policy.  

