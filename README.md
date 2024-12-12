# data-analyst/solution-artchitect jadenguyen
# City of Vancouver Data Analytics Project

## Project Overview
This repository showcases the **City of Vancouver Data Analytics Platform** project. The initiative focuses on migrating City of Vancouver operations to AWS, specifically designing and implementing a **data analytics platform** to optimize operations related to **Operating Water Permits**.

## Objectives
- Develop a scalable data analytics platform to handle large datasets related to city operations.
- Enable descriptive analysis through tasks like **data ingestion**, **profiling**, and **cleaning**.
- Evaluate project performance using **Operational Excellence** and **Security** frameworks.

## Dataset
The project utilized anonymized and secure datasets representing:
- Water permit applications and approvals.
- Historical usage patterns and compliance metrics.

## Methodology
### Data Pipeline Development:
1. **Data Ingestion**:
   - Ingested structured and unstructured data into the analytics platform using AWS services.
   - Tools: AWS S3 for storage, AWS Glue for ETL.
2. **Data Profiling and Cleaning**:
   - Addressed missing values and inconsistent formats.
   - Tools: Python (Pandas, NumPy).
3. **Pipeline Design**:
   - Built scalable pipelines with clear workflows for real-time and batch data processing.
4. **Data Enriching**:
   - Enhanced datasets by integrating supplementary information for richer analytics.
   - Tools: AWS Lambda for real-time transformations.
5. **Data Protection**:
   - Applied encryption and access controls to ensure secure handling of sensitive data.
   - Tools: AWS KMS, IAM roles.
6. **Data Governance**:
   - Established policies for data stewardship and lifecycle management.
   - Tools: AWS Glue Data Catalog.
7. **Data Observability**:
   - Monitored data pipelines to detect and resolve anomalies proactively.
   - Tools: AWS CloudWatch, AWS X-Ray.

### Performance Evaluation:
#### **Operational Excellence**
- Automated workflows to enhance efficiency.
- Introduced monitoring systems for resource utilization and pipeline performance.

#### **Security**
- Applied AWS security best practices, including IAM roles and encryption.
- Ensured data privacy compliance through logging and access control.

#### **Reliability**
- Implemented backup and recovery mechanisms to minimize downtime.
- Used AWS Route 53 for fault-tolerant DNS services.

#### **Performance Efficiency**
- Optimized query times by leveraging AWS Redshift for analytical workloads.

#### **Cost Optimization**
- Utilized AWS Reserved Instances for predictable workloads.
- Monitored usage patterns to scale resources dynamically.

#### **Sustainability**
- Adopted serverless technologies to minimize carbon footprint.
- Optimized data storage tiers for efficient energy use.

## Tools and Technologies
- **Cloud Services**: AWS S3, AWS Glue, AWS Lambda, AWS KMS, AWS Redshift, AWS CloudWatch.
- **Programming**: Python (Pandas, NumPy, Matplotlib).
- **Visualization**: Draw.io for data flow diagrams.

## Deliverables
- **Pipeline Visualizations**: Comprehensive diagrams illustrating the architecture.
- **Descriptive Analytics Report**: Detailed analysis of ingested and cleaned datasets.
- **Performance Evaluation Report**: Insights on operational efficiency and security measures.

## Key Visualizations
Include links or embedded images for:
- Data pipeline architecture.
- Sample data profiling output.
- Operational metrics dashboards.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/city-of-vancouver-project.git
   ```
2. Navigate to the relevant sections for:
   - Scripts (`/scripts`): Contains Python code for ingestion and cleaning.
   - Documentation (`/docs`): Includes visualizations and reports.

## License
[MIT License](LICENSE)

## Contact
For questions or collaboration opportunities, please reach out at [your-email@example.com].
