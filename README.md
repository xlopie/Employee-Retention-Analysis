# Employee-Retention-Analysis
Introduction to Data Mining project analyzing patterns associated with employee job satisfaction using KNIME.
# Employee Retention and Job Satisfaction Analysis

**Group:** Individual project — Gregory Opie
**Course:** Introduction to Data Mining
**Software:** KNIME

## 1. Contribution Log

| Member Name | Key Responsibilities | Deliverables/Nodes Owned | Percentage Effort |
| --- | --- | --- | --- |
| Gregory Opie | All project responsibilities, including data profiling, preparation, analysis, visualization, and documentation | Week 2: CSV Reader, Statistics, three GroupBy nodes, three Bar Chart nodes, data audit report, and weekly checklist | 100% |

### Week 2 Progress

- Inspected 14,999 records and 10 features.
- Documented data types, missing values, numerical summaries, and unique values.
- Created Salary, PromotionLast5years, and WorkAccident distribution charts.
- Identified 3,008 repeated rows for further investigation.
- Uploaded the dataset, exported KNIME workflow, and audit report.

## 2. Version Control and Infrastructure

- **Primary Communication Platform:** Individual project; progress documented in this README.
- **Weekly Sync Time:** Week 2
- **GitHub Repository:** https://github.com/xlopie/Employee-Retention-Analysis

## 3. Workflow Documentation

### KNIME Workflow Overview

The current Week 2 workflow loads JobSatisfaction.csv using CSV Reader.
Statistics summarizes the dataset. Three separate GroupBy branches
count records by Salary, PromotionLast5years, and WorkAccident.
Each branch connects to a Bar Chart.

### Key Annotations

The current workflow contains these branch labels:

1. Salary Distribution
2. Promotion Distribution
3. Work Accident Distribution

These are node comments. Detailed explanations of the processing
logic still need to be added as workflow or Metanode annotations.

### Known Limitations

- Identical rows cannot automatically be treated as duplicate employees
  because the dataset does not contain employee IDs.
- Binary coding meanings and tenure units need confirmation.
- Week 2 describes distributions; it does not establish causes of
  dissatisfaction.
- Binning, Boolean encoding, and association rule mining are planned
  for later milestones.

## 4. Individual Agreement and Attestation

**Name:** Gregory Opie
**Signature/confirmation:** G.Opie
