# Microsoft-DP-700-Exam-Prep-Fabric-Data-Engineer-Associate-Notes
This Repository contains my "Microsoft DP-700 Exam Prep : Fabric Data Engineer Associate" Course Notes from Udemy

**I) Introduction**

**A) Course Overview**

**B) What is Data Engineering?**

**C) Evolution of Data Engineering**

**D) What is Lakehouse?**

**E) Medallion Architecture Explained!**

**F) Delta Lake - Hot Topic!**

**G) Azure Free Account**

**H) Azure Fundamentals**




# **I) Introduction**

# **A) Course Overview**

DP 700 certification is currently the most in-demand certification that every organization is seeking. However, obtaining this certification requires guided and structured learning, which includes mastering six key areas.

Let’s uncover the first area. In this area, you will learn all the important frameworks such as Madeleine architecture, Delta Lake, shortcuts, caching, egress, cost, and much more. This foundational knowledge will prepare you for more advanced topics.

After this, you will master your second area: Fabric Data Factory. Here, you will learn all the important activities and build end-to-end pipelines, including real-time scenarios, giving you practical, hands-on experience.

Next, it’s time to master the most in-demand technology: Spark. In this area, you will learn all the important PySpark functions, along with all the Spark functionalities available in Fabric, making you proficient in one of the most sought-after data engineering skills.

Now, let’s talk about the fourth area: data warehousing. Fabric Data Warehouse is not a traditional data warehouse—it is a lake-centric data warehouse. You will need to understand all the functionalities that are new to the world of data engineering, introduced specifically by Fabric.

The fifth area is my personal favorite: real-time analytics. In this area, you will learn about event streams and build end-to-end flows, including Event House, KQL databases. You will also learn how to write efficient custom query languages, giving you the ability to handle real-time data efficiently.

Finally, you need to have strong hands-on skills with Git in Fabric. This will enable you to efficiently perform continuous integration using Azure DevOps or GitHub, and continuous deployment using deployment pipelines in Fabric.

There is also one bonus area: Fabric Data Governance and Security. In this area, you will master data lineage, endorsements, Fabric access control, and OneLake access control, ensuring that you have a comprehensive understanding of data governance.

So why should you continue with this course? There are three main reasons. First, I am an Azure Data Engineer and have obtained many certifications, including BP 700, so I know exactly what you need to succeed. Second, this course strongly focuses on hands-on skills, because learning by doing is the best way to master these topics. Third, the course provides engaging lectures, so you will feel as though you are attending a live class.

Because of all these reasons, you will not only obtain the DP 700 certification, but you will also become a professional Fabric developer. This will help you outperform in interviews and land your dream roles.

If you want to obtain DP 700 certification along with strong hands-on skills, I am ready to kickstart our first lecture and see you there.

# **B) What is Data Engineering?**

So, I know now that you are going to become a Fabric Data Engineer. And I know that data engineering is one of the most sought-after roles right now. The industry is booming, but do you know the reason behind this surge in demand? Why is everyone so eager to become a data engineer, and why is Fabric considered the most in-demand technology? Let’s break it down.

The first thing you need to understand is what data engineering actually is—something that no one really tells you. Before becoming a data engineer, you should know the core purpose and scope of data engineering. People are going crazy about data engineers because organizations are struggling to handle the massive amounts of data being generated every day.

Data engineering can be divided into multiple phases. Phase number one is data generation. As the name suggests, data is being generated at an incredibly high rate. Everything around us—watching videos, scrolling on social media, purchasing items online—creates data. Every click, view, and transaction is contributing to this data explosion. Businesses also generate huge amounts of data through website traffic, purchases, and interactions.

Here’s a crazy fact: 90% of the data that exists in the world today has been generated in the last three to four years. Despite having internet access for over two decades, the pace of data generation has exploded recently. And the next five years will only accelerate this trend, which is why organizations are going crazy to hire data engineers.

Data comes in multiple forms: videos, images, structured data in tables, semi-structured formats like JSON or CSV, and data from APIs. With this variety and volume, there is no standard format. Without organization, this data is essentially garbage because it lacks relationships, structure, and actionable insights.

This leads us to the second phase of data engineering: data serving. Generated data must be processed and curated before being served to business stakeholders, leaders, and CEOs. Without standardization, decision-makers are confused and cannot make data-driven decisions. Data analysts, data scientists, and machine learning engineers all depend on curated data to perform their tasks.

The solution is the data model. This model can be relational, dimensional, or of any other format. It transforms raw data into a structured form that can be used to make business decisions. And who creates this data model? That’s right—you, the data engineer. You process the raw data and turn it into structured, actionable insights for everyone in the organization.

To illustrate this with a real-life analogy: imagine having a lot of raw vegetables like tomatoes, onions, and cucumbers. If you or your friends are hungry, eating these raw vegetables is equivalent to using raw data—it’s not ideal. A data engineer behaves like a chef, taking raw ingredients, processing them—cooking, boiling, or frying—and serving them as a finished dish. This ensures that the data is consumable and valuable.

Now you understand why companies are going mad after data engineers. They have so much raw data (vegetables), but they need skilled professionals (chefs) to process and prepare it in a usable form. This is the essence of data engineering.

To summarize, the three major pillars of data engineering are:

Data Generation – Understanding how data is created and collected.

Data Processing – Transforming raw data into usable formats.

Data Serving – Creating data models and structured outputs for decision-making.

And this is just one aspect of a data engineer’s role. There is so much more beyond creating data models. That’s why this course is designed not only to help you crack the DP 700 certification—the most in-demand certification right now—but also to provide strong hands-on experience, making you a professional Fabric developer.

In this course, we will cover all fundamentals, concepts, and practical exercises in depth. You will gain real-world insights, amazing examples, and practical scenarios that will make learning exciting. By the end, you will have both the certification and the hands-on skills to excel as a Fabric Data Engineer.

Now that you understand what data engineering is, let’s dive into the next chapter and continue our journey.

# **C) Evolution of Data Engineering**

In this chapter, we will talk about the evolution of data engineering, because I personally feel that it forms the base of everything we are doing today. Understanding why and how data engineering evolved will help you align with modern-day solutions, and it will explain why cloud data engineering has become so important and why cloud technologies are so popular nowadays.

Let’s go back in time, to the 1980s, when data engineering officially started. At that time, the primary approach to managing data was through data warehouses. Data warehouses were the proven way to model data so that it could be effectively used by data analysts, machine learning engineers, and other business stakeholders. Even today, data warehouses remain widely used, which shows their power and reliability.

A quick question: what kind of data model did we build in data warehouses? The answer is dimensional data models, which store data in the form of facts and dimensions. This model was highly performant, enabling accurate reporting and analysis. Everything was efficient—data modeling, reporting, and overall performance were top-notch.

If everything was working so well, then why did data engineering evolve? The reason lies in the rise of big data. As organizations began generating more data, traditional systems faced new challenges, summarized as the three V’s of big data: volume, velocity, and variety.

The first V is volume. Data was being generated in massive amounts, and traditional data warehouses could not handle such large volumes efficiently. Even if they could, the cost of storing structured data in SQL tables was extremely high.

The second V is velocity, which refers to the speed at which data was generated. Data volumes increased rapidly, moving from just a few records per second in the 1980s to thousands or even tens of thousands of records per second. Traditional data warehouses struggled to process data at such high speed.

The third V is variety, which is arguably the most important. Traditional data warehouses could only handle structured data. But as semi-structured data (like JSON or CSV files) and unstructured data (like images and videos) became more common, data warehouses could not accommodate these new types of data.

The solution to these challenges was the Data Lake, introduced in the early 2000s. Data Lakes revolutionized data engineering by addressing all three V’s. They allowed organizations to store massive volumes of data at a low cost, handle high-speed data ingestion, and store all types of data—structured, semi-structured, and unstructured. Data Lakes were a game-changer, and organizations were thrilled with this new solution.

However, over time, an unexpected limitation of Data Lakes emerged. The two primary consumers of data—data analysts and data scientists—experienced different outcomes. Data scientists were happy because they could directly use raw data for machine learning, without worrying about visualizations or reporting. But data analysts faced challenges. Reports generated from Data Lakes were less performant compared to data warehouses, especially when performing joins or building relationships between tables. This performance degradation created problems for reporting and analytics.

To address these limitations, a new solution emerged: the Lakehouse. The Lakehouse combines the benefits of both Data Lakes and Data Warehouses. It provides the scalability and flexibility of a Data Lake while maintaining the high performance required for analytics and reporting. This revolutionary approach solved the problems that existed in both Data Lakes and traditional Data Warehouses, creating the modern foundation for data engineering.

# **D) What is Lakehouse?**

Now let’s talk about the Lakehouse. The term “Lakehouse” is a combination of two words: Data Lake and Data Warehouse. Essentially, when we merge a data lake with a data warehouse, we get a Lakehouse. This is the simplest way to define it.

To understand the concept, let’s revisit our experience with Data Lakes. We were happy with Data Lakes because they could handle multiple file formats and store data at a low cost. However, in the modern approach called Lakehouse, which is considered the modern data warehouse or a modern way to model data for data engineering, we take this concept further.

In a Lakehouse, we continue to use the Data Lake but add data warehouse capabilities on top of it. This addition addresses the concerns of data analysts and report builders who previously complained about poor report performance in Data Lakes. By adding a warehouse layer, reports become faster, and building them becomes easier. Theoretically, the concept is simple: Data Lake + Data Warehouse = Lakehouse.

But how does this work in real life? After all, Data Lakes and Data Warehouses are different entities. Data Lakes are typically cloud storage solutions like Azure Data Lake, AWS S3, or Google Cloud Storage, while Data Warehouses are structured SQL databases. The key to combining them is Delta Lake.

When we add Delta Lake on top of a Data Lake, it introduces data warehousing capabilities. Delta Lake allows us to merge the flexibility of a Data Lake with the structured capabilities of a data warehouse. This is achieved through Delta Logs, which are a game-changer. Delta Logs provide features like data versioning, time travel, rollback capabilities, access controls such as grant and revoke, and all other functionalities of a traditional data warehouse. This is why Delta Lake is revolutionary in the world of data engineering.

Fabric, Microsoft’s modern data platform, is built entirely on the Lakehouse concept. Understanding Delta Lake is crucial because it forms the foundation of how Fabric works. By mastering Delta Lake, you will already have the fundamentals in place when building end-to-end solutions in Fabric. Delta Lake is relatively new in the market, and resources are limited, but with guided learning, you can understand it fully.

The popularity of the Lakehouse stems from its ability to solve multiple problems: it addresses the three V’s of big data—volume, velocity, and variety—and resolves the reporting challenges that existed with Data Lakes due to lack of data modeling capabilities. In short, the Lakehouse is the combination of Delta Lake (data warehouse layer) and the underlying Data Lake, and without Delta Lake, a Lakehouse cannot exist.

With this understanding of the evolution of data engineering and the Lakehouse, the next step is to create an Azure account. Azure is the platform where we will build Fabric solutions, so it’s important to understand some fundamentals and data services in Azure. Once the Azure account is ready, you will have the base knowledge required to start working with Fabric and begin building end-to-end solutions.

So let’s get started by creating a free Azure account, after which we’ll go through a quick overview of Azure and the key data services used in Fabric. This will ensure your foundation is strong before diving into practical Fabric solutions.

# **E) Medallion Architecture Explained!**

Now let’s talk about a very popular architecture in modern data engineering, especially in cloud data engineering, known as the Medallion Architecture. This architecture is widely used because of its simplicity and effectiveness, and I’ll explain why it is called “medallion” in a moment.

Before diving into the details of the medallions, it’s important to understand the basic flow of this architecture. There are three major stages or layers in the medallion approach. The first stage is called the Raw Zone. The Raw Zone is also referred to as the Bronze Layer. In this layer, every unit of data is copied and ingested exactly as it is, without any transformations or changes. This approach ensures that the original data is preserved and can always be referred back to if needed.

Once the data lands in the Bronze Layer, we move on to the second stage, called the Enriched Layer or the Silver Layer. In this layer, major transformations are applied to the data. These transformations may include deduplication, adding additional columns, cleaning columns, and removing nulls. The objective is to create enriched and structured entities that are more usable for downstream processes. This is why it is referred to as the enriched or Silver Layer.

The third and final stage is the Curated Layer, also called the Gold Layer. This layer contains the cleanest and most refined data, ready to be served to end users. The Gold Layer is designed for data consumption by various stakeholders such as data analysts, data scientists, business analysts, and managers. The data here is fully curated, meaning it is structured, validated, and ready to generate insights.

One key principle of the Medallion Architecture is that data becomes progressively cleaner as it moves from one layer to the next—from Bronze to Silver to Gold. While providing access to the Gold Layer is a common practice, it is not a strict rule; different organizations may have variations in how they allow access.

In summary, the Medallion Architecture is a structured way to organize and process data in multiple layers—Bronze (raw), Silver (enriched), and Gold (curated). Its popularity comes from its simplicity, clarity, and the fact that it ensures clean, structured, and consumable data for all stakeholders. It’s not a complex architecture; it’s essentially a logical renaming of the layers to reflect the progression of data quality.

# **F) Delta Lake - Hot Topic!**

Now let’s try to understand Delta Lake, especially in the context of Lakehouse architecture. But let me clarify upfront—Delta Lake is independent of any tool, technology, or cloud. It’s a core concept that enables Lakehouse, and understanding it will help you grasp modern data engineering workflows.

At its core, Delta Lake is simple. Imagine you have a data source, which can be anything—an API, a database, or any other data provider. You want to ingest data from this source into a destination folder. Typically, you would store this data in Parquet format, which is a columnar file format. Columnar formats store data column by column, unlike row-based formats that store data row by row. For big data, columnar formats are always preferred, and Parquet is currently the best choice.

Now, let’s consider a scenario:

Day 1: You ingest a file called raw_data_day1.parquet.

Day 2: Another Parquet file arrives.

Day 3: Yet another file comes in.

So far, you are simply storing files in Parquet format. This is a normal approach.

The magic happens when you decide to save your data in Delta format instead of plain Parquet.

When you save in Delta format, here’s what changes:

You still have your Parquet files, but now a new folder called _delta_log is created.

This Delta Log is a transactional log that keeps track of all files, their schemas, and all operations performed on the data.

Why is this important?

In Parquet files, the schema is stored at the footer of each file. So if you have thousands of files, the query engine must read all footers to understand the schema.

With Delta Lake, the transaction log stores the schema centrally, making schema management far easier and faster.

Every day, when new files arrive, logs for these files are saved in the Delta Log. This log is essentially a set of JSON files that record every DML operation (insert, update, delete) on the data folder. For example:

Day 1 → 000.json

Day 2 → 001.json

Day 3 → 002.json

This enables powerful capabilities for your data:

ACID Transactions: Delta Log ensures Atomicity, Consistency, Isolation, and Durability, which are essential for building reliable data warehouses.

Data Versioning & Time Travel: Each day’s data ingestion creates a new version of the table. You can easily travel back in time to any previous version to restore data or undo changes.

Optimization & Indexing: While Delta Lake does not have direct indexing, it provides indirect indexing through optimization techniques like Z-Ordering, OPTIMIZE commands, and write optimization, which greatly improve query performance.

So in essence, Delta Lake is just Parquet files with an added Delta Log that enables data warehousing features like transactions, versioning, time travel, and performance optimization.

Important note: Delta Lake only works with Parquet files. You cannot combine Delta Log with other formats like CSV.

In conclusion, Delta Lake is the game-changing component of Lakehouse architecture. It adds reliability, performance, and advanced features to simple columnar storage, bridging the gap between traditional data warehouses and modern data lakes.

# **G) Azure Free Account**

In order to create your free Azure account, the steps are very simple. Let me guide you through the process, and you’ll see it’s easy. First, open your browser and go to Google. Search for “Azure Free Account” and hit enter. You’ll land on the web page with multiple links; I recommend clicking on the official one. This will take you to the main page where you can create your free Azure account.

On this page, you will notice two options. This step is important: if you want to create a free Azure account, select “Try Azure for free”. The other option is Pay-as-you-go, which is a paid account. While the pay-as-you-go option is good for using all Azure services, it’s not necessary when starting out. The free tier provides $200 credit for 30 days, so there’s no need to spend money initially. Simply click on the free option.

Next, you need to provide a Microsoft email account. If you already have one, you can use it. A Microsoft account can be an Outlook account, or sometimes people convert their Gmail account into a Microsoft account. If you don’t have a Microsoft account, don’t worry—just click “Create one”. You’ll then land on a page to set up your account. You can use any email address (Gmail, Yahoo, etc.) or choose to get a new email address through Outlook.com. Personally, I created my account using Outlook.com.

A word of caution: sometimes Microsoft may test your credibility to ensure you’re not a robot. This can be frustrating on a computer. I recommend creating the Outlook account on a mobile phone instead, either through the Outlook app or the Outlook web page. Once your account is ready, return to the Azure signup page and enter your email. This is the simplest and most reliable way to create your account without issues.

After entering your email, you’ll see a page indicating that you receive $200 credit for 30 days. Even though you probably won’t use much of it, it’s a great way to explore Azure services. After 30 days, the paid services will be nullified unless you choose to upgrade, but any services that are free for 12 months will remain available. So there’s no need to worry about charges—Azure is effectively free with this approach.

Next, fill in your personal details and click the Sign Up button. Once completed, check all required boxes and click Next. You’ll be asked to provide verification using a credit or debit card. This is a temporary authorization for verification purposes only; you will not be charged unless you opt for Pay-as-you-go. Once verified, you’ll be prompted to enable multi-factor authentication and provide an alternate email address. After completing these steps, your account is ready.

You can now access the Azure Portal either by clicking the link provided or by going to portal.azure.com
. Once logged in, you’ll see the Azure dashboard. Here, the popular services are highlighted, though your view may differ slightly. This overview will focus on Azure features that are relevant to Fabric, so you won’t need to explore every detail.

Let’s go through the key components of the portal. First, there’s the Dashboard, which allows you to organize your Azure services like VMs, storage accounts, SQL databases, and other resources. Note that this dashboard is for organizing services, not for building reports. Next, we have All Resources and Resource Groups. In Azure terminology, all the services you use are called resources—for example, virtual machines, app services, storage accounts, SQL databases, and Cosmos DB. These resources are organized into folders called resource groups, which act as project-level containers. In simple terms, services equal resources, and the folder that contains them equals a resource group.

You will also notice some popular services on the portal. These are highlighted for easy access and are often used in conjunction with Fabric. One of the most important areas in Azure is Microsoft Entra ID, which is directly relevant to Fabric. Fabric is part of the Azure ecosystem, and all user management, service principals, and accounts we create are managed at the Microsoft Entra ID level. Essentially, Microsoft Entra ID is the renamed version of Azure Active Directory, and this is where administrative and security management occurs.

Other useful portal features include Monitor, which allows you to track the health and performance of your resources, and Advisor, which provides AI-driven recommendations to optimize resources and scaling. Additionally, Cost Management + Billing helps monitor spending. With a free account, you don’t need to worry about costs during the first 30 days. Personally, I also use a paid account to access services beyond the free period and for tutorials, but the free account is sufficient for starting out. Finally, Help + Support allows you to raise tickets for assistance from Microsoft if needed.

In summary, this gives you a quick overview of Azure. It’s simple, and you don’t need to dive into all the services immediately. Our focus will be on Fabric, but having a clear understanding of these Azure fundamentals is essential because Fabric relies on these underlying services. In the next step, we will explore the popular Azure services that serve as a strong foundation for Fabric and understand their roles in the ecosystem.

# **H) Azure Fundamentals****

Now, first of all, let's try to understand what Microsoft Entra ID is. This is the most important part of a job that we need to use within Fabric because, while the rest of the components are also important, Entra ID is the backbone of user and resource management. If you are using Fabric in an organization, you will need access to many resources, and if your organization already has solutions built in Azure, you will need to understand what access is required to those resources.

Microsoft Entra ID covers all users—internal and external—as well as security groups and service principals. Let’s break this down. Security groups are used to manage access efficiently. For example, if you are a data engineer and there are 50 data engineers in your organization, instead of granting access individually to each user for a resource, you can create a security group containing all 50 users and grant access to the group. This way, everyone in the group gets access to the resource without the admin manually managing each user.

Service principals, on the other hand, are dummy accounts or “robot accounts” created for automated processes. For instance, if a data factory or any Azure resource needs access to data stored in Dataverse or another system, it can use a service principal instead of a personal account. This ensures continuity—if a user leaves the organization, credentials do not need to be reconfigured. The service principal acts as a secure, reusable identity for accessing resources.

In summary, Microsoft Entra ID plays a critical role in performing all admin activities for both Azure and Fabric. While Fabric has its own admin tasks, the basis of all admin operations is managed via Entra ID.

To explore practically, open your Azure portal, search for Entra ID, and click on it. On the overview tab, you can see tenant information, your primary domain (usually your email), and licenses. You can manage users, groups, roles, enterprise applications, and app registrations for creating service principals. Properties provide personal account information, while monitoring lets you access audit logs and log analytics.

For users, you can create new users or invite external users. The tenant domain will automatically assign the domain name. Groups allow you to create security groups, add members, and manage access efficiently. App registrations enable the creation of service principals, including secrets for credentials.

Next, let’s discuss the hierarchical structure in Azure. At the top, you have the tenant account, which is the owner of the Azure platform. Under the tenant, there are subscriptions, which are necessary to isolate billing for different business units, like HR, IT, marketing, etc. Within subscriptions, resources are organized into resource groups, which act as folders to hold individual Azure services. Each service must belong to a resource group to be created and managed. This hierarchical structure keeps everything organized and isolated.

Now, some popular Azure data services aligned with Fabric include Azure Data Lake Storage Gen2 (ADLS Gen2), Azure Data Factory, Azure Databricks, Azure Synapse Analytics, RBAC, Event Hubs, and Stream Analytics.

Azure Data Lake Storage Gen2 is the storage solution for structured, semi-structured, and unstructured data. It is built on top of blob storage, with hierarchical namespaces enabled to create folder-like structures, essentially forming a data lake.

Azure Data Factory (ADF) is a low-code ETL/ELT tool that allows data movement, transformation, monitoring, and triggering pipelines. It is highly scalable, user-friendly, and will be replaced by Fabric Data Factory in the future.

Azure Databricks simplifies working with Apache Spark by managing clusters automatically. It provides an interactive notebook environment for distributed computing without the complexity of manual cluster management. Fabric provides its own Spark management layer as an alternative.

Azure Synapse Analytics is a data warehousing solution with dedicated SQL pools (traditional, database-oriented) and serverless SQL pools (modern, lake-centric architecture). Serverless SQL pools automatically scale and store data in data lakes using Delta Lake, forming a lakehouse architecture. Fabric Data Warehouse now replaces traditional dedicated SQL pools with lake-centric capabilities.

RBAC (Role-Based Access Control) provides fine-grained access control at file, folder, and container levels. It is crucial for granting access in both Azure and Fabric. Knowledge of RBAC can distinguish an experienced professional in interviews.

Azure Event Hubs is a managed real-time data ingestion service, similar to Kafka, which temporarily stores streaming data as events and makes it available to consumers like Data Lake, Stream Analytics, or Databricks.

Azure Stream Analytics processes streaming data from Event Hubs, performing transformations and storing results in Data Lake, Blob Storage, or Synapse Analytics. This allows near real-time analytics without writing code.

These fundamentals cover all the key Azure services you need to know to effectively work with Fabric. You do not need to master every detail; understanding these services, their alternatives, and their role in data processing is sufficient. With this foundation, you are ready to start working with Fabric.
