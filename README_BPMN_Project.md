# RouteWise Logistics — BPMN Process Analysis and Improvement

## Project Overview

This project presents a Business Analysis and process improvement case study for RouteWise Logistics. The objective was to analyse the current logistics workflow, identify operational pain points, define business requirements and design an improved future-state process using BPMN.

The project combines AS IS and TO BE process mapping, stakeholder analysis, user stories, acceptance criteria, business rules, Agile planning and continuous improvement.

> This case study is fictitious and was created exclusively for educational and portfolio purposes.

\---

## Business Objective

Improve logistics performance by:

* Increasing process visibility
* Identifying delays and operational bottlenecks
* Clarifying roles and responsibilities
* Connecting KPIs with process stages
* Supporting root-cause analysis
* Defining preventive and corrective actions
* Improving SLA compliance
* Enabling continuous improvement

\---

## AS IS Process

The current-state process covers:

1. Receive the order
2. Register the order
3. Prepare the order
4. Assign the carrier
5. Start delivery
6. Check whether the delivery was completed within the SLA
7. Register delayed orders
8. Register customer complaints
9. Close the order

The current process is mainly reactive because delays and complaints are handled after they occur.

!\[AS IS Process](images/as-is-process.png)

\---

## TO BE Process

The future-state process introduces:

1. Order data validation
2. Estimated delivery date calculation
3. Delay-risk assessment
4. Early identification of delay causes
5. Carrier reassignment or route adjustment
6. Operations-team notification
7. Preventive action
8. Delivery-status monitoring
9. Delay alerts
10. Identification of the affected order, carrier and region
11. Corrective-action definition
12. Customer notification
13. Corrective-action monitoring
14. Performance evaluation
15. Action-plan review when necessary
16. KPI updates
17. Order closure

The TO BE process moves the operation from reactive issue handling to proactive risk management.

!\[TO BE Process](images/to-be-process.png)

\---

## End-to-End Improvement Process

The end-to-end BPMN model connects operational data, analysis, decision-making and corrective action.

### Participants

* Operational Systems
* BI Analyst
* Power BI Platform
* Operations Manager
* Carrier and Warehouse Teams

### Main Stages

* Record operational data
* Collect and review source data
* Clean and standardise data
* Validate fields, dates, statuses and identifiers
* Create the dimensional model
* Define table relationships
* Create calculated columns and DAX measures
* Document KPI definitions and business rules
* Refresh the semantic model
* Calculate logistics KPIs
* Generate alerts and risk indicators
* Analyse performance
* Identify root causes
* Define and assign corrective actions
* Evaluate results
* Close or revise the action plan

!\[End-to-End Improvement Process](images/end-to-end-process.png)

\---

## Stakeholders

|Stakeholder|Responsibility|
|-|-|
|Operations Manager|Monitors performance and defines corrective actions|
|Logistics Supervisor|Identifies delays and operational deviations|
|Business Analyst|Defines requirements, process rules and improvement opportunities|
|Finance Analyst|Analyses logistics costs|
|Customer Experience Manager|Monitors returns and complaints|
|BI Analyst|Prepares data and supports KPI analysis|
|Carrier and Warehouse Teams|Implement corrective and preventive actions|

\---

## Product Backlog — User Stories

|ID|User Role|User Story|Business Value|Priority|
|-|-|-|-|-|
|US01|Operations Manager|View the total number of orders|Monitor operational volume|High|
|US02|Logistics Supervisor|Identify delayed orders|Act quickly|High|
|US03|Business Analyst|Monitor Delivery SLA|Assess operational performance|High|
|US04|Finance Analyst|Analyse average delivery cost|Control logistics expenses|Medium|
|US05|CX Manager|Monitor returns|Identify recurring issues|Medium|
|US06|Operations Manager|Filter by region, carrier and period|Analyse the causes of deviations|High|
|US07|Business Analyst|Visualise AS IS and TO BE processes|Link KPIs to process improvement|High|

\---

## Acceptance Criteria Example

### User Story

As a Business Analyst, I want to monitor the Delivery SLA so that I can assess operational performance.

### Acceptance Criteria

* The dashboard must display the Delivery SLA KPI as a percentage.
* The user must be able to filter by month, region and carrier.
* Deliveries outside the SLA must be clearly visible.
* Cancelled orders must be excluded from the SLA calculation.
* The KPI must be validated against the data source.

\---

## Agile Delivery Approach

The project was structured around:

* Transparency
* Collaboration
* Iteration
* Incremental delivery
* Business-value prioritisation
* End-user focus
* Continuous improvement

### Sprint 1 — Data Preparation and Modelling

* Import and validate the dataset
* Clean and transform data
* Handle null values and inconsistencies
* Create calculated columns
* Build the data model
* Validate the data

### Sprint 2 — KPI Development and Dashboard

* Create DAX measures
* Develop the main KPIs
* Build the Executive Overview
* Create performance visuals
* Add filters and slicers
* Validate KPIs against the source data

### Sprint 3 — Process Analysis and Improvement

* Map the AS IS process using BPMN
* Identify pain points
* Design the TO BE process
* Map KPIs to process stages
* Improve storytelling
* Prepare documentation and publication

!\[Agile Delivery Approach](images/agile-delivery-approach.png)

\---

## Key Pain Points Identified

* Reactive delay management
* Limited early identification of delivery risk
* Weak connection between issues and corrective actions
* Unclear ownership of improvement actions
* Limited visibility of affected orders, carriers and regions
* Limited monitoring of action effectiveness

\---

## Improvement Opportunities

* Validate order data before execution
* Assess delay risk earlier
* Generate automated alerts
* Reassign carriers or adjust routes
* Notify operations teams and customers earlier
* Define corrective-action ownership
* Monitor action status and outcomes
* Link KPIs to process stages
* Establish a continuous improvement loop

\---

## Results and Benefits

* Better process visibility
* Faster identification of delays and deviations
* Improved SLA compliance
* Proactive risk identification
* Clearer roles and responsibilities
* Better stakeholder communication
* Faster preventive and corrective actions
* Improved traceability of business rules
* Data-driven decision-making
* Continuous improvement

\---

## Tools, Methods and Skills

* BPMN
* AS IS / TO BE Process Mapping
* Business Analysis
* Requirements Gathering
* Requirements Analysis
* Stakeholder Analysis
* Gap Analysis
* Root-Cause Analysis
* Process Improvement
* Business Rules
* KPI Mapping
* User Stories
* Acceptance Criteria
* Product Backlog
* Agile
* Sprint Planning
* Kanban
* Continuous Improvement
* Process Documentation

\---

## Repository Structure

```text
routewise-logistics-bpmn-process-analysis/
│
├── docs/
│   └── RouteWise\_Logistics\_BPMN\_Portfolio.pdf
│
├── images/
│   ├── agile-delivery-approach.png
│   ├── as-is-process.png
│   ├── to-be-process.png
│   └── end-to-end-process.png
│
├── source/
│   └── RouteWise\_Logistics\_Process\_Model.vsdx
│
├── README.md
├── LICENSE
└── .gitignore
```

\---

## Project Deliverables

* AS IS BPMN process
* TO BE BPMN process
* End-to-end improvement process
* Stakeholder analysis
* Product backlog
* User stories
* Acceptance criteria
* Agile sprint plan
* Kanban board
* Business-rules documentation
* Process improvement recommendations
* Portfolio documentation

\---

## Author

**Érica Adriana Marques Teodoro**

Electrical Engineer | Business Analyst | Data Analysis | Process Improvement

