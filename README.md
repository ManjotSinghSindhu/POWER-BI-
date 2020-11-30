# POWER-BI-

**Power BI** is a Data Visualization and Business Intelligence tool that converts data from different data sources to interactive dashboards and BI reports. Power BI suite provides multiple software, connector, and services - Power BI desktop, Power BI service based on Saas, and mobile Power BI apps available for different platforms. These set of services are used by business users to consume data and build BI reports.

Power BI desktop app is used to create reports, while Power BI Services (Software as a Service - SaaS) is used to publish the reports, and Power BI mobile app is used to view the reports and dashboards.

Power BI Desktop is available in both 32-bit and 64-bit versions. To download the latest version, you can use the following link:

https://powerbi.microsoft.com/en-us/downloads/

**The parts of Power BI**

Power BI consists of several elements that all work together, starting with these three basics:

1. A Windows desktop application called Power BI Desktop.
2. An online SaaS (Software as a Service) service called the Power BI service.
3. Power BI mobile apps for Windows, iOS, and Android devices.

These three elements—Power BI Desktop, the service, and the mobile apps—are designed to let you create, share, and consume business insights in the way that serves you and your role most effectively.

Beyond those three, Power BI also features two other elements:

Power BI Report Builder, for creating paginated reports to share in the Power BI service. Read more about paginated reports later in this article.
Power BI Report Server, an on-premises report server where you can publish your Power BI reports, after creating them in Power BI Desktop. Read more about Power BI Report Server later in this article.

Type of Charts are :

**1. COLUMN CHART**

A column chart is a data visualization where each category is represented by a rectangle, with the height of the rectangle being proportional to the values being plotted. Column charts are also known as vertical bar charts.

**Advantages**

They are particularly useful when:

1. **The data has a small number of discrete categories, with a single value for each category.** Where there are multiple values per category, the variables such as small multiples, cluster column charts, and stacked column charts, shown above, are superior.
2. **The goal is to compare the values of each category.**
3. **The intent is to make it simple for the viewer.** Column charts are arguably sometimes the best of all visualizations, as they tap into our instinctive ability to understand heights, whereas most other data visualizations require some degree of training for the reader to decode.

**Limitations and alternatives**

Column charts are a relatively poor choice when:
1. There are a very large number of categories. With more than about ten data points, other visualizations such as dot charts or even bubble clouds, donut charts, pie charts, and word clouds, are often better.
2. It is interesting to look at the cumulative values of the categories. In such situations pie charts, donut charts, and waterfall charts tend to be superior.
3. The values being represented are small counts (numbers less than 10), in which case pictograph column charts and minimal column charts are often clearer and more interesting.
4. The intended audience has a low level of interest. In this case, the variants of pictographs can be more visually engaging.
5. The values being represented are rates (e.g., deaths per thousand), in which case pictograph area and waffle charts are better.

**2. STACKED COLUMN CHART**

Power BI Stacked Column Chart & Stacked Bar Chart  both are most usable visuals in Power BI.

Stacked Column Chart is useful to compare multiple dimensions against a single measure. In a Stacked Column Chart, Axis is represented on X-axis and the data is represented on Y-axis.

**3. PIE CHART**

Pie charts in Power BI are mostly used for visualizing the percentage contribution for various categories in order to assess the performance of these categories. The pie charts are handy tools as they allow very quick and effective decision making owing to the insights they provide. Power BI provides an easy and quick approach to build pie charts.

**Things to Remember**

1. In Power BI, we need not perform any extra step in order to obtain percentage contribution values in pie chart, as they are provided by Power BI automatically.
2. Other variants of pie chart such as donut chart and gauge chart are not dependent on pie chart in Power Bi, rather they are available as ready-made charts.

**4. DONUT CHART**

These visuals can be created and viewed in both Power BI Desktop and the Power BI service. The steps and illustrations in this article are from Power BI Desktop. A donut chart is similar to a pie chart in that it shows the relationship of parts to a whole. The only difference is that the center is blank and allows space for a label or icon.

**5. FUNNEL CHART**

These visuals can be created and viewed in both Power BI Desktop and the Power BI service. The steps and illustrations in this article are from Power BI Desktop. A funnel chart helps you visualize a linear process that has sequential connected stages.

**6. RIBBON CHART**

In the new Ribbon Chart visual there is a really nice feature when you hover your cursor over the connective "ribbon" part. It displays a tool tip that has the previous bar total, the next total, and change in position between the two totals.

**7. INCLUDE AND EXCLUDE**

1. When we create a visualization and exploring data sometimes we focus on specific data. Also, we want to remove a specific point because we don’t want to focus on them.
2. Now, we can select one or more points and right-clicks to include or exclude points in your visual.
3. Exclude will filter out the points you’ve chosen to exclude.

**8. VIEW DATA AND IMPORT**

Mainly, Power Bi Desktop support two types of data source connection mode like Import & Direct Query mode. Here we will focus on Import mode.

In this mode Power Bi Desktop store the data inside Power Bi Cache. If your data size is less then 1 GB or data not continually changing then you can use Import mode.

And it is very fast compare to Direct Query mode because all data comes from Power Bi Desktop Cache, so you can use this mode to develop & testing purpose.

But later on you have to change your data source mode as a Direct Query for production, it will be depends on your organization you want to change this or not.

When you choose import mode, in that case Power Bi fetch the data from given source and load into Power Bi Cache, this is one time activity. Later on you can Schedule or refresh to get latest Data.
