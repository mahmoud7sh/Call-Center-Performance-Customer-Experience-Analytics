# Call Center Performance & Customer Experience Analytics

An interactive Power BI project analyzing **32,941 call records** to understand call center operations, service efficiency, and customer experience across communication channels and locations.

## Project Overview

This project explores customer interactions across multiple call centers and communication channels. The dashboard brings together operational KPIs and customer-experience indicators to help users monitor call volume, call duration, response performance, SLA status, and customer sentiment.

The report is organized into two pages:

- **Executive Overview** – a high-level view of call volume, duration, channels, call-center locations, sentiment, and call reasons.
- **Performance Details** – a closer look at October call trends, geographic distribution, negative and positive calls, and SLA performance.

## Key Metrics

| KPI | Result |
|---|---:|
| Total Calls | 32,941 |
| Total Call Duration | 13.74K hours |
| Total Call Duration | 824.2K minutes |
| Average Call Duration | 25.02 minutes |
| Response Time | 75.3% |
| Negative Calls | 17K |
| Negative Sentiment Rate | 51.9% |
| Within SLA Rate | 62.6% |
| Above SLA Rate | 12.7% |

## Dashboard Pages

### 1. Executive Overview

The overview page provides a snapshot of overall call center activity, including:

- Total calls and call-duration KPIs
- Weekly distribution of call volume
- Calls by state
- Calls by communication channel
- Calls by call-center location
- Customer sentiment distribution
- Calls by reason

### 2. Performance Details

The details page focuses on service performance and customer experience:

- October call-volume trends
- Top five cities by call volume
- Negative and positive calls during October
- Negative-call volume and negative sentiment rate
- Within-SLA and above-SLA performance

## Dashboard Preview

The dashboard report contains two pages. Open the PDF already included in this repository to view each page:

- [Executive Overview – Page 1](./Call%20Center%20Project%20_%20Dashboard.pdf#page=1)
- [Performance Details – Page 2](./Call%20Center%20Project%20_%20Dashboard.pdf#page=2)

## Data & Model

The analysis uses **32,941 call records** and a dataset containing 12 main call-related columns:

- `Id`
- `Call Timestamp`
- `Call-Centres City`
- `Channel`
- `City`
- `Customer Name`
- `Reason`
- `Response Time`
- `Sentiment`
- `State`
- `Call Duration In Minutes`
- `Csat Score`

The Power BI model uses a main calls table together with a separate Date/Time table to support time-based analysis.

## Tools & Technologies

- **Power BI** – data modeling, DAX measures, and interactive report development
- **Power Query** – data cleaning and transformation
- **DAX** – KPI calculations and analytical measures
- **Microsoft Excel** – data inspection and validation

## Project Workflow

1. Inspected and validated the source data in Excel.
2. Cleaned and transformed the data using Power Query.
3. Prepared the data model using the calls table and Date/Time table.
4. Created analytical measures and KPIs using DAX.
5. Designed a two-page interactive Power BI report.
6. Analyzed operational performance, customer sentiment, channels, and geographic patterns.

## Key Observations

- The dataset contains **32,941 calls** across multiple channels and locations.
- The negative sentiment rate is **51.9%**, representing approximately 17K calls.
- The reported within-SLA rate is **62.6%**, while the above-SLA rate is **12.7%**.
- The Call Center channel records the largest channel volume at approximately **10.6K calls**.
- Los Angeles has the highest call-center location volume at approximately **13.7K calls**.

## Project Objective

The objective is to turn raw call records into actionable operational visibility by combining call-volume analysis with customer sentiment and service-performance indicators in one interactive reporting solution.

---

*This project was developed as a data analytics portfolio project using Power BI and Microsoft data tools.*
