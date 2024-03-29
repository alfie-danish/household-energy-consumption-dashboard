# ⚡️ Household Energy Consumption Dashboard

![Dashboard](https://github.com/alfie-danish/household-energy-consumption-dashboard/blob/main/images/energy-consumption-dashboard.png)

## 🔗 Project Links

- [Dashboard](https://docs.google.com/spreadsheets/d/1uOJTNK9xCz9ggfGibY_PYZQd-uMrx7ju8oLQWO0zcXE/edit?usp=sharing)
- [Python script](https://github.com/alfie-danish/household-energy-consumption-dashboard/blob/d3afc1eef78dbcef8393c02ea61461a34c068014/python_data_cleaning(energy_consumption).ipynb)

## 💡Introduction

In the year 2022, households across the globe saw energy prices skyrocketing through the roof. At the same time, we are seeing quickly depleting energy reserves in many nations. In an attempt to be more sustainable and conscious about energy spending. The following dashboard aims to track the energy consumption of a typical household. 

## ✅ Project Details

### Questions to Answer:

- Total gas and electricity cost this year to date
- Energy cost in comparison to previous year
- Total gas and electricity used this year to date
- Energy used in comparison to amount pre-ordered from service provider
- Yearly visual tracking of energy used per month

### Tech Stack:

- Google Sheets
- Python
- Deepnote

### **Methods:**

- By connecting Google Sheet + Python and using GSPREAD library, I can use Python for data wrangling
- By only inputting meter reading into Google Sheets on a monthly basis, I can utilise Panda’s **INTERPOLATE** method to forward fill missing values between each data entry day
- Dashboard will be produced in Google Sheets. Data prep within relies heavily on Google’s **QUERY** and **ARRAYFORMULA** functions
<table><tr><td valign="top" width="50%">
<img src="https://github.com/alfie-danish/household-energy-consumption-dashboard/blob/main/images/query1.png" align="center" style="width: 100%" />

</td><td valign="top" width="50%">

<div align="center">
<img src="https://github.com/alfie-danish/household-energy-consumption-dashboard/blob/main/images/query2.png" align="center" style="width: 100%" />
</div>  

</td></tr></table>  

### Data Source:

- Personal dataset

---

## ↔️ Related Projects

- Coming soon!

## ➡️ References

- [Pandas](https://pandas.pydata.org/)
- [GSpread](https://docs.gspread.org/en/v5.7.0/)

## 🤝 Get In Touch

Feedbacks are welcome!
