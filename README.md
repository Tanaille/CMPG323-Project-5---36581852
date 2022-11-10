# CMPG323-Project-5---36581852
### Reporting and monitoring project for CMPG323

<p align="center">
    <img src="https://www.pei.com/wp-content/uploads/2016/08/maxresdefaultreduced.jpg">
</p>

### Summary
The goal of this project is to implement a dynamic and insightful reporting and monitoring system for the Connected Office application. It utilizes Microsoft Power BI to extract live data, filter the data and display it in a simple, user-friendly interface.

### Report Pages
The Power BI report is comprised of the following pages:
- High-Level Metrics - The main dashboard and overview page which provides a summarized overview of the most important aspects of the system. These include number of device status by zone, totals for devices, zones and categories, active/inactive devices and a summarized device registrtation decomposition tree which allows users to drill down and view device registration details by date, category and zone.

- Device Monitoring - This page provides real-time monitoring capabilities and displays the number of devices, their position within categories or zones as well as their overall status.

- Device Registration - Displays the number of device categories as well as time-series information regarding device registration and their position within different zones.

### Usage
#### Basic
The user may navigate throguh the various report pages by clicking on the desired page name. Each page contains several visualizations / tables displaying the relevant information. Users may highlight specific data values (such as devices, zones or categories) by clicking on the value within any visualization. Doing so will highlight and summarize information regarding that item across all visualizations in the page.

#### Filtering
Several predefined filters have been set up for users to help focus on relevant information. These filters are applied across all pages and may be cleared by CTRL+Clicking the clear filter button in the top right corner of the page.
<p>
<img src = "https://raw.githubusercontent.com/jongio/icons/master/clearfilter/clearfiltericon.png" width=60px height=60px>

##### Filter by Category
Filters all data according to the selected category.

##### Filter by Zone
Filters all data according to the selected zone.

##### Filter by Device Platform
Filters all data according to the selected device platform.

##### Filter by Device
Filters all data according to the selected device.

##### Filter by Regisration Date
Filters all data according to the device registration date.

##### Filter by Status
Filters all data according to device status.

##### Date Slicer
In addition to these filters, a date slicer has been provided in the top right corner of the screen to enable quick, ad-hoc date filtering.
