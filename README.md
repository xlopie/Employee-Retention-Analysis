# Employee Retention and Job Satisfaction Analysis

Introduction to Data Mining project analyzing patterns associated
with employee job satisfaction using KNIME.

- **Student:** Gregory Opie
- **Project format:** Individual
- **Course:** Introduction to Data Mining
- **Software:** KNIME

## 1. Contribution Log

| Member Name | Key Responsibilities | Deliverables/Nodes Owned | Percentage Effort |
| --- | --- | --- | --- |
| Gregory Opie | Data profiling, preparation, analysis, visualization, and documentation | Week 2: CSV Reader, Statistics, GroupBy nodes, Bar Charts, audit report, and checklist. Week 3: Binner, three Rule Engines, two One to Many nodes, Number to String, preparation Metanode, CSV Writer, and Boolean matrix. | 100% |

### Week 2 Progress

- Inspected 14,999 records and 10 features.
- Documented data types, missing values, numerical summaries, and unique values.
- Created Salary, PromotionLast5years, and WorkAccident distribution charts.
- Identified 3,008 repeated rows for further investigation.
- Uploaded the dataset, exported KNIME workflow, and audit report.

### Week 3 Progress

- Used Binner to create three equal-frequency bins for SatisfactionLevel,
  LastEvaluation, and AverageMonthlyHours.
- Used three Rule Engine nodes to label bins Low, Avg, and High.
- Used One to Many to encode categorical features as 0/1 indicators.
- Converted project counts and tenure to categories and encoded them.
- Grouped preparation nodes into an annotated Metanode.
- Successfully reran the preparation branch and exported the CSV.
- Validated 14,999 rows and 39 columns with no missing values
  or values other than 0 and 1.
- Uploaded the Week 3 workflow and Boolean matrix.

## 2. Version Control and Infrastructure

- **Primary Communication Platform:** Individual project; progress documented in this README.
- **Weekly Sync Time:** [Enter your weekly review day and time.]
- **GitHub Repository:** https://github.com/xlopie/Employee-Retention-Analysis

## 3. Workflow Documentation

### KNIME Workflow Overview

The workflow loads JobSatisfaction.csv using CSV Reader.

The Week 2 branches provide statistical summaries and distribution
charts for salary, promotions, and workplace accidents.

The Week 3 Boolean Data Preparation Metanode uses Binner to create
three equal-frequency bins for satisfaction, evaluation, and monthly
hours. Three Rule Engines assign descriptive labels.

One to Many encodes the labeled bins, department, and salary.
Number to String converts project counts and tenure into categories,
which a second One to Many node encodes.

WorkAccident, LeftCompany, and PromotionLast5years remain as existing
binary indicators. CSV Writer exports the final 14,999-row,
39-column Boolean matrix with headers and without RowIDs.

### Key Annotations

- Salary Distribution, Promotion Distribution, and Work Accident
  Distribution identify the Week 2 chart branches.
- Comments explain each Week 3 preparation step.
- The Week 3 Boolean Data Preparation Metanode has a comment
  summarizing binning, labeling, and encoding.
- The CSV Writer comment explains the export settings.

### Known Limitations

- Identical rows cannot automatically be treated as duplicate employees
  because the dataset does not contain employee IDs.
- Binary coding meanings and tenure units need confirmation.
- Low, Avg, and High bins represent relative groups within this dataset,
  rather than established HR thresholds.
- Data distributions and association rules do not establish causation.
- File paths may need updating when running on another computer.
- Binning and Boolean encoding are complete. Association rule mining
  and evaluation are planned for later milestones.

## 4. Individual Agreement and Attestation

**Name:** Gregory Opie

**Signature/confirmation:** G.Opie
