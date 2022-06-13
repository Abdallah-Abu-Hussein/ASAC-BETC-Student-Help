# Business Intelligence 

![](./Pasted%20image%2020220517205355.png)

### What's it ?

*BI* is about integrating all the information streams produced by a firm into a single, coherent enterprise-wide set of data and then analyze the data and present it to managers so that managers can make better decisions and plans.

### About Data :
Any business operation will generate data there's  two main types of Data :
### Structured data 
which resides in predefined formats and models such as a database.
### Unstructured data 
which is stored in its natural format until it’s extracted for analysis, it is not organized in a pre-defined manner

![](./images/Pasted%20image%2020220520064451.png)
### The problems with unstructured Data

1. it's unsolved problem in the tech industry
2. waste 30%-40% of workers time 
3. it may contain important large information that's needed for analysis and decision making, but since the difficulty of properly searching, finding, and assessing unstructured data, organizations may not draw upon these vast reservoirs of information, which could influence a particular decision, task, or project. This can ultimately lead to poorly informed decision-making. 
4. Volume of data,up to 85% of all data exists as Unstructured and semi-structured data. 
5. Searchability of unstructured textual data.

### How to solve those problems :
Answer > *Metadata* 

### What's Metadata?
Short answer, Metadata it's data about data, like as author and time of creation, and this can be stored in a relational database.

![](./images/Pasted%20image%2020220520074508.png)

> To solve problems with searchability and assessment of data, it is necessary to know something about the content. This can be done by adding context through the use of metadata. Many systems already capture some metadata (e.g. filename, author, size, etc.), but more useful would be metadata about the actual content – e.g. summaries, topics, people, or companies mentioned. 

## Types of Employees and Decision making in companies
###### Employees :

1. `Senior management` : makes long-range strategic decisions about products and services as well as ensures financial performance of the firm.
2. `middle management`:carries out the programs and plans of senior management
3. `operational management`: is responsible for monitoring the daily activities of the business.

- `Knowledge Workers`: such as engineers, scientists, or architects, design products or services and create new knowledge for the firm, whereas.

- `Data workers`: such as secretaries or clerks, assist with scheduling and communications at all levels of the firm. 
 
###### Decisions :

1. `structured` > Repetitive and routine; involve definite procedure for handling so they do not have to be treated each time as new
2. `unstructured` > Decision maker must provide judgment, evaluation, and insight to solve problems
3. `semistrctured` > Only part of problem has clear-cut answer provided by accepted procedure

`Senior managers` Make many unstructured decisions
`Middle managers`Make more structured decisions but these may include unstructured components
`Operational managers` and rank and file employees
Make more structured decisions

![](images/Pasted%20image%2020220520082550.png)
### Types of information Systems :
# TPS 
*Transaction processing systems*Serve operational managers and staff, Perform and record daily routine transactions necessary to conduct business Examples: sales order entry, payroll, shipping, Allow managers to monitor status of operations
Serve predefined, structured goals and decision making ,Provide information for other systems.

# MIS
 *Management Information Systems* Serve middle management,Provide reports on firm’s current performance, based on data from T P S, Provide answers to routine questions with predefined ,procedure for answering them,Typically have little analytic capability

# DSS
*Decision Support Systems* Serve middle management and business analysts
Support non-routine decision making
Perform advanced analysis:
Goal Seeking Analysis
What if Analysis
May use external information as well T P S / M I S data

# EIS

*Executive Information Systems*Also called Executive Support Systems (ESS)
Support top level senior management
Address non-routine decisions
Requiring judgment, evaluation, and insight
Incorporate data about external events (e.g., new tax laws or competitors) as well as summarized information from internal M I S and D S S Example: Digital dashboard with real-time view of firm’s financial performance


![](/images/Pasted%20image%2020220521023741.png)
![](./images/Pasted%20image%2020220521023830.png)

### Business Processes :

- Business processes, refer to the manner in which work is organized, coordinated, and focused to produce a valuable product or service. 
- Business processes are logically related set of activities that define how specific business tasks are performed.
- These activities are supported by flows of information, and knowledge among the participants in business processes.
- Businesses: Can be seen as collection of business processes.

### Types of Business Processes

#### Operational process

- Operating processes create, add, or deliver value for which customers are willing to pay. They develop, make, sell, and deliver products and services. 
- They are typically designed to execute an organization's stated business strategy. 
- Examples of operating processes can be product manufacturing, sales order processing, customer services, or rendering repair and warranty services.

#### Management process


- This involves the planning, monitoring and the general oversee. This means ensuring that the team is meeting targets, that the workplace is compliant and safe, and that concerns of employees are dealt with...etc.
- Decision-making processes are management processes that define objectives, study alternatives, analyze available data. They interpret findings and compare alternatives to form a conclusion or make a choice upon which the organization may act.

- Examples of decision-making processes include strategic planning, selecting new suppliers, acquiring or merging with another organization, or how best to restructure during trying economic conditions.

#### Supporting process

- The processes that make it possible for the operational and management processes to be carried out effectively, they don’t generate income themselves, but are there to serve the internal body of staff across the organization.  
- Like : inventory replenishment and machine maintenance. processes that support management processes are administrative, typically associated with finance, accounting, sales, or human resources.

### Tools and Techniques Used In BI
 
##### Tools : 

1. Data Warehouses
2. Data Marts 
3. Hadoop
4. OLAP

### Data Warehouses

DWs are a Database where current and historical data of potential interest to decision makers throughout the company is stored.

#### How it works 

  This data is combined with data from external sources and transformed by correcting inaccurate and incomplete data and restructuring the data for management reporting and analysis before being loaded into the data warehouse.
  
![](./images/Pasted%20image%2020220521031847.png)

### Why its important (Benefits) :

-  **A Data Warehouse Delivers Enhanced  Business Intelligence** By providing data from various sources.
- **A  Data Warehouse Saves Time** Because users can quickly access critical data from  a number of sources all in one place
- **A  Data Warehouse Enhances Data Quality  and Consistency** By the conversion of data from numerous source systems into a common format. Since each data from is standardized, each department will  produce Data that is in line with all the other departments.

### Data Marts 

  A data mart is a simple form of a data warehouse that is focused on a single subject  like Sales, Finance, or Marketing. usually built  and controlled by a department within an organization.
 
![](./images/Pasted%20image%2020220521033218.png)

### Hadoop

Is an open source software framework that **enables distributed parallel processing of huge amounts of data across inexpensive computers** and it's managed by the Apache Software Foundation.

### How it works :

It breaks a big data problem down into sub-problems, distributes them among up to thousands of inexpensive computer processing nodes, and then combines the result into a smaller data set that is easier to analyze. it can handle unstructured and semi-structured data in vast quantities, as well as structured data as well as for a staging area for unstructured and semi-structured data before they are loaded into a data warehouse.

### OLAP
 
Stands for **Online analytical processing** is a software that allows users to analyze information from multiple database systems at the same time. 

![](./images/Pasted%20image%2020220521034040.png)

#### How It Works 

- A Data warehouse would extract information from multiple data sources and formats like text files, excel sheet, multimedia files…etc.
- The extracted data is cleaned and transformed. Data is loaded into an OLAP server (or OLAP cube) where information is pre-calculated in advance for further analysis.
- The OLAP Cube consists of numeric facts called measures which are categorized by dimensions. OLAP Cube is also called the hypercube

##### Techniques :
1. Data Mining 
2. Simulating and forecasting Like:

   >  - What-if analysis
   >  - Goal seeking and optimization

### Data Mining 
Data mining provides insights into corporate data that cannot be obtained with OLAP **by finding hidden patterns and relationships in large databases and inferring rules from them to predict future behavior.** The patterns and rules are used to guide decision making and forecast the effect of those decisions.

### Simulating and forecasting 
#### What-if analysis 

> Is About building a model that establishes relationships between many variables and then changes some variables to see how other variables are affected. Excel is popular for building relatively simple what-if models.

#### Goal seeking and optimization 

> similar to what-if analysis, but in reverse. Instead of estimating several variables and calculating the result, the user sets a target value for a particular metric, such as profit/loss, and tells the software which variable to change to try to reach the goal.

### EU General Data Protection Regulation (G D P R)

> - European countries do not allow businesses to use personally identifiable information without consumer’s prior consent.
> - Before collecting Data on costumers they must provide their informed consent before any company can legally use data about them, and they have the right to access that information, correct it, and request that no further data be collected.
> - E U member nations cannot transfer personal data to countries without similar privacy protection
> 


# Sources
[1] Management Information Systems: Managing the Digital Firm 15th Edition (2018) by Kenneth Laudon, Jane Laudon
