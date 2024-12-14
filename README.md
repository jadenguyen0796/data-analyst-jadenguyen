# Data Analyst/Solutions Artchitect - #jadenguyen
# City of Vancouver Data Analytics - Operating Water Permits Project

## Project Overview
This repository documents the **City of Vancouver Data Analytics Platform (DAP)** project. The initiative aimed to migrate City of Vancouver operations to AWS by designing and implementing a scalable, secure, and efficient data analytics platform tailored to support operational needs, specifically related to **Operating Water Permits**.

---

## Part 1: Data Analytics Platform Development

### Objectives
- Build a robust data analytics platform (DAP) to manage and analyze city data effectively.
- Implement scalable pipelines for **data ingestion**, **profiling**, **cleaning**, and **processing**.
- Adhere to AWS Well-Architected Framework principles, focusing on Operational Excellence and Security.

### Dataset
The project used anonymized datasets comprising:
- Water permit applications and approvals.
- Historical data on compliance and usage patterns.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/71919627-7e36-48cd-84f3-a6441eeb5318" />


### Steps and Methodology
#### Step 1: Data Ingestion
- Integrated structured and unstructured data into AWS S3.
- Used **AWS Glue** for ETL processes, enabling scalable and automated data ingestion workflows.


#### Step 2: Data Profiling and Cleaning
- Identified and resolved issues such as missing values and inconsistent data formats.
- Tools: Python libraries (**Pandas**, **NumPy**) for exploratory and cleaning tasks.


#### Step 3: Pipeline Design
- Designed end-to-end pipelines for real-time and batch data processing.
- Leveraged **AWS Lambda** for event-driven workflows.


### Deliverables for Part 1
- **Data Pipeline Diagrams**: Detailed flowcharts created using Draw.io to visualize pipeline architecture.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/76698ba0-29d9-4242-a57b-5a3edc5687d9" />

- **Descriptive Analytics Report**: Summary of dataset transformations and quality improvements.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/f70c32a1-35b9-429e-94c7-d945a9428202" />

<img width="468" alt="image" src="https://github.com/user-attachments/assets/71d40e3f-7ac0-47aa-b661-f7f4b76b8f11" />
---

## Part 2: Data Enrichment and Architecture Analysis

### Objectives
Expand and evaluate the DAP by incorporating advanced features like **data enriching**, **governance**, and **observability** while aligning with additional AWS Well-Architected pillars.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/965f8d1c-9bd8-4d49-b17a-6ad36f5c6f89" />

### Steps and Methodology
#### Step 4: Data Enriching
- Enhanced datasets by integrating external data sources through VPC and instances to improve analytics depth.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/ff0362a9-791f-4c2c-a8aa-625d28e98580" />

<img width="468" alt="image" src="https://github.com/user-attachments/assets/83e8fba5-8d9a-4bea-92c8-7f0af4842447" />

- Implemented real-time data transformation using **AWS Lambda**.

#### Step 5: Data Protection
- Enforced robust encryption standards using **AWS KMS**.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/5383116b-a93d-4b5b-9847-684fbc3d20c3" />

- Configured IAM roles to control access and secure sensitive datasets.

#### Step 6: Data Governance
- Established data stewardship policies to ensure compliance with city regulations.
- Built a data catalog using **AWS Glue Data Catalog** for metadata management.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/80bf676b-0f66-4c85-8559-4837dd22f599" />


#### Step 7: Data Observability
- Monitored pipelines to detect anomalies and bottlenecks proactively.
- Used **AWS CloudWatch** and **AWS X-Ray** for logging and tracing.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/a2bebff9-e2a6-47ad-a62f-70331bdc49f0" />


### AWS Well-Architected Pillars Addressed
#### Operational Excellence
- Automated operational workflows to improve consistency and reduce manual intervention.
- Established metrics and alerts for system health.

#### Security
- Implemented fine-grained IAM policies and end-to-end encryption.
- Ensured auditability through comprehensive logging.

#### Reliability
- Designed fault-tolerant pipelines with backup and recovery mechanisms.
- Used **AWS Route 53** for failover and DNS services.

#### Performance Efficiency
- Optimized data query speeds using **AWS Redshift** for analytical workloads.

#### Cost Optimization
- Right-sized resources using AWS Cost Explorer and implemented Reserved Instances.

#### Sustainability
- Adopted serverless architectures to minimize energy usage and environmental impact.

### Deliverables for Part 2
- **Data Enrichment Scripts**: Python code for real-time transformations.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/4611c1c0-20ea-433d-9a22-e5ca618429ae" />

- **Governance Framework Documentation**: Comprehensive data policies.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/6b456f5e-c051-47ef-a7d9-c58e131a4538" />


- **Performance Metrics Dashboards**: Visualizations for key operational metrics.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/b95122b6-024b-4061-aaf4-b6686f206632" />

---

## Tools and Technologies
- **Cloud Services**: AWS S3, AWS Glue, AWS Lambda, AWS KMS, AWS Redshift, AWS CloudWatch, AWS X-Ray.
- **Programming**: Python (Pandas, NumPy, Matplotlib).
- **Visualization**: Draw.io for data flow and architecture diagrams.

---

## Contact
For questions or collaboration opportunities, please contact [jade.nguyen0796@gmail.com]
