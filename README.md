# Sin App

The application purpose is to create reports by Incident Managers. At the end of each month, IM has to create a report regarding the amount of outage communication sent by each Service Desk. The application can significantly reduce the time of creating this report.

Creating a rapot consists in copying to Excel individual information from e-mail (SIN - Service Impact Notification) received by the Service Desk agent, which is generated by the platform. This is a very tedious task, as only some information are relevant and have to be extracted individually to the appropriate column in the report. In addition, the date format in the report is different from the email format, which should also be manually changed. In addition, it is necessary to calculate the time difference between the initial communication and  the date of its resolution.

The application allows you to copy the entire email and automatically extract the necessary information. Date format is automatically changed to required format and difference between dates is calculated as well. The generated row can be copied to Excel.

The application has been used by a company for half a year and significantly improves the process of generating report.
<br/><br/>

[![Alt text](https://img.youtube.com/vi/Wyco8N_zha8/0.jpg)](https://www.youtube.com/watch?v=Wyco8N_zha8)

## Example content of emails:

**CEST**<br/>
Unreported / Resolved: Service Impact Notification – Thursday, 16-Jun 2019<br/>
Resolved:&nbsp; Site disconnected from 00:24:51 CEST to 01:25:43 CEST<br/>
Regions Affected:&nbsp;  EMEA<br/>
Services Impacted:&nbsp;  Related services<br/>
Sites Impacted:&nbsp;  Eng<br/>
Brief Description:&nbsp;  Both routers on site appeared to be offline at same moment.<br/>
SIN Reported:&nbsp;  16-Jun-2019 01:04 CEST<br/>
Problem Team/Owner:&nbsp;  TeleCOM<br/>
Infra Ticket Number:&nbsp;  7416781 <br/>
Issue Discovered:&nbsp;  16-Jun-2019 00:04 CEST <br/>
Issue Resolved:&nbsp;  16-Jun-2019 02:20 CEST <br/>
Root Cause:&nbsp;  Power Outage<br/>

**EDT**<br/>
Resolved: Service Impact Notification – Sunday, 29-Jun-2019<br/>
Resolved:&nbsp; Maintenance work activity has been completed.<br/>
Regions Affected:&nbsp;  Global<br/>
Services Impacted:&nbsp;  Network Connectivity<br/>
Sites Impacted:&nbsp;  All sites connected to Eng<br/>
Brief Description:&nbsp;  Maintenance work will need to be extended beyond the monthly window.<br/>
SIN Reported:&nbsp;  29-Jun-2019 10:02 EDT<br/>
Problem Team/Owner:&nbsp;  LAN-WAN-Eng<br/>
Infra Ticket Number:&nbsp;  7220677 <br/>
Issue Discovered:&nbsp;  29-Jun-2019 10:01 EDT <br/>
Issue Resolved:&nbsp;  29-Jun-2019 10:59 EDT <br/>
Root Cause:&nbsp;  Maintenance work activity has been completed.

