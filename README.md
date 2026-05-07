# Operational Analytics for Animal Shelter Efficiency

### Project Statement

Animal shelters face challenges in managing intake volume, reducing overcrowding, and improving adoption rates. Inefficient allocation of resources and lack of data-driven decision-making can lead to longer shelter stays and lower adoption success.

This project analyzes shelter operations data to identify key factors affecting adoption outcomes and operational efficiency, with the goal of supporting better decision-making.

### Business Objective
The goal is to create a Power BI report that:
- Identifies operational trends
- Improves understanding of live-release performance
- Analysis that support data-driven decision based from:
  - shelter capacity,
  - resource planning,
  - and animal welfare outcomes
- Provide recommendations for strategic improvements in operations and placement success

### Key Questions
The following are questions that should that should be answered:
- How do intake and outcome volumes change over time (month, season, day-of-week)?
- How has the number of pet adoptions changed over the years?
- What is the shelter’s live-release rate, and how has it trended?
- Which types of pets are adopted most often?
- Which species, age groups, or breed types have higher or lower live-release rates?
- Do certain intake types or conditions lead to different outcomes?
- What is the average length of stay, and how does it vary across different animal profiles or outcome types?
- Which animals tend to stay the longest in the shelter, and what characteristics do they share?
- Are there seasonal or day-of-week intake patterns that inform staffing or resource allocation?
- Which intake sources contribute the largest volumes, and what does this imply for community outreach or prevention programs?
- Are there animals that return to the shelter more than once, and what factors predict repeat intakes?
- Which data-driven actions could most effectively improve save rates or reduce length of stay?

### Analysis
The analysis focused on identifying operational patterns and factors that influence adoption outcomes, shelter efficiency, and overall animal welfare. 
#### 1. Adoption Outcome Analysis

The analysis revealed significant differences in adoption outcomes across animal categories, age groups, and intake conditions.

Key Findings
- Certain animal groups experienced consistently lower adoption rates, indicating potential challenges in visibility, demand, or adoptability.
- Younger animals generally showed higher adoption success and shorter shelter stays compared to older animals.
- Animals with medical or behavioral concerns tended to remain in the shelter longer before reaching an outcome.
- Adoption outcomes varied across intake types, suggesting that the condition or background of incoming animals may influence adoption likelihood.

These findings suggest that shelters can improve adoption performance by prioritizing targeted campaigns for low-adoption groups and implementing earlier intervention strategies for animals at risk of extended stays.

#### 2. Length of Stay Analysis

Length of stay is a critical operational metric because prolonged shelter stays increase overcrowding risk, operational costs, and resource strain.

Key Findings
- Animals with longer shelter stays showed lower probabilities of successful adoption outcomes.
- Certain animal categories consistently remained in the shelter longer than others.
- Peak intake periods contributed to increased shelter occupancy and delayed processing times.
- Extended shelter duration may reduce available capacity for future intakes.

Reducing average shelter stay duration can improve operational efficiency, increase intake capacity, and enhance animal welfare outcomes. Early promotion and prioritization of long-stay animals could help mitigate overcrowding issues.

#### 3. Intake Trend Analysis

The intake analysis focused on understanding patterns that affect shelter workload and resource allocation.

Key Findings
- Intake volume fluctuated across different periods, creating operational peaks and bottlenecks.
- Specific intake sources contributed disproportionately to shelter occupancy.
- Seasonal patterns appeared to influence both intake and adoption activity.

Understanding intake trends allows shelters to better allocate staffing, medical resources, and adoption efforts during high-volume periods.

#### 4. Operational Performance Metrics

Several operational KPIs were evaluated to measure shelter effectiveness.

KPIs Analyzed
- Adoption Rate
- Average Length of Stay
- Intake-to-Outcome Ratio
- Outcome Distribution by Animal Type
- Shelter Throughput Trends
- Operational Insight

Monitoring these KPIs regularly can help shelters identify inefficiencies early, optimize workflows, and improve overall operational performance.

### Recommendations
Based on the findings, the following recommendations were identified:

- #### Target Low-Adoption Groups
  Develop targeted adoption campaigns for animal groups with historically lower adoption success.

- #### Reduce Long Shelter Stays
  Prioritize visibility and promotion for animals approaching extended shelter durations.

- #### Improve Intake Planning
  Adjust staffing and operational planning during periods with historically high intake volume.

- #### Enhance Resource Allocation
  Allocate medical, behavioral, and promotional resources toward high-risk or long-stay animals.

### Business Impact

If implemented, these recommendations could help:

- Increase adoption success rates
- Reduce average shelter stay duration
- Improve shelter capacity management
- Enhance operational efficiency
- Support better animal welfare outcomes

<details>
<summary><h3>About Data</h3></summary>
The dataset was collected from Long Beach Animal Care Services.

  #### Data Dictionary
  | Column Name        | Description                                                                   |
  | ------------------ | ----------------------------------------------------------------------------- |
  | Kennel ID          | Identifier for the kennel or housing location                                 |
  | Animal ID          | Unique identifier assigned to each animal                                     |
  | Animal Name        | Name of the animal                                                            |
  | Animal Type        | Species of animal (Dog, Cat, etc.)                                            |
  | Primary Color      | Main coat color                                                               |
  | Secondary Color    | Secondary coat color                                                          |
  | Sex                | Sex of the animal (Male, Female, Unknown)                                     |
  | DOB                | Date of birth (if known)                                                      |
  | Intake Date        | Date the animal entered the shelter                                           |
  | Intake Condition   | Health or physical condition at intake                                        |
  | Intake Type        | Primary source of intake (Stray, Owner Surrender, Confiscated, etc.)          |
  | Intake Subtype     | More detailed intake classification                                           |
  | Reason for Intake  | Explanation for why the animal was taken in                                   |
  | Outcome Date       | Date the animal exited the shelter                                            |
  | Crossing           | Intake or outcome crossing indicator (e.g., transferred across jurisdictions) |
  | Jurisdiction       | Governing area or authority                                                   |
  | Outcome Type       | Final outcome (Adoption, RTO, Transfer, Euthanasia, etc.)                     |
  | Outcome Subtype    | Detailed outcome classification                                               |
  | latitude           | Latitude coordinate of intake/outcome location                                |
  | longitude          | Longitude coordinate of intake/outcome location                               |
  | geopoint           | Combined latitude & longitude field                                           |
  | intake_is_dead     | Animal was deceased upon intake                                               |
  | intake_duration    | Days between intake and outcome                                               |
  | is_current_month   | Intake occurred in the current month                                          |
  | outcome_is_dead    | Outcome was non-live (euthanasia, died, disposal)                             |
  | outcome_is_current | Outcome occurred in the current month                                         |
  | outcome_is_other   | Outcome not classified as live or dead                                        |
  | outcome_is_alive   | Outcome was live (adoption, RTO, transfer)                                    |
  | was_outcome_alive  | Snapshot of live outcome status                                               |

  #### Data Source
  - downloaded from onyx data dataDNA [website](https://datadna.onyxdata.co.uk/challenges/november-2025-datadna-ecommerce-analytics-challenge).

</details>
 
### Refer
  - refer to my [post](https://www.linkedin.com/posts/batchaaan22_datafam-datadna-datavisualization-activity-7406541678737620992-pH-D?utm_source=share&utm_medium=member_desktop&rcm=ACoAADU37-4BvZkdxoNILB6GhzRJGT7OoLWMMoY) for my submission.
