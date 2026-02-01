# DHS Family Planning Analysis (Python)

This repository presents a data analysis project examining modern contraceptive use among married or in-union women aged 15–49 using Demographic and Health Survey (DHS) data.

The project follows standard DHS, WHO, and NGO/INGO reporting practices and is intended as a portfolio example for roles in data analysis, monitoring and evaluation (M&E), and public health research.
## Data Source

The data were obtained from the Demographic and Health Surveys (DHS) Program after submitting a formal data request.

Due to DHS data use restrictions, raw data files are not included in this repository. All variable definitions and interpretations were based on the DHS Recode Manual and dataset documentation provided by the DHS Program.
## Methodology

- Imported DHS Individual Recode (IR) data in Stata (.DTA) format using Python  
- Selected and transformed policy-relevant variables for family planning analysis  
- Constructed a modern contraceptive use indicator following DHS and WHO definitions  
- Restricted analysis to married or in-union women aged 15–49  
- Applied DHS sampling weights to produce nationally representative estimates  
- Analyzed modern contraceptive use by residence, education, and age group  
- Created clear, policy-ready visualizations using matplotlib  
## Key Outputs
- Reproducible Jupyter Notebook with full analysis workflow  
- Clean bar charts suitable for reports and presentations  
- Written project summary explaining data source, methods, and findings  

## Repository Structure
DHS-Family-Planning-Analysis-Python/
│
├── notebook/
│ └── dhs_fp_analysis.ipynb
│
├── outputs/
│ ├── mcp_by_residence.png
│ ├── mcp_by_education.png
│ └── mcp_by_age.png
│
├── docs/
│ └── DHS_Modern_Contraceptive_Analysis_Project.docx
│
├── README.md
└── requirements.txt
## Tools Used

- Python  
- pandas  
- numpy  
- matplotlib  
- Jupyter Notebook  
## Ethical Use of Data

This project complies with DHS data usage guidelines. The data were used solely for analytical and educational purposes, and no attempt was made to identify individual respondents.

## Author
** Riyam Kafle **
Aspiring Data Analyst / M&E Officer with experience analyzing DHS survey data for NGO and INGO-focused research.


