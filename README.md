# Power BI AI Insights Guide
*(Key Influencers, Decomposition Tree, Q&A, Smart Narrative)*

## Prerequisites

- Preprocessed CSV file
- Microsoft Power BI Desktop installed
- Dataset successfully loaded

This document explains how to use four AI Insight features in Power BI after data loading is complete.

---

## 1. Key Influencers

### Purpose
Identify which factors most strongly influence a selected metric.

### How to Use
1. Go to **Report View**.
2. In the **Visualizations** pane, select **Key Influencers**.
3. Drag the target metric into the **Analyze** field.
4. Drag explanatory variables into the **Explain by** field.

### What It Does
- Automatically analyzes statistical relationships
- Ranks influencing factors
- Shows relative impact strength
- Provides segmented comparisons

### Use Case Examples
- What factors increase sales?
- What affects customer churn?
- What variables influence performance outcomes?

### Important Notes
- The target field must be numeric or categorical.
- More relevant explanatory variables improve accuracy.
- Results are probabilistic, not absolute conclusions.

---

## 2. Decomposition Tree

### Purpose
Break down a metric step-by-step to identify root causes.

### How to Use
1. Select **Decomposition Tree** from Visualizations.
2. Drag the main metric into the **Analyze** field.
3. Drag categorical variables into the **Explain by** field.
4. Click the "+" icon on the visual to expand by dimension.
5. Use the **AI split option** to let Power BI choose the most impactful breakdown automatically.

### What It Does
- Performs hierarchical drill-down
- Automatically detects highest contributors
- Supports interactive exploration

### Use Case Examples
- Why did revenue drop?
- Which region contributes most to profit?
- Which category drives the highest cost?

### Important Notes
- Works best with well-structured categorical data.
- AI split selects statistically strongest drivers.

---

## 3. Q&A

### Purpose
Query your dataset using natural language.

### How to Use
1. Insert the **Q&A** visual.
2. Type your question in English.

### Example Queries
- total sales by region
- average revenue by month
- highest temperature date
- profit by product category

### What It Does
- Converts natural language into visuals
- Automatically generates charts
- Suggests auto-complete field names

### Important Notes
- English provides more reliable results.
- Use exact column names when possible.
- Keep questions simple and direct.

---

## 4. Smart Narrative

### Purpose
Automatically generate textual summaries of report insights.

### How to Use
1. Go to **Insert**.
2. Click **Smart Narrative**.
3. Power BI generates an automatic summary of the current report.
4. Edit or customize the generated text if needed.

### What It Does
- Detects trends and comparisons
- Generates dynamic summaries
- Updates automatically when data changes

### Use Case Examples
- Executive dashboards
- Summary sections in reports
- Automated insight explanations

### Important Notes
- Output is automatically generated and may require refinement.
- The summary updates dynamically with filters.

---

## Summary

Power BI AI Insights enable:

- Driver detection (Key Influencers)
- Root cause analysis (Decomposition Tree)
- Natural language querying (Q&A)
- Automated insight storytelling (Smart Narrative)

These features allow advanced analysis without writing code.
