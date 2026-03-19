# Splunk Query Used

index=wineventlog EventCode=4624
| table _time Account_Name Logon_Type Source_Network_Address

## Purpose
This query detects successful login events and shows key investigation fields.