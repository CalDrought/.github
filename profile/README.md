# Visualizing Urban Water Data for Drought Management Across California

![Image of California Drought](https://bren.ucsb.edu/sites/default/files/2025-01/life-finds-a-way-photo-of-grass-pushing-through-d-2023-11-27-05-30-40-utc-2.jpg)

## Abstract
California is known for its susceptibility to drought, caused in part by a misallocation of water resources and an increase in demand. Critical drought related information is reported to multiple state agencies, separating important data and limiting access, leading to the underutilization and poor integration of data into water management. The California Water Data Consortium has created an open source portal containing previously separately stored data into one cohesive and clean format. This project assists the Consortium by creating a governance report, including gap analyses and staff training recommendations, to further clean and maintain the data. The project also created an online dashboard, making it easy for water managers with limited time or coding experience to analyze the data and identify critical missing values that could lead to misinterpretation. By improving data accessibility and usability, this project aims to strengthen California’s drought resilience through more informed and coordinated water management practices.

### [More information on the project can be found here](https://bren.ucsb.edu/projects/data-drought-resiliency)

### Data Source
The datasets used in this project originate from the [California Natural Resources Agency](https://data.cnra.ca.gov/dataset/urban-water-data-drought). These files provide historical and forecasted data related to water shortage conditions, as well as water production and delivery across various water agencies in the state. 

| Variable                         | Type         | Approximate Size | Description                                                                 |
|----------------------------------|--------------|------------------|-----------------------------------------------------------------------------|
| Actual Water Shortage Level      | `.csv`       | 823 KB           | Monthly water shortage levels for water agencies                            |
| Five Year Water Shortage Outlook | `.csv`       | 204 KB           | Projected water use and supply of water agencies based on 5 worst drought years |
| Historical Production and Delivery | `.csv`     | 89 MB            | Water production/delivery by water type for water agencies                  |
| Monthly Water Shortage Outlook   | `.csv`       | 1 MB             | Projected monthly water shortage or surplus for water agencies              |


This is a capstone project for the [Master of Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at [Bren School of Environmental Science and Management](https://bren.ucsb.edu/), University of California, Santa Barbara

## Repositories in our project:

[Gap Analysis](https://github.com/CalDrought/gap_analysis)

Houses our gap analysis for urban drought data that is currently housed in the [CNRA portal](https://data.cnra.ca.gov/dataset/urban-water-data-drought). Detailed descriptions of the original data can be found in the Urban Water Drought Data ReadMe. This repository includes an analysis of current data gaps, desired data, user usability, and training recommendations for staff.

[Dashboard](https://github.com/CalDrought/dashboard)

Houses the code for the dashboard section of the capstone project. This dashboard includes maps of California, graphs of water/ drought data, summary statistics, and an overview of missing values in the data. The intention of this dashboard is to display the data in easily visualized and interpretable way. 

[Urban-Water-Drought-Data](https://github.com/CalDrought/urban-water-drought-data) 

Is a forked repository of the [FlowWest github repository](https://github.com/FlowWest/urban-water-drought-data/tree/7fa75d25fe327423f715dc0d55ff258a11d8c6e4), which contains the data and metadata associated with this project. 

## Contributors:
Tom Gibbens-Matsuyama { [GitHub](https://github.com/tommats00) | [Website](https://tommats00.github.io/) | [LinkedIn](https://www.linkedin.com/in/tom-gibbens-matsuyama-861458248?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BM8h7JpVaT6WvTKH4YaIIlg%3D%3D) }

Emma Bea Mitchell { [GitHub](https://github.com/emmabeamitchell) | [Website](https://emmabeamitchell.github.io/) | [LinkedIn](www.linkedin.com/in/emma-bea-mitchell) }

Karol Paya { [GitHub](https://github.com/kpaya) | [LinkedIn](https://www.linkedin.com/in/karolpaya/) }

Takeen Shamloo { [GitHub](https://github.com/takeenshamloo) | [Website](https://takeenshamloo.github.io/) | [LinkedIn](https://www.linkedin.com/in/takeen-shamloo-aa2685162/) }

#### Client:
[California Water Data Consortium](https://cawaterdata.org/)

#### Advisor
[Dr. Naomi Tague](https://bren.ucsb.edu/people/christina-tague)

#### Instructor 
[Carmen Galaz García](https://bren.ucsb.edu/people/carmen-galaz-garcia-0)


Copyright CC0-1.0 2025
