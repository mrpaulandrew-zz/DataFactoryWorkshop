# ![Azure Data Factory Icon](https://github.com/mrpaulandrew/DataFactoryPreconPublic/blob/master/Images/ADF%20Icon%20Small.png "ADF Icon") Azure Data Factory Full Day Workshop 
Hello friends and welcome to this full day workshop on Azure Data Factory. Today we will be all becoming advanced factory workers!... And we completely recommend this description when describing your job to family members. But be warned, if you go on to tell them that the factory is in the cloud you are likely to be branded as crazy. However, here and now that is ok. You are amoungst like minded geeky friends that all want to become cloud factory workers as well :-)

On a more serious note; throughout ours days training you will quickly notice, like with most technologies, there is an awful lot of different ways you can implement this Azure orchestration service and understanding the best way to do something is often the biggest challenge. That said, if you only take away one thing from today we would ask that you have an appreciation of this fact. Then when delviering solutions you take a step back from the requirements and think about the overview technical design and how Azure Data Factory should fit into your platform as a core component.

All to often with new and shiny service we start playing around then try to make the technology fit our solution. Rather than thinking about the solution requirements and which technology meets our needs. This is true of all developers, we don't want to preach, so are simply asking for a little bit of mindfulness.
  
Moving on. You might have noticed that there are two of us **waves**. This is not an accident. This is designed to ensure that while someone is talking someone else is on hand to help with particular problems or discuss an issue you're facing. We each have sharpies and access to the whiteboard. We might be able to answer your question during the session, but during the break, lets dive into any details we've not covered or you want further clarification on.

## Today's Abstract

__Azure Data Factory – Zero to Hero__

If we want to achieve any data processing in the cloud we need an umbrella service to manage, schedule and handle our solution. For a long time when on premises, the SQL Agent has been our go to tool, combined with T-SQL and SSIS packages. It’s now time to upgrade and start using cloud native services to achieve the same thing in Azure. Within a Modern Data Warehouse, the primary component for delivering that orchestration is Azure Data Factory, combined with Azure Databricks.

In this full day of training we’ll start with the basics and then get hands on with the tools. We’ll build our own cloud ETL pipelines using all Data Factory has to offer. Plus, consider hybrid architectures to lift and shift your SSIS packages into Azure.

Specifically we'll be covering the following topics:

* An introduction to Azure Data Factory.
* How to extend our orchestration with Custom Activities and Azure Functions.
* Using SSIS packages in Azure.
* Data Factory Data Flow with Azure Databricks
* Dynamic metadata driven pipelines.
* Factory alerting and monitoring.
* Data Factory DevOps.

Have your laptops to hand and come armed with your Azure subscription, including credit and rights to deploy resources.

Please check with bill payer.

Infrastructure not included.

## Agenda 

__Module 0__ - Introductions  

__Module 1__ - What and why Azure Data Factory?  
 └── Service components  
 └── Integration Runtimes  
 └── Source control  

__Lab 1__ - Creating a simple copy pipeline.

*** Break ***

__Module 2__ - Dynamic pipelines and advanced patterns.  
 └── Lookups, ForEach, Child Pipelines  
 └── Alerting & Error handling  
 └── Templates  

__Lab 2__ - Copying all tables from a SQLDB using metadata driven parameters.

*** Lunch ***  

__Module 3__ - Data Factory Extensibility  
 └── Azure Functions  
 └── Web Activities vs Web Hook Activities  
 └── Custom Activities  

__Module 4__ - Data Factory Data Flows  
 └── Mapping Data Flows  
 └── Databricks Cluster Configuration   
 └── Wrangling Data Flows  

__Lab 3__ - Using data flows to transform and load your data.

*** Break ***

__Module 5__ - SSIS packages in Azure  
 └── The SSIS Integration Runtime cluster  
 └── Scale out package execution  

__Module 6__ - Data Factory in Production  
 └── Alerting & Monitoring  
 └── Security  
 └── Costing  
 └── DevOps  

__Module 7__ - Conclusions  
 └── Wider Solution Bootstrapping  
 └── Azure Data Factory in the Modern Data Warehouse  


## Structure our GitHub Repository
- Slides - You will find the latest version of all the slides located [here](https://github.com/mrpaulandrew/AdatisBIinAzureWorkshop/tree/master/Slides). 
- Labs - All the labs we will run through during this session. 
- Code Examples - You will see as we go through the session a lot of code in the slides. Rather than copying this from the slides, all content is here too. 
- Images - All the images used as documentation in labs.  

## Tools required for today
These labs require tools most Azure developers have on their development machines. They do need to be the latest edition for some of the new features to work. 

As a minimum delegates should have:  
- A laptop.
- An Azure subscription with available credit.
- A modern internet browser.
 
For delegates to get the most out of the day and get involved in advanced areas, we also recommend having the following tools available:
- Visual Studio 2017 (Community Edition or higher) 
- Azure extensions installed.
- Azure Data Lake tools installed.
- PowerShell extensions installed.
- SQL Server Management Studio (v17 or higher)
- Azure Storage Explorer
- PowerShell 5.1 or higher
- Azure modules installed
- GitHub desktop
- VSCode 
 
## About the speakers
There are business cards for all speakers on the desk at the front. 

### Paul Andrew 
__Principal Consultant & Solution Architect & Data Platform MVP @ Adatis Consulting Ltd__

Paul is a Microsoft Data Platform MVP with 10+ years’ experience working with the complete on premises SQL Server stack in a variety of roles and industries. Now as Data Analytics Consultant has turned his keyboard to big data solutions on the Microsoft cloud platform. Specialising in Data Factory, Data Bricks, Data Lake and Stream Analytics. Paul is also a STEM Ambassador for the networking education in schools’ programme, PASS chapter leader, a member of the Data Relay committee, SQL Bits, SQL Saturday, SQL Day, SQLGLA, PASS Summit speaker and helper. Currently the Stack Overflow top user for Azure Data Factory. As well as very active member of the technical community.

You can contact Paul via:

- Email [paul@mrpaulandrew.com](mailto:paul@mrpaulandrew.com)
- Twitter [@MrPaulAndrew](https://twitter.com/MrPaulAndrew)
- LinkedIn [In/mrpaulandrew](https://www.linkedin.com/in/mrpaulandrew/)
- Blog [mrpaulandrew.com](https://mrpaulandrew.com)


### Simon Whitley
__Director of Data Engineering & Data Platform MVP @ Advancing Analytics Ltd__

Simon is the technical lead for Adatis, driving their adoption of new architectures and leading Research & Development within the company. He has over a decade of analytics experience, largely within the Microsoft realm and has been pushing distributed cloud architectures for analytics for the past few years.

Microsoft Data Platform MVP, Simon runs the SQLSurrey PASS Chapter, speaks at a conferences across the world and user groups throughout the UK and Europe and will happily talk your ear off about the various new approaches we're currently working on.

You can contact Simon by:
- Email [simon@advancinganalytics.co.uk](mailto:simon@advancinganalytics.co.uk) 
- Twitter [@MrSiWhiteley](https://twitter.com/MrSiWhiteley)

### Links mentioned during the talk. 

As we talk about interesting links and examples we will collect these here for futrue reference. 
