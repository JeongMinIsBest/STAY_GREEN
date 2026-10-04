# 🛏️ 2024 MCST Data Utilization Competition
- **Theme**: Analysis and utilization of cultural, sports, and tourism issues and policy effects through data analysis  
- **Organizer**: Korea Culture & Tourism Institute (KCTI)  
- **Sponsor**: Shinhan Card  
<br/>

## ✏️ Project Overview
- **Planning & Analysis**: Jaewoo Seo, Jeongmin Lim  
- **Project Period**: November 18, 2024 – November 25, 2024  
- **Project Title**: **Green Score–Based Hotel Selection and Attraction Strategy to Address Regional Polarization in Green Stay Tourism**
<br/>

## 🧩 Data Collection
- **Carbon Emissions Data**
  - National Carbon Emissions/Absorption Statistics  
  - Source: Ministry of Land, Infrastructure and Transport – Carbon Spatial Map System  
  - Used as an indicator representing the environmental burden of each region.

- **Hotel Activity Data**
  - Source: Korea National Travel Survey (Ministry of Culture, Sports and Tourism)
  - Variables used:
    - Intention to revisit for domestic overnight travel by destination
    - Average expenditure per person for domestic overnight travel by destination
    - Number of domestic overnight trips by destination
    - Average number of overnight stays per person by destination
    - Annual total hotel revenue
  - These variables represent regional accommodation demand and tourism consumption levels.
<br/>

## 🗂️ Data Preprocessing and Final Dataset
Each dataset was organized at the **province-level (si/do)** and unnecessary variables were removed.  
The datasets were then merged using the **region name (si/do)** as the key to construct the final dataset.
<br/>
