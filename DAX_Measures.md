-- Average Billing
AvgBilling = AVERAGE('Healthcare'[Billing Amount])

-- Total Billing
TotalBilling = SUM('Healthcare'[Billing Amount])

-- Patient Key to handle duplicates
PatientKey = 'Healthcare'[Name] & "-" & 'Healthcare'[Age] & "-" & 'Healthcare'[Gender]

-- Length of Stay
LengthOfStay = DATEDIFF('Healthcare'[Date of Admission], 'Healthcare'[Discharge Date], DAY)
