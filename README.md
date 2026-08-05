RouteWise Logistics — BPMN Process Analysis and Improvement
Project Overview
This project presents a Business Analysis and process improvement case study for RouteWise Logistics. The objective was to analyse the current logistics workflow, identify operational pain points, define business requirements and design an improved future-state process using BPMN.
The project combines AS IS and TO BE process mapping, stakeholder analysis, product backlog, user stories, acceptance criteria, business rules, KPI alignment, Agile planning, Kanban, root-cause analysis and continuous improvement.
> This case study is fictitious and was created exclusively for educational and portfolio purposes.
---
Business Objective
Improve visibility into logistics performance by monitoring deliveries, SLAs, delays, costs and returns, while supporting data-driven decision-making and continuous process improvement.
The project aims to:
Increase process visibility
Identify delays and operational bottlenecks
Clarify roles and responsibilities
Connect KPIs with process stages
Support root-cause analysis
Define preventive and corrective actions
Improve SLA compliance
Enable continuous improvement
---
Agile Delivery Approach
The project was structured around transparency, collaboration, iteration and continuous delivery.
![Agile Delivery Approach](images/agile-delivery-approach.png)
Sprint 1 — Data Preparation and Modelling
Import and validate the dataset
Clean and transform data in Power Query
Handle null values and inconsistencies
Create calculated columns
Build and validate the data model
Deliverable: Clean data model ready for analysis.
Sprint 2 — KPI Development and Dashboard
Create DAX measures
Develop the main KPIs
Build the Executive Overview
Create performance visuals
Add dynamic slicers and filters
Validate KPIs against the data source
Deliverable: First functional version of the dashboard.
Sprint 3 — Process Analysis and Improvement
Map the AS IS process using BPMN
Identify process pain points
Design the TO BE process
Map KPIs to process stages
Improve storytelling
Prepare documentation and publication
Deliverable: Final dashboard with process analysis and documentation.
---
Kanban Board
Done
Data cleaning and preparation
Relational data model
Main DAX measures
Executive Overview page
AS IS and TO BE BPMN processes
In Progress
Improve the GitHub README
Review DAX measures
Create business-rules documentation
To Do
Add advanced SQL analysis
Create a drill-through detail page
Improve page tooltips
Add delay forecasting using time-series analysis
---
Product Backlog — User Stories
ID	User Role	I Want To	So That	Priority
US01	Operations Manager	View the total number of orders	Monitor operational volume	High
US02	Logistics Supervisor	Identify delayed orders	Act quickly	High
US03	Business Analyst	Monitor Delivery SLA	Assess operational performance	High
US04	Finance Analyst	Analyse average delivery cost	Control logistics expenses	Medium
US05	CX Manager	Monitor returns	Identify recurring issues	Medium
US06	Operations Manager	Filter by region, carrier and period	Analyse the causes of deviations	High
US07	Business Analyst	Visualise the AS IS and TO BE processes	Link KPIs to process improvement	High
---
Acceptance Criteria Example
User Story
As a Business Analyst, I want to monitor the Delivery SLA so that I can assess operational performance.
Acceptance Criteria
The dashboard must display the Delivery SLA KPI as a percentage.
The user must be able to filter by month, region and carrier.
Deliveries outside the SLA must be clearly visible.
Cancelled orders must be excluded from the SLA calculation.
The KPI must be validated against the data source.
---
KPIs Tracked
Total Orders
Delivered Orders
Delayed Orders
Delivery SLA (%)
Average Delivery Time
Average Delivery Cost
Return Rate
Customer Complaints
---
AS IS Process — Current Process
The current logistics workflow includes:
Receive and register the order
Prepare the order
Assign the carrier
Start delivery
Check SLA compliance
Register delayed orders
Register customer complaints
Close the order
The current process is mainly reactive because delays and complaints are handled after they occur.
![AS IS Process](images/as-is-process.png)
---
TO BE Process — Improved Process
The future-state process introduces:
Order-data validation
Estimated delivery-date calculation
Delay-risk assessment
Early identification of delay causes
Carrier reassignment or route adjustment
Operations-team notification
Preventive action
Delivery-status monitoring
Delay alerts
Identification of the affected order, carrier and region
Corrective-action definition
Customer notification
Corrective-action monitoring
Performance evaluation
Action-plan review when necessary
KPI updates
Order closure
The TO BE process moves the operation from reactive issue handling to proactive risk management.
![TO BE Process](images/to-be-process.png)
---
End-to-End Logistics Performance and Improvement Process
The end-to-end BPMN model connects operational data generation, data preparation, KPI calculation, performance monitoring, issue resolution and continuous improvement.
![End-to-End Improvement Process](images/end-to-end-process.png)
Participants
Operational Systems
BI Analyst
Power BI Platform
Operations Manager
Carrier and Warehouse Teams
Main Process Stages
1. Operational Data Generation
Record order information
Record shipping and delivery information
Record carrier and warehouse information
Record returns and complaints
Store operational data in source tables
2. Data Preparation and Validation
Collect data from source tables
Review the data structure and business requirements
Clean and standardise data in Power Query
Validate fields, dates, statuses and identifiers
Correct transformation rules or request source-data correction
Create a dimensional data model
Define table relationships
Create calculated columns and DAX measures
Document KPI definitions and business rules
3. KPI Calculation and Visualisation
Refresh the semantic model
Calculate logistics KPIs
Update dashboard visuals
Generate performance alerts and risk indicators
4. Performance Monitoring and Decision-Making
Review the Executive Overview
Analyse delivery, carrier, regional, cost and return performance
Identify the affected carrier, warehouse or region
Analyse the root cause
Define corrective action
Assign the action to the responsible team
5. Corrective Action and Continuous Improvement
Review the operational issue
Implement corrective action
Report action status and results
Evaluate whether performance improved
Close the improvement action or revise the action plan
---
Key Pain Points
Reactive handling of delivery delays
Limited early identification of delivery risk
Weak connection between operational issues and corrective actions
Unclear ownership of improvement actions
Limited visibility of affected orders, carriers and regions
Limited monitoring of action effectiveness
---
Improvement Opportunities
Validate order data before execution
Calculate estimated delivery dates
Assess delay risk earlier
Generate automated alerts
Reassign carriers or adjust routes
Apply preventive action before SLA breaches
Notify operations teams and customers earlier
Define corrective-action ownership
Monitor action status and outcomes
Link KPIs to process stages
Establish a continuous improvement loop
---
Project Deliverables
Agile delivery approach
Sprint plan
Kanban board
Product backlog
User stories
Acceptance criteria
AS IS BPMN process
TO BE BPMN process
End-to-end improvement process
Stakeholder analysis
KPI mapping
Business-rules documentation
Process improvement recommendations
Project documentation
GitHub publication
---
Results and Benefits
Clear visibility into logistics performance
Rapid identification of delays and deviations
Improved SLA compliance
Reduced operational costs
Reliable data-driven decision-making
Mapped and optimised processes
Proactive risk identification
Faster operational actions
Improved stakeholder communication
Clearer roles and responsibilities
Continuous improvement
---
Tools, Methods and Skills
BPMN
AS IS / TO BE Process Mapping
Business Analysis
Requirements Gathering
Requirements Analysis
Stakeholder Analysis
Gap Analysis
Root-Cause Analysis
Process Improvement
Business Rules
KPI Mapping
User Stories
Acceptance Criteria
Product Backlog
Agile
Sprint Planning
Kanban
Continuous Improvement
Process Documentation
---
Repository Structure
```text
routewise-logistics-bpmn-process-analysis/
│
├── docs/
│   └── RouteWise_Logistics_BPMN_Portfolio.pdf
│
├── images/
│   ├── agile-delivery-approach.png
│   ├── as-is-process.png
│   ├── end-to-end-process.png
│   └── to-be-process.png
│
├── source/
│   └── RouteWise_Logistics_Process_Model.vsdx
│
├── README.md
├── LICENSE
└── .gitignore
```
---
Data Disclaimer
This project is a fictitious case study created exclusively for educational and portfolio purposes.
No real customer, carrier, employee or company information is included.
---
Author
Érica Teodoro
Electrical Engineer | Business Analyst | Data Analysis | Process Improvement
