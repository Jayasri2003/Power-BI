
# “Real-Time Analysis of Customers Bank Loan”

### “ARUMUGAM PILLAI SEETHAI AMMAL COLLEGE”

NM ID	:424EE0A4B4F3E59B7194989EEB23D186

NAME    :JAYASRI S


Trainer Name	:	R.UMAMAHESHWARI

Master Name	    :	R.UMAMAHESHWARI




### ABSTRACT

In the realm of banking operations, data serves as a pivotal asset, particularly in the context of loan accounts. This project, "Real-Time Analysis of Customer Bank Loan," aims to harness the power of PowerBI, a leading business intelligence tool, to conduct real-time analysis and visualization of loan customer data. The objective is to provide banks with deep insights into loan customer demographics, behaviors, and trends, thereby empowering data-driven decision-making and enhancing customer satisfaction in the loan process. Through this analysis, banks can swiftly respond to changing customer needs, identify cross-selling opportunities, and tailor loan products to meet customer preferences. This project aligns with the broader goal of digital transformation in banking, fostering efficiency, innovation, and a customer-centric approach.




## INDEX


1	Chapter 1:Introduction

2	Chapter 2: Services and Tools Required 

3	Chapter 3: Project Architecture

4	Chapter 4: Modeling and Result

5	Conclusion	

6	Future Scope	

7	References	

8	Links	

 
### CHAPTER 1
#### INTRODUCTION
#### 1.1	Problem Statement
In the dynamic landscape of banking, understanding the behaviors and preferences of loan customers is paramount for efficient loan management and revenue generation. However, traditional methods of data analysis often fall short in providing real-time insights, especially given the vast and rapidly changing nature of loan account data. This lag in analysis can lead to missed opportunities for personalized engagement, cross-selling, and up-selling, ultimately impacting the bank's revenue and customer satisfaction. The diverse data set including loan amounts, interest rates, transaction amounts, and customer demographics presents additional challenges for analysis.

#### 1.2	Proposed Solution
The proposed solution is the development of a PowerBI dashboard tailored for real-time analysis of customer bank loan data. This dashboard will seamlessly integrate data from various sources including loan amounts, interest rates, transaction details, and customer demographics. By providing an intuitive and interactive interface, banks can gain a holistic view of loan customer behaviors and trends. The real-time analysis capability of the dashboard enables prompt responses to customer preferences, identification of cross-selling opportunities, and customization of loan products.

#### 1.3	Feature
The Power BI dashboard for real-time loan analysis will include the following key features:

•	Real-Time Loan Analysis: The ability to analyze loan data as it is generated, providing immediate insights into loan performance.

•	Loan Type Distribution: Visual representation of the distribution of loan types among customers, allowing banks to understand which products are most popular.

•	Repayment Patterns: Charts and graphs showing customer repayment behaviors, including on-time payments, late payments, and defaults.

•	Customer Segmentation: Segmentation of customers based on demographics and loan behaviors, enabling targeted marketing and personalized services.

•	Predictive Analysis: Use of historical data and machine learning algorithms to predict future loan trends and customer behaviors.

#### 1.4	Advantages
Implementing this Power BI dashboard for real-time loan analysis offers several advantages for banking institutions:

•	Informed Decision-Making: Banks can make data-driven decisions promptly based on real-time insights, optimizing their loan offerings and strategies.

•	Enhanced Customer Engagement: Understanding customer loan behaviors and preferences allows banks to engage with customers more effectively, offering tailored products and services.

•	Revenue Growth: By identifying trends and patterns in loan data, banks can optimize their offerings, leading to increased cross-selling, up-selling, and customer retention.

#### 1.5	Scope
The scope of this project is extensive, aiming to benefit banking institutions of all sizes seeking to optimize their loan services and customer interactions. The Power BI dashboard will provide a foundational tool for real-time analysis and visualization of loan data. Future expansions of the project may include:

•	Advanced Analytics: Incorporation of machine learning algorithms for more sophisticated predictive modelling.

•	Integration with Additional Data Sources: Expanding the dashboard to integrate with more diverse datasets such as credit scores, economic indicators, and customer feedback for comprehensive insights.

•	Compliance and Risk Management: Integration of risk management tools to monitor and mitigate potential loan risks.

•	User Customization: Providing flexibility for banks to customize the dashboard to their specific needs and preferences.
By continuously evolving and expanding, this project lays the foundation for banking institutions to navigate the complex landscape of loan management with data-driven insights, ultimately leading to improved customer satisfaction, revenue growth, and operational efficiency.

### CHAPTER 2
#### SERVICES AND TOOLS REQUIRED
#### 2.1 Services Used
Data Collection : Banks need to collect and store customer data in real-time.

2.2 Tools and Software used

Tools:
•	PowerBI: The main tool for this project is PowerBI, which will be used to create interactive dashboards for real-time data visualization.

•	Power Query: This is a data connection technology that enables you to discover, connect, combine, and refine data across a wide variety of sources.

Software Requirements:

•	PowerBI Desktop: This is a Windows application that you can use to create reports and publish them to PowerBI.

•	PowerBI Service: This is an online SaaS (Software as a Service) service that you use to publish reports, create new dashboards, and share insights.

•	PowerBI Mobile: This is a mobile application that you can use to access your reports and dashboards on the go.

### CHAPTER 3
#### PROJECT ARCHITECTURE
#### 3.1 Architecture

1.	Data Collection: Real-time customer loan data is collected from various sources like bank transactions, loan applications, etc.

2.	Data Visualization: The processed data and the results from the predictive models are visualized in real-time using PowerBI. PowerBI allows you to create interactive dashboards that can provide valuable insights into the data.

•	Frontend Tool: Power BI for creating interactive and dynamic dashboards.

3.	Data Access: The dashboards created in PowerBI can be accessed through PowerBI Desktop, PowerBI Service (online), and PowerBI Mobile.

•	Power BI Desktop: Windows application for creating and designing reports and dashboards.

•	Power BI Service: Online SaaS platform for publishing reports, sharing insights, and collaborating with stakeholders.

•	Power BI Mobile: Mobile application for accessing dashboards on smartphones and tablets.

This architecture offers a robust solution for real-time analysis of customers bank loan. However, customization may be necessary based on the bank’s specific needs, existing infrastructure, and compliance requirements with data privacy and security regulations.

### CHAPTER 4
#### MODELING AND RESULT
#### Manage Relationship:
In the Power BI model, relationships are established to connect the Customer ID from the Customer sheet with the Loan ID in the Loan Data sheet, enabling a comprehensive view of each customer's loans. Additionally, the Customer ID from the Customer sheet is linked to the Transaction sheet, allowing insights into individual transaction details alongside customer information. This structure enables dynamic analysis: users can explore customer segments, loan details, and transaction patterns seamlessly.

Visualizations within Power BI can then offer valuable insights. For example, bar charts can illustrate customer segmentation based on age groups or income levels, while line charts track loan performance over time, highlighting trends in loan types and statuses. Transaction analysis can be displayed through scatter plots or maps, showing transaction amounts and locations. If predictive models are integrated, users can view loan status predictions alongside actual outcomes, aiding in risk management. Overall, this interconnected Power BI model empowers users to make informed decisions by providing a holistic view of bank loan customers, their loans, and transaction behaviours.

![Relationship](https://github.com/Jayasri2003/Power-BI/assets/148708193/27df9bec-09ea-4ddf-8399-7667cc3f94fd)

#### Grouping of age by ranges:

As the customer age range from 20 to 50, we shall group them into three groups for easy profiling. We will group the ages into three groups.

20-30-year-olds: These individuals are typically young adults, just starting out in their careers or pursuing higher education. They might be exploring various life paths and are often tech-savvy and open to new experiences.

30-40-year-olds: This segment often consists of individuals who are well into their careers, starting families, and establishing themselves in their professions. They might be focused on career growth and family life.

40-50-year-olds: Individuals in this age range are often at the peak of their careers, with many years of professional experience. Some may have teenage children and are balancing family responsibilities with work commitments.

Each of these segments represents a different stage of life and may have distinct needs and preferences. By categorizing customers into these age ranges, we can better tailor our services and products to suit their lifestyles and interests.

![9](https://github.com/Jayasri2003/Power-BI/assets/148708193/f0ccac16-347f-4e5e-a829-32160fe72e30)

#### Edit Relationship:
When editing relationships between tables in Power BI, establishing a one-to-one relationship between the "Loan" and "Customer" tables is a crucial step in data modelling. This relationship ensures that each customer in the "Customer" table corresponds to exactly one loan in the "Loan" table, and vice versa.

By linking the "Customer ID" field as a one-to-one relationship, we are enforcing a direct and unique association between these two tables. This means that for every customer identified by their unique ID in the "Customer" table, there exists precisely one corresponding record in the "Loan" table, and no more. Similarly, each loan record in the "Loan" table is tied to one specific customer.

This setup facilitates efficient data analysis and reporting. For instance, when analysing loan data, we can seamlessly incorporate customer details such as name, contact information, or demographics from the "Customer" table without duplication or confusion. Likewise, in reports related to customers, loan-specific information can be accurately displayed for each customer, enhancing the depth of insights derived from the data.

![3](https://github.com/Jayasri2003/Power-BI/assets/148708193/0af12e22-8a4b-4a2f-bb2a-8c994cb4b07a)

#### Check Distinct Values:
To ensure data accuracy and integrity across all sheets, it is essential to check for distinct values within the "Customer Data," "Loan Data," and "Transaction Data" sheets. Identifying distinct values helps in understanding the uniqueness and completeness of the data within each sheet.

In the "Customer Data" sheet, reviewing distinct values such as customer IDs, names, contact details, and any other unique identifiers allows us to verify that each customer is represented 
only once. This process helps in detecting any duplicate or missing entries, ensuring that each customer's information is correctly captured and avoiding data redundancy.

Similarly, examining distinct values in the "Loan Data" sheet provides insights into the unique loan identifiers, loan types, amounts, and other loan-specific details. Confirming the uniqueness of loan IDs ensures that each loan is accurately recorded, preventing any confusion or errors in loan-related analysis.

![1](https://github.com/Jayasri2003/Power-BI/assets/148708193/fe0725fa-0069-442f-9c63-53bffa4abf8d)

#### Replacing Values:
Replacing values in the "Income" field within a dataset can be a crucial step in data cleaning and preparation, especially when dealing with financial or economic data. In Power BI, the "Replace Values" function provides a straightforward yet powerful method to standardize and update income information across the dataset.
When using "Replace Values" for the "Income" field, analysts can address various scenarios. One common use case is to handle missing or null values. By replacing these with a default value or using interpolation techniques, such as filling missing values with the mean or median income, the dataset becomes completer and more suitable for analysis.

Another common scenario is correcting inconsistencies in income formatting. For example, if incomes are recorded in different formats such as currency symbols, commas, or decimals, "Replace Values" can be employed to unify the format. This ensures that all income values are in a consistent format, making calculations and comparisons more straightforward.

Moreover, "Replace Values" is valuable for handling outliers or erroneous entries in the "Income" field. Analysts can identify values that seem unrealistic (such as extremely high or low incomes) and replace them with more appropriate values. This improves the overall quality of the dataset and ensures that outliers do not skew analysis results.
Additionally, when anonymizing or masking sensitive income data for privacy reasons, "Replace Values" allows for the substitution of actual income values with masked or generalized ranges. This protects individual privacy while still allowing for meaningful analysis of income distribution trends.

![6](https://github.com/Jayasri2003/Power-BI/assets/148708193/2932e88e-d25a-49ac-a207-630e0b3ee5ce)


#### Changing Data Type :
Changing the data type of a field, such as "Age," to a whole number is a common and straightforward process in Power BI, providing greater flexibility and accuracy in data analysis. When "Age" is represented as a whole number rather than text or decimal, it becomes easier to perform mathematical operations and comparisons.

Converting "Age" to a whole number using the "Change Data Type" feature ensures that each individual's age is treated as a discrete, whole value. This is particularly useful when calculating averages, identifying trends, or creating age groupings for analysis. For example, if "Age" is stored as text or decimal values, converting it to a whole number allows for direct comparisons such as filtering for customers above a certain age or calculating the average age of a group.

Furthermore, changing "Age" to a whole number enhances data consistency and readability. It eliminates the risk of having ages stored inconsistently, such as "30.5" or "thirty-two," which can cause issues in calculations or sorting. By standardizing "Age" as a whole number, the dataset becomes cleaner and more manageable for analysis and reporting purposes.
Additionally, the whole number data type is efficient for storage and computation. It takes up less memory compared to text or decimal formats, which is beneficial when working with large datasets. This efficiency ensures better performance and responsiveness when interacting with reports and dashboards in Power BI.

Moreover, when visualizing "Age" data, having it as a whole number allows for more straightforward representation in charts and graphs. Histograms or bar charts showing age distribution become more intuitive and informative when "Age" is uniformly treated as a whole number.

![8](https://github.com/Jayasri2003/Power-BI/assets/148708193/b08d1b0e-6469-434b-a145-6550ee8a6724)

 

#### DASHBOARD :


![OUTPUT 1](https://github.com/Jayasri2003/Power-BI/assets/148708193/77f356ec-e5a1-4976-9097-bd4711015836)


![OUTPUT 2](https://github.com/Jayasri2003/Power-BI/assets/148708193/85051b49-533b-4b93-8556-a2e8a4d7ebf1)

![OUTPUT 3](https://github.com/Jayasri2003/Power-BI/assets/148708193/33221884-5cc0-492f-b904-68489c0fbb54)

![OUTPUT 4](https://github.com/Jayasri2003/Power-BI/assets/148708193/0d9cbb94-c9d4-474d-8857-5a7e469e9afc)


### CONCLUSION
The project "Real-Time Analysis of Customers Bank Loan " using PowerBI has showcased the significant impact of data analytics within the banking sector. Through real-time analysis of loan customer data, valuable insights into customer behaviour, preferences, and trends have been uncovered, empowering informed decision-making processes. The interactive dashboards and reports have offered a comprehensive view of loan customer data, facilitating the identification of patterns and correlations. This in-depth analysis has not only streamlined the efficiency of data processing but has also bolstered the bank's capacity to deliver personalized services tailored to individual loan customer needs. Moreover, the project underscores the pivotal role of data visualization in rendering complex data more understandable and accessible. Leveraging PowerBI, the bank has been able to present loan customer data in visually appealing formats, aiding in clearer insights and improved decision-making. Overall, the "Real-Time Analysis of Customers Bank Loan " project demonstrates the power of data analytics in optimizing loan services, enhancing customer satisfaction, and driving strategic decisions within the banking industry.


### FUTURE SCOPE
The future scope of the "Real-Time Analysis of Customers Bank Loan " project is expansive and promising. As advancements in analytics and machine learning continue to evolve, PowerBI can be harnessed to forecast future trends based on historical loan customer data. By integrating predictive analytics into the project, the bank can anticipate loan customer needs and offer initiative-taking solutions, thus enhancing customer satisfaction and loyalty. Moreover, PowerBI's versatility in integrating with various data sources opens avenues to incorporate diverse datasets, providing a more holistic view of loan customers. This expanded data integration could offer insights beyond traditional banking transactions, such as customer behaviours, market trends, and economic indicators. Considering the growing importance of data privacy and security, future iterations of this project should prioritize robust data governance strategies. Implementing stringent data protection measures will ensure the secure handling of sensitive loan customer data while adhering to stringent data protection regulations. Furthermore, the project can explore the integration of real-time data streams for even more timely and relevant insights. By incorporating live data feeds, the bank can gain immediate visibility into loan customer activities, enabling prompt decision-making and personalized services. In conclusion, the future of the "Real-Time Analysis of Customers Bank Loan " project holds immense potential. By leveraging advanced analytics, integrating diverse datasets, implementing strong data governance, and embracing real-time data streams, the bank can transform its interactions with loan customers. This transformation could lead to improved customer satisfaction, enhanced risk management, and greater business success.


### REFERENCES
https://www.youtube.com/live/yQ8bT9AI4yc?si=CRoanVUhKlIynKrE
https://www.youtube.com/live/HSXxAQ1NioA?si=_1p_5m8BMmmQAFmR
https://www.youtube.com/live/NNdnLEsbClg?si=fJqDnqjTrBLF-la1



