# CMPG323-Project-5---36581852
### Reporting and monitoring project for CMPG323

<p align="center">
    <img src="https://www.pei.com/wp-content/uploads/2016/08/maxresdefaultreduced.jpg">
</p>

### Summary
The goal of this project is to implement a dynamic and insightful reporting and monitoring system for the Connected Office application. It utilizes Microsoft Power BI to extract live data, filter the data and display it in a simple, user-friendly interface.

### Report Pages
The Power BI report is comprised of the following pages:

<p align="left">
<img src="https://github.com/Tanaille/CMPG323-Project-5---36581852/blob/main/Screenshots/Pages.PNG">
</p>

- High-Level Metrics - The main dashboard and overview page which provides a summarized overview of the most important aspects of the system. These include number of device status by zone, totals for devices, zones and categories, active/inactive devices and a summarized device registrtation decomposition tree which allows users to drill down and view device registration details by date, category and zone.

- Device Monitoring - This page provides real-time monitoring capabilities and displays the number of devices, their position within categories or zones as well as their overall status.

- Device Registration - Displays the number of device categories as well as time-series information regarding device registration and their position within different zones.

### Usage
#### Basic
<img src="https://github.com/Tanaille/CMPG323-Project-5---36581852/blob/main/Screenshots/High-Level%20Metrics.PNG">
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

<img src = "https://github.com/Tanaille/CMPG323-Project-5---36581852/blob/main/Screenshots/Filters.PNG" width="20%" height="20%">

##### Date Slicer
In addition to these filters, a date slicer has been provided in the top right corner of the screen to enable quick, ad-hoc date filtering.

<img src="https://github.com/Tanaille/CMPG323-Project-5---36581852/blob/main/Screenshots/Date%20Slicer.PNG">

### Reference List
1. https://powerbi.microsoft.com/cs-cz/blog/combining-excel-files-hosted-on-a-sharepoint-folder/
2. https://powerbi.tips/2016/09/loading-excel-files-from-sharepoint/
3. https://support.microsoft.com/en-us/office/keep-or-remove-duplicate-rows-power-query-d9cffc69-dc5d-4d94-8b66-72779688874d
4. https://dash-intel.com/powerbi/modeling_measure+calculated+columns.php
5. https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-tutorial-create-calculated-columns
6. https://forum.enterprisedna.co/t/need-the-count-of-category/19408/2
7. https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-create-and-manage-relationships
8. https://community.powerbi.com/t5/Desktop/Rename-column-headers-in-a-table/m-p/43801
9. https://community.powerbi.com/t5/Desktop/Change-card-label/m-p/1669
10. https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-kpi?tabs=powerbi-desktop
11. https://community.powerbi.com/t5/Desktop/using-Multi-row-Card/m-p/751827
12. https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-add-custom-column
13. https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-add-column-from-example
14. https://community.powerbi.com/t5/Desktop/Need-a-formula-for-count-not-equal-to-a-value/m-p/454007
15. https://www.enjoysharepoint.com/power-bi-measure-countif/
16. https://hevodata.com/learn/dax-count/
17. https://www.instructorbrandon.com/power-bi-data-visualization-best-practices-part-6-of-15-multi-row-cards/
18. https://www.projectpro.io/recipes/what-is-multi-row-card-power-bi
19. https://www.spguides.com/power-bi-filter-between-two-dates/
20. https://tanducits.com/tips-and-tricks/power-bi-slicer-between-two-dates
21. https://community.powerbi.com/t5/Desktop/Use-a-date-slicer-to-filter-on-a-period-instead-of-a-single-date/m-p/588265#M278953
22. https://learn.microsoft.com/en-us/power-bi/visuals/desktop-slicer-filter-date-range
23. https://blog.jongallant.com/2020/05/powerbi-clear-all-filters/
24. https://radacad.com/power-bi-visualization-tip-hide-or-lock-the-filter-for-users
25. https://learn.microsoft.com/en-us/dax/related-function-dax
26. https://dax.guide/related/
27. https://www.sqlbi.com/articles/using-related-and-relatedtable-in-dax/
28. https://github.com/jongio/icons/blob/master/clearfilter/clearfiltericon.png
