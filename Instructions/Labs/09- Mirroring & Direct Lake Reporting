# Exercise 7: Data Warehouse Analyze Data in a Warehouse with Fabric Copilot

### Estimated Duration: 60 minutes

In this lab, you will analyze data in a warehouse using Fabric Copilot by connecting to your data source, running queries, and visualizing insights to drive informed decision-making.

## Lab objectives

You will be able to complete the following tasks:

- Connect to the Data Warehouse  
- Explore Data Sources  
- Run Data Queries  
- Visualize Data Insights  
- Generate Reports  
- Collaborate on Findings  

1. Select the workspace **fabric-<inject key="DeploymentID" enableCopy="false"/>** (this is the workspace that mimics the lab environment)

   ![New dataflow.](./Images/26.png)
 
1. Select **Data Warehouse<inject key="DeploymentID" enableCopy="false"/>** from the list.

   ![New dataflow.](./Images/33.png)

1. In the **Explorer** pane, verify that the **dbo** schema in the data warehouse contains the following four tables:
   
    - **DimCustomer**

    - **DimDate**

    - **DimProduct**

    - **FactSalesOrder**

      ![01](./Images/02/Pg4-T2-S9.png)  

    > **Tip**: If the schema takes a while to load, just refresh the browser page.
 
1. Clicking on the **Model** view allows you to view the relationships between different tables within the data warehouse.

    ![](./Images/pg-8.png)

1. When you click on the relationship between **FactSalesOrder** and **DimCustomer** and access its properties, you're essentially examining how these two tables are linked together. This relationship defines how data from these tables can be combined or related when querying or visualizing in Power BI.

     ![](./Images/10.png)

    - This relationship indicates that each record in the "FactSalesOrder" table is associated with a specific customer represented in the "DimCustomer" table. For example, if we have a sales record in "FactSalesOrder" for a particular transaction, we can use this relationship to look up additional details about the corresponding customer from the "DimCustomer" table.

    - This linkage is crucial for defining the Semantic Model used by Power BI. The Semantic Model essentially acts as a blueprint that outlines how data elements are interconnected and how they should be interpreted within Power BI. By establishing and defining relationships between tables, we're instructing Power BI on how to navigate and analyze the data effectively.
 
1. Clicking on **New Report** from the **reporting tab** allows you to create a new report within Power BI. This report will utilize the Semantic Model defined by the relationships established in the data warehouse.
 
   ![](./Images/pg-08-1.png)

1. The Semantic Model, as defined in the data warehouse, is reflected in the Power BI interface. This includes the tables and their respective fields visible in the Data Pane of Power BI, which you can use to build your reports.

1. Locate and click on the **Copilot** feature within the tool or platform you're using.

   ![](./Images/13.png)

1. If the pop-up titled **Welcome to Copilot in Power BI** appears, proceed by selecting **Get Started**.

   ![](./Images/14.png)

1. Locate the logo or icon associated with Copilot, then click on it to access its menu or interface.

   ![](./Images/15.png)

1. Recognize that Copilot offers functionalities such as providing suggestions, generating code snippets, and offering explanations. However, it's important to note its limitations, which may include the inability to create certain visualizations or directly modify page layouts.

1. Selecting **What's in my data** prompts Copilot to analyze the semantic model or dataset currently in use.

   ![](./Images/16.png)

   - Copilot's analysis indicates that your dataset encompasses **sales performance**, **customer details**, **product information**, and **query performance**, offering a holistic view of your business operations. It suggests potential applications such as sales trend analysis, regional performance evaluation, customer segmentation, product evaluation, and query optimization. This highlights Copilot's adept understanding of dataset components and analytical techniques, providing valuable insights for strategic decision-making, customer engagement strategies, product refinement, and system enhancement.
    
   - Copilot represents a significant advancement in AI utilization, showcasing its capability beyond just generating code or manipulating data. Its capacity to assist in analyzing datasets is particularly noteworthy, as it offers intelligent insights and suggestions that enhance the entire data analysis process. By leveraging Copilot, users can gain a deeper understanding and uncover valuable patterns within their datasets, ultimately empowering them to make informed decisions based on the insights derived. This highlights the transformative potential of AI in augmenting human capabilities and driving innovation in data analysis methodologies.
 
1. Explore the capabilities of Copilot further by **clicking on its logo** within the text box. This will allow you to access additional features and functionalities that Copilot offers, providing a deeper understanding of its capabilities.
  
   ![](./Images/24.png)

1. Click **Create a page that shows**.

    ![](./Images/17.png)
   
1. At this time, you can only ask for a page or report to be created. You can't ask for specific visuals.
 
1. Type the following command into Copilot:
  
    ```
    Create a page that shows "Total Sales by Product Category"
    ```
 
1. **Execute the command** and let Copilot generate the report. Note that AI-generated results may vary, and you're never entirely sure what you'll get.

    ![](./Images/18.png)

   - The report provides a comprehensive analysis of total sales across a spectrum of product categories, revealing a consistent pattern of total sales summing up to 19.59 million across all 39 categories. Similarly, the quantity sold uniformly stands at 25.98 thousand units for each category. With an average total sales figure of 4.55 thousand, it suggests an even distribution of sales performance across all categories. This uniformity underscores a balanced sales landscape across diverse product categories, thereby offering valuable insights for informed decision-making in subsequent business strategies.
   
1. Type the following command into Copilot

    ```
    Suggest Content for this Report
    ```
 
1. **Expand each suggestion** to see the text of the prompt and what will be created. This helps illustrate the range of suggestions Copilot can provide.
 
1. Select the **Sales Performace Analysis** report as it's usually a decent report to work with. Note that the report generated can vary.
 
   ![](./Images/22.png)
  
    >**Note:** Click **Edit** to demonstrate that you can adjust the query and customize the report.

   ![](./Images/21.png)

1. **Clear the input box** and select:

    ```
    Give me an executive summary
    ```
    ![](./Images/23.png)

1. Save the report as **Sample**.

1. The summary provides an overview of sales revenue data from 2021 to 2022, highlighting increases year-over-year and identifying key months and regions driving revenue growth, with 2022 contributing significantly to total revenue, led by strong performance in the United States.

## Summary

In this lab, you connected to a data warehouse using Fabric Copilot and explored the available datasets. You ran queries to extract insights and created visualizations for effective analysis. Finally, you compiled your findings into reports and collaborated with team members on the results.

### You have successfully completed the lab. Click on Next >> to procced with next exercise.
