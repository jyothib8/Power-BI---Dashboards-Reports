# Power BI Dashboards & Reports

## USA Vaccination Report

This repository contains Power BI dashboards and reports focused on USA vaccination data analytics.

### Project Overview

The USA Vaccination Report provides comprehensive insights into vaccination trends, coverage rates, and distribution patterns across the United States.

### Dashboard Components

#### 1. **Vaccination Coverage Dashboard**
   - State-by-state vaccination rates
   - Population coverage metrics
   - Trend analysis over time
   - Demographic breakdowns

#### 2. **Vaccine Distribution Analysis**
   - Geographic heat maps
   - Vaccine type distribution
   - Dosage tracking (1st dose, 2nd dose, Boosters)
   - Supply chain efficiency

#### 3. **Demographic Insights**
   - Age group analysis
   - Ethnic and racial demographics
   - Vulnerable population tracking
   - Equity metrics

#### 4. **Comparative Analysis**
   - State-to-state comparisons
   - National vs. state performance
   - Regional clustering
   - Trend comparison

### Data Sources

- USA CDC Vaccination Data
- State Health Department Reports
- Census Data (for population denominators)
- Demographic Information

### Key Metrics & KPIs

- **Total Vaccinations**: Count of all administered doses
- **Vaccination Rate**: Percentage of population vaccinated
- **Fully Vaccinated**: Percentage with complete vaccination series
- **Booster Coverage**: Percentage with booster doses
- **Equity Index**: Measure of equitable distribution

### How to Use

1. Connect Power BI to the data source files in the `/data` directory
2. Use the relationships defined in the data model
3. Customize reports based on the templates provided
4. Refresh data regularly for up-to-date insights

### File Structure

```
├── README.md
├── data/
│   ├── vaccination_data.csv
│   ├── state_demographics.csv
│   └── vaccine_distribution.csv
├── dashboards/
│   ├── Vaccination_Coverage_Dashboard.pbix
│   ├── Distribution_Analysis.pbix
│   ├── Demographic_Insights.pbix
│   └── Comparative_Analysis.pbix
├── documentation/
│   ├── DATA_DICTIONARY.md
│   ├── DASHBOARD_GUIDE.md
│   └── METRICS_DEFINITION.md
└── templates/
    └── power_bi_template.pbit
```

### Getting Started

1. Clone or download this repository
2. Review the data dictionary in `/documentation`
3. Import data files into Power BI
4. Open the dashboard templates
5. Refresh data connections
6. Customize visuals as needed

### Updates & Maintenance

- Data updated weekly
- Dashboard refreshed on Mondays
- Quarterly review of metrics and KPIs

### Contributing

To contribute improvements:
1. Create a new branch
2. Make your changes
3. Submit a pull request
4. Include documentation of changes

### Contact

For questions or support regarding these dashboards, please create an issue in this repository.

---
**Last Updated**: June 2, 2026
**Version**: 1.0
