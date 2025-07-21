# DA4U | Powerbi Emergency Admissions Report
This Power BI report was built to explore and visualize emergency hospital admissions using a sample dataset. It’s a quick but structured report that shows how limited, realistic data can still reveal meaningful trends about patient flow, departmental workload, and admission timelines.

# Dataset Overview

The dataset includes the following fields:

    Visit Date
    Time before Admission
    Department
    Admission Status (Admitted or Not Admitted)
    Gender

While simplified and anonymized, this data mimics a real emergency intake scenario.

Download Hospital Emergency data sample [here](https://github.com/datavitalyzer/DA4U-Powerbi-Emergency-Admissions-Report/blob/main/Hospital%20ER.csv)

# Report Structure

The report is divided into two key sections, both using filters for calendar date and admitting department to allow dynamic exploration.

Page 1: Patient Overview

![Image](https://github.com/user-attachments/assets/7192be8d-2fbd-48b4-899c-88c6785f7660)


This section provides a high-level view of all patients arriving at the emergency department. It includes:

    Total patient count
    List of patients details
    Patient distribution by day and time
    Filters to explore trends by date and department

This gives a sense of patient volume and how demand fluctuates over time.

Page 2: Admission & Ventilation Focus

![Image](https://github.com/user-attachments/assets/773fc652-efae-48e1-992d-7aaf6d5240b4)

This section narrows the focus to more clinical insights, particularly around admission timelines and ventilation needs. It includes:

    Patient counts broken down by gender and admission status
    Visualization of patients seen within or over 30 minutes before the final admission decision
    Breakdown of ventilated patients by department, filtered by admission status
    and other analytics your can discover in the report

This section aims to give insight into patient urgency, delays before admission, and where critical care resources like ventilation are being used.

You can browse the report online [Here](https://app.fabric.microsoft.com/view?r=eyJrIjoiYTMwYzNmMmQtYTYwZC00YWI2LWIzZDItMzIyNzhmZTE5Y2MyIiwidCI6ImYzM2EwNzZmLWRkYmYtNDYyOC1hNzg2LWQ1NTRhNzAxYzg0NSIsImMiOjh9)
