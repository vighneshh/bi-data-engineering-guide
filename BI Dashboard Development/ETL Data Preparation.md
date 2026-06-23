# 📋 Step 5: ETL / Data Preparation

The goal of this phase is to **extract data from the source systems, transform it into the required format, and load it into the BI data model** while ensuring accuracy, consistency, and performance.

## ETL / Data Preparation Questionnaire

### 📥 Extract

* [ ] Can I successfully connect to all required data sources?
* [ ] Are all required tables/files being extracted?
* [ ] Are only the necessary columns being loaded?
* [ ] Is the extraction process automated?
* [ ] Are there any extraction errors or missing records?

---

### 🔄 Transform

#### 🧹 Data Cleansing

* [ ] Have duplicate records been removed?
* [ ] Have missing values been handled?
* [ ] Have invalid records been corrected or excluded?
* [ ] Are data formats standardized (Date, Number, Text)?
* [ ] Are naming conventions consistent?

---

#### 🔗 Data Integration

* [ ] Are all tables joined correctly?
* [ ] Are lookup/mapping tables applied?
* [ ] Are relationships preserved after transformation?
* [ ] Have orphan records been handled?

---

#### 📊 Business Rules

* [ ] Have all business rules been applied?
* [ ] Are calculated fields created where required?
* [ ] Are status flags and classifications derived correctly?
* [ ] Have mappings (Country, Region, Product, ERP, etc.) been applied?

---

#### 📅 Date Preparation

* [ ] Are date fields converted to the correct format?
* [ ] Is the Calendar/Date table generated?
* [ ] Are Fiscal Year, Quarter, Month, Week, and Day fields created?
* [ ] Are all date relationships validated?

---

#### 🏷️ Data Standardization

* [ ] Are field names standardized?
* [ ] Are data types optimized?
* [ ] Are codes translated into business-friendly values?
* [ ] Are units of measure consistent?

---

### 📤 Load

* [ ] Is the transformed data loaded into the data model?
* [ ] Are all fact and dimension tables populated?
* [ ] Are row counts validated after loading?
* [ ] Is incremental loading required?
* [ ] Is the load process optimized for performance?

---

### ⚡ Performance Optimization

* [ ] Have unnecessary columns been removed?
* [ ] Have unnecessary records been filtered?
* [ ] Are joins optimized?
* [ ] Are transformations performed efficiently?
* [ ] Is memory usage optimized?

---

### ✔️ Validation

* [ ] Do row counts match the source?
* [ ] Do totals match the source system?
* [ ] Are KPIs producing expected values?
* [ ] Are all relationships working correctly?
* [ ] Are there any transformation errors?

---

### 📝 Error Handling & Logging

* [ ] Are ETL errors logged?
* [ ] Are rejected records captured?
* [ ] Is there a process for retrying failed loads?
* [ ] Are validation results documented?

---

### 🔄 Automation & Scheduling

* [ ] Is the ETL process fully automated?
* [ ] Is the refresh schedule configured?
* [ ] Are dependencies between ETL jobs handled?
* [ ] Are notifications configured for ETL failures?

---

# ✅ Deliverables

By the end of this phase, you should have:

* [ ] ETL scripts or workflows
* [ ] Cleaned and transformed datasets
* [ ] Populated fact and dimension tables
* [ ] Calendar/Date table
* [ ] Lookup and mapping tables
* [ ] Validation report (row counts, totals, KPI checks)
* [ ] ETL error and execution logs
* [ ] Automated refresh process (if applicable)

---

> **Note:** This phase focuses on **building the data pipeline**, not creating dashboard visuals. Once the ETL process consistently produces clean, validated data, you are ready for the next phase: **KPI & Measure Definition**.
