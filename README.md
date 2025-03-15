# Insights-Through-Analysis

# Overview : 

 1. Enhance the funnel chart by highlighting the top 10 selling products by sales amount.

 2. Enhance the clarity of the histogram by using age bins instead of distinct ages.

 3. Enhance the scatter chart by clustering the cities into four categories according to their performance.

--------------------------------------------------------------------------------------------------------------------------------------------

# 1. Enhance Funnel Chart with Top N Analysis

  To reduce clutter in the funnel chart displaying 295 products and their revenues, apply a Top N analysis to highlight the top 10 selling products by revenue.

# 1. Select the Funnel Chart

  • Click the funnel chart visual and select the Focus Mode button to enlarge it.

# 2. Expand the Filter Options
    
  • In the Filter Pane, click the down arrow to expand the filtering options.

# 3. Set Filter Type

  • Choose Top N as the Filter type.

# 4. Input Filter Value
    
  • Ensure Top is selected and input 10 as the filter value.

# 5. Sort by Revenue
   
  • Add Sales Amount to the By value field to enable sorting by revenue.

# 6. Apply the Filter
   
  • Click Apply Filter to see the updated chart with the top 10 selling products by revenue.

![image_alt](https://github.com/DSgenes/Insights-Through-Analysis/blob/09dd30aa17eed08e6acf1a0c34f8e33913a960cb/Screenshot%20-%202.png)

------------------------------------------------------------------------------------------------------------------------------------------------

# 2. Enhance Histogram with Age Group Bins
 
   To segment customer ages into decade ranges (e.g., 20-30, 30-40, 40-50, 50-60) on the histogram, follow these steps:

# 1. Locate the CustomerAge Column
 
   • In the Data Pane on the right, find the CustomerAge column.

# 2. Create a New Group

   • Right-click on CustomerAge and select New Group from the pop-up menu.

# 3. Set Bin Type

   • In the Groups menu, select Bin as the group type and Size of bins as the bin type.

# 4. Define Bin Size
   
   • Set the bin size to 10 to segment ages into decade ranges (20-30, 30-40, 40-50, 50-60), then select OK.

# 5. Remove CustomerAge from X-Axis
  
   • Remove CustomerAge from the X-axis of the histogram visualization.

# 6. Add Age Group Bins to X-Axis

   • Drag and drop the newly created CustomerAge Bin to the X-axis to incorporate the age group bins.

![image_alt](https://github.com/DSgenes/Insights-Through-Analysis/blob/ffd6dd941bb898eeb3673864e7e0252abbba963e/Screenshot%20-%203.png)

--------------------------------------------------------------------------------------------------------------------------------------------------

# 3. Add Clustering Techniques to the Scatter Chart

   To integrate clustering into the scatter chart, follow these steps:

# 1. Access Scatter Chart Options

   • Click the ellipsis (three dots) in the upper-right corner of the scatter chart.

# 2. Select Clustering Option

   • From the drop-down menu, select Automatically find clusters.

# 3. Modify Cluster Description
 
   • In the Clusters window, update the description to Clusters for City based on Revenue and Order Number.

# 4. Set Number of Clusters

   • Enter 4 as the desired number of clusters in the Number of clusters field.

# 5. Apply the Clustering
 
   • Click OK to finalize the clustering settings.

![image_alt](https://github.com/DSgenes/Insights-Through-Analysis/blob/f1ef570634fd32e51486a00283d3047c826835c3/Screenshot%20-%204.png)

---------------------------------------------------------------------------------------------------------------------------------------------------

# Overall View : 

![image_alt](https://github.com/DSgenes/Insights-Through-Analysis/blob/5480d3a458b6422b08a2a5d401fd99eeaaa1d603/Screenshot%20-%205.png)

