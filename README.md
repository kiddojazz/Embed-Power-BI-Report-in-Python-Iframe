# Embed-Power-BI-Report-in-Python-Iframe

Are you a Data Analyst that toggle between using Python and Power BI. If Yes, then I will show you a way to embed your Power BI report you published to the web inside on **Jupyter Notebook** using the **IFrame** library in Python.

**Note:** This process also works for embedding Power BI report into any website. What you just need are plugin like Embed and IFrame already installed.
You can check my previous video on how to go about it. [YouTube](https://www.youtube.com/watch?v=Z2kGkRutYLQ&t=128s)

## Step 1: Import all necessary Libraries
```
from IPython.display import IFrame
```

## Step 2: Write a variable that get the Report

For the process you will need to get the embeded link that have been published to Power BI web service.
- You will need to get the embeded code by selecting publish to web [Power BI Service](https://app.powerbi.com/).
- Copy the embeded code and paste in your jupyter notebook *src* source link.
- Run you code and see that happens.
```
Dashboard = IFrame(src="https://app.powerbi.com/view?r=eyJrIjoiYWJiODdhNWMtNWJjYy00YjIyLWEzYjEtNzVmMWQ4M2ZlNjYwIiwidCI6ImRhNDQ5YjJmLTczMjMtNDI4My1iZTFiLWQ5NTc4YTU2ODQ0YyJ9&pageName=ReportSection5afaa3dac70134a2a90c", width = 1000, height = 600)
display(Dashboard)
```

**Thanks for staying this long bye!!!**
