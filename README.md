# Insurance Data Analysis - Power BI Dashboard

## 📊 Project Overview

This Power BI project provides comprehensive analysis and visualization of insurance policy and claims data. The dashboard offers insights into policy distribution, claim statuses, premium trends, and customer demographics across multiple insurance types.

## 📁 Project Files

- **Insurance_Data_Analysis.pbix** - Power BI dashboard file
- **InsuranceData.csv** - Source dataset containing policy and claims information
- 
## 📈 Dataset Description

The dataset contains **10,000+ records** of insurance policies and claims with the following key attributes:

### Data Fields

| Field Name | Description | Data Type |
|------------|-------------|-----------|
| PolicyNumber | Unique policy identifier | Text |
| CustomerID | Unique customer identifier | Text |
| Gender | Customer gender (Male/Female) | Text |
| Age | Customer age | Numeric |
| PolicyType | Type of insurance (Auto, Travel, Health, Home, Life) | Text |
| PolicyStartDate | Policy inception date | Date |
| PolicyEndDate | Policy expiration date | Date |
| PremiumAmount | Premium paid for the policy | Currency |
| CoverageAmount | Total coverage amount | Currency |
| ClaimNumber | Unique claim identifier | Text |
| ClaimDate | Date when claim was filed | Date |
| ClaimAmount | Amount claimed | Currency |
| ClaimStatus | Status of claim (Settled, Pending, Rejected) | Text |

### Data Characteristics

- **Time Period**: August 2023 - June 2024
- **Total Records**: 10,006 policies
- **Insurance Types**: 5 categories (Auto, Travel, Health, Home, Life)
- **Claim Statuses**: 3 categories (Settled, Pending, Rejected)
- **Age Range**: 23-85 years
- **Gender Distribution**: Male and Female

## 🎯 Dashboard Features

Based on the data structure, the dashboard includes:

### Key Metrics
- Total number of policies
- Total premium amount collected
- Total coverage amount
- Total claims filed and settled
- Claim settlement ratio

### Visualizations
- **Policy Distribution** by type (Auto, Travel, Health, Home, Life)
- **Claim Status Analysis** (Settled vs Pending vs Rejected)
- **Age Group Analysis** for customer segmentation
- **Gender-based Analytics**
- **Premium and Coverage Trends** over time
- **Claim Amount Analysis** by policy type
- **Active vs Inactive Policies** tracking

### Interactive Filters
- Date range selection (PolicyStartDate, PolicyEndDate, ClaimDate)
- Policy type filter
- Gender filter
- Age group segmentation
- Claim status filter

## 🔧 Technical Setup

### Prerequisites
- **Microsoft Power BI Desktop** (Latest version recommended)
- Minimum 4GB RAM
- Windows 10 or later / macOS with Power BI Desktop installed

### Installation Steps

1. **Clone or Download** this repository
2. **Open Power BI Desktop**
3. **Open the file**: `Insurance_Data_Analysis.pbix`
4. If prompted, update the data source path to point to `InsuranceData.csv`

### Data Refresh

To refresh the data:
1. Click **Home** > **Refresh** in Power BI Desktop
2. Ensure the CSV file path is correctly configured
3. For automatic refresh in Power BI Service, configure scheduled refresh settings

## 📊 Key Insights

The dashboard helps answer questions such as:

- Which insurance type generates the most premium revenue?
- What is the claim settlement rate across different policy types?
- How does age and gender influence policy selection?
- What are the peak periods for policy purchases and claims?
- Which policy types have the highest claim rejection rates?
- What is the average claim amount by policy type?
- How do coverage amounts correlate with premium amounts?

## 🎨 Dashboard Design

The dashboard follows best practices:
- **Clean and intuitive layout**
- **Consistent color scheme** for different insurance types
- **Interactive cross-filtering** between visuals
- **Clear KPI indicators** for quick insights
- **Responsive design** for different screen sizes

## 📝 Data Model

The data model includes:
- **Date tables** for time intelligence calculations
- **Calculated columns** for age groups and derived metrics
- **Measures** for KPIs like claim settlement rate, average premium, etc.
- **Relationships** properly configured for accurate filtering

## 🔍 Calculated Measures (Examples)

## 🚀 Usage Guidelines

### For Business Users
- Use slicers to filter data by date range, policy type, or customer demographics
- Hover over charts for detailed tooltips
- Click on visual elements to cross-filter other visuals
- Export specific visuals or reports as needed

### For Analysts
- Drill down into specific segments for detailed analysis
- Use the underlying data to create additional custom calculations
- Modify visuals to explore different perspectives
- Export data to Excel for further analysis

**Note**: This dashboard is for internal business analysis purposes. Ensure data security and privacy compliance when sharing or publishing.
