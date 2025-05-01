# HR-Insights-Dashboard: Interactive Workforce Analytics Platform

![HR Dashboard Preview](./Dashboard%201.png)

## Project Overview
This comprehensive HR Analytics Dashboard provides powerful insights into workforce data through interactive visualizations built in Tableau. The project delivers both high-level organizational insights and granular employee data analysis, enabling data-driven HR decision-making.

## Key Features

### Summary View
The dashboard offers three main analytical sections:

#### 📊 Organizational Overview
- Employee headcount metrics (hired, active, terminated) 
- Historical hiring and termination trends
- Departmental and job title distribution
- Geographical analysis (HQ vs branches, city/state distribution)

#### 👥 Demographic Analysis
- Gender distribution and diversity metrics
- Age group segmentation
- Educational background analysis
- Performance rating correlation with education level

#### 💰 Compensation Intelligence
- Salary distribution across educational backgrounds
- Gender-based compensation analysis 
- Age-to-salary correlation by department
- Compensation trends and outliers

### Employee Records View
- Comprehensive employee directory with filterable fields
- Individual employee performance and compensation data
- Custom sorting and filtering capabilities
- Exportable reports for offline analysis

## Technical Implementation

### Technologies Used
- Tableau Desktop 2023.1
- Python with Faker library for data generation
- Photopea for icon customization
- Draw.io for mockup creation
- Procreate for initial design concepts
- Figma for dashboard background design

### Development Methodology
1. Requirements gathering through user story development
2. Mock data generation using Python and GPT
3. Initial mockup creation and design iteration
4. Dashboard development in Tableau with custom visualizations
5. Interactive filter implementation and dashboard actions
6. UI refinement and performance optimization

## Project Structure
```
HR-Insights-Dashboard/
├── data/
│   └── hr_employee_data.csv
├── design/
│   ├── mockups/
│   │   ├── initial_sketch.procreate
│   │   └── dashboard_wireframes.drawio
│   └── icons/
│       ├── icon_sources.txt
│       └── psd_files/
├── tableau/
│   └── HR_Analytics_Dashboard.twbx
└── documentation/
    ├── data_dictionary.md
    └── user_guide.md
```

## Installation and Usage
1. Clone this repository
2. Download [Tableau Public](https://public.tableau.com/en-us/s/download) or use Tableau Desktop
3. Open the `HR_Analytics_Dashboard.twbx` file located in the tableau folder
4. Explore the dashboard using the interactive filters and visualization options

## Data Source
The dataset simulates realistic HR information generated using Python's Faker library and ChatGPT prompts. It includes employee demographics, job details, compensation data, performance metrics, and attrition information—all designed to mimic real-world HR scenarios.

## Future Enhancements
- Predictive analytics for employee attrition risk
- Advanced compensation analysis tools
- Performance trajectory visualizations
- Integration with real-time HR data systems
- Mobile-responsive dashboard design

## Acknowledgments
- Icons sourced from Flaticon and customized to match dashboard aesthetics
- Dashboard background designed in Figma
- Initial mockup created using Procreate

## License
This project is available for educational and personal use. When sharing publicly, please provide attribution to the original creator.

---

*This project demonstrates proficiency in data visualization, HR analytics, and dashboard design using industry-standard tools and methodologies.*
