# Inventory Recall Quantity Recommendation Engine

## Project Summary
Developed an Excel-based inventory recommendation engine to support retail stock recall planning. The solution analyses sales performance, stock positions, warehouse availability and inventory cover metrics to generate statistically supported recall quantity recommendations, reducing manual effort and improving decision consistency.

## Business Problem
After styles had been identified for recall, stock controllers still needed to manually determine how many pairs should be recalled.
This required reviewing multiple inventory indicators including stock positions, warehouse inventory, online commitments, sales history and future deliveries before deciding an appropriate recall quantity.

Because the process relied on manual interpretation of several metrics, decisions could be time-consuming and inconsistent. Whilst the source reports contained all of the required information, determining the ideal recall quantity still required manual judgement.

## Solution Developed
I developed an automated inventory recommendation engine that calculates an ideal recall quantity, based on weeks-of-cover principles, for styles already selected for recall.

The model analyses inventory and operational metrics and generates a recommended recall quantity using predefined business rules. Rather than manually reviewing multiple data points for every style, the solution provides a data-driven recommendation which can then be reviewed by the planner.
The calculation engine evaluates stock positions, warehouse availability, online stock commitments, sales performance, future deliveries, and weeks cover to generate a recommended recall quantity.

## Methodology
The recommendation engine uses a combination of stock position, warehouse availability, online commitments, sales history, future deliveries, and weeks-of-cover calculations to estimate an appropriate recall quantity. The recommendation is designed to provide a consistent starting point for planner review rather than replace human decision-making.

## Business Impact
Prior to the development of the recommendation engine, determining recall quantities required stock controllers to manually review multiple inventory indicators including stock positions, warehouse availability, online commitments, sales performance, delivery schedules, and inventory cover metrics before making a judgement on the appropriate recall quantity.

The recommendation engine consolidated this information into a structured decision-support process, automatically evaluating the key inventory metrics and generating a recommended recall quantity based on predefined business rules.

This delivered several improvements:

Improved Efficiency
* Reduced the time required to review inventory data and determine recall quantities by automating the evaluation of multiple inventory indicators.

More Consistent Decision Making
* Applied the same business rules and inventory planning principles across all styles, helping to ensure recall decisions were based on a consistent approach.

Better Use of Planner Time
* Allowed planners to focus on reviewing recommendations and investigating exceptions rather than performing repetitive calculations and data interpretation.

Increased Confidence in Decisions
* Provided statistical and inventory-based justification for recommended recall quantities, supporting decisions with data rather than relying solely on manual judgement.

Scalable Process
* Enabled larger volumes of inventory data to be assessed efficiently without a proportional increase in manual workload.

## Tools & Technologies Used
* Microsoft Excel
* Office Scripts

## Screenshots & Workflow Evidence
The screenshots below demonstrate the workflow used to prepare, export and process inventory recall data. They show how raw operational information was structured before being used to generate recall quantity recommendations. 

To protect commercially sensitive information, all screenshots used anonymized or representative data. The workflow, logic, and outputs accurately reflect the process used within the solution.

### Screenshot 1: Data preparation in MAPPER
This screenshot shows the customised RID created in MAPPER to organise the required inventory data before export. This step ensured the source data was structured consistently for analysis.
 
### Screenshot 2: Export-ready inventory dataset
The RID was populated with the key fields needed to apply the recall quantity business rules, including stock, sales and inventory indicators. At this stage, the dataset was ready to be exported into Microsoft Excel for processing.
 
### Screenshot 3: Data Transformed in Excel
This screenshot demonstrates how the exported data was brought into Excel and prepared for automated recommendation logic. The model applies predefined rules to support consistent recall quantity decisions. 

### Screenshot 4: Office Script automation
This screenshot shows the Office Script used to automate key parts of the workflow between the Excel calculation model and the final recommendation output. The script helped standardise repeatable steps, reduce manual processing, and make the process faster, cleaner, and more consistent.

### Screenshot 5: Excel Decision Support Model
The final output provides a recommended recall quantity for review. This gives planners a clear, data-supported starting point and reduces the amount of manual interpretation required.

## Skills Demonstrated
*	Data Preparation
*	Data Transformation
*	Data Analysis
*	Excel Automation
*	Office Scripts
*	Inventory Analysis
*	Business Analysis
*	Decision Support Modelling
*	Business Process Improvement
*	Inventory Management
