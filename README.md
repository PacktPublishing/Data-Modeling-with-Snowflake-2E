
# Data Modeling with Snowflake, Second Edition

<a href="https://www.packtpub.com/product/data-modeling-with-snowflake/9781837634453"><img src="https://content.packt.com/_/image/original/B32134/cover_image.jpg?version=1756797323" alt="Data Modeling with Snowflake" height="256px" align="right"></a>

This is the code repository for [Data Modeling with Snowflake, Second Edition](https://www.packtpub.com/product/data-modeling-with-snowflake/9781837028030), published by Packt.

**A practical guide to accelerating Snowflake development using universal modeling techniques**

## What is this book about?
Struggling with rising Snowflake costs and constant tuning? Poorly aligned data models can lead to bloated expenses, inefficient queries, and time-consuming rework. Data Modeling with Snowflake helps you harness the Snowflake Data Cloud’s scalable, cloud-native architecture and expansive feature set to deliver data solutions faster than ever.
This book introduces simple, practical data modeling frameworks that accelerate agile design and evolve alongside your projects from concept to code. Rooted in decades of proven database design principles, these frameworks are paired, for the first time, with Snowflake-native objects and real-world examples, offering a two-in-one crash course in theory and direct application.
Through real-world examples designed to make learning easy, you’ll leverage Snowflake’s innovative features like Time Travel, Zero-Copy Cloning, and Change Data Capture (CDC) to create cost-efficient solutions. Whether you're just starting out or refining your architecture, this book will guide you in designing smarter, scaling faster, and cutting costs by aligning timeless modeling principles with the power of Snowflake.

This book covers the following exciting features: 
* Master data modeling fundamentals to get your designs right on the first attempt with time-saving benefits
* Discover Snowflake’s cloud-native architecture and unique features
* Apply modeling concepts to achieve higher efficiency by leveraging Snowflake architecture
* Get to grips with modeling concepts like normalization and slowly changing dimensions (SCDs)
* Read and transform semi-structured data, including hierarchies, using pre-built recipes and examples
* Explore organizational frameworks like Data Vault and Data Mesh
* Understand the business metrics that drive scalable, cost-effective data projects

If you feel this book is for you, get your [copy](https://www.amazon.com/Data-Modeling-Snowflake-accelerating-development/dp/1837028036/) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
-- Query the change tracking metadata to observe
-- only inserts from the timestamp till now
select * from myTable
changes(information => append_only)
at(timestamp => $cDts);
```

**Following is what you need for this book:**
This book is for developers working with SQL who are looking to build a strong foundation in modeling best practices and gain an understanding of where they can be effectively applied to save time and effort. Whether you’re an ace in SQL logic or starting out in database design, this book will equip you with the practical foundations of data modeling to guide you on your data journey with Snowflake. Developers who’ve recently discovered Snowflake will be able to uncover its core features and learn to incorporate them into universal modeling frameworks.	

With the following software and hardware list you can run all code files present in the book (Chapter 1-19).

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  1-19		  |   		Snowflake Data Cloud   | Windows, Mac OS X, and Linux (Any) |
| 1-19         |   			SQL																		  |        Windows, Mac OS X, and Linux (Any)                             |


### Related products <Other books you may enjoy>
* The Ultimate Guide to Snowpark [[Packt]](https://www.packtpub.com/en-in/product/the-ultimate-guide-to-snowpark-9781805124450) [[Amazon]](https://www.amazon.com/Ultimate-Guide-Snowpark-efficient-workloads/dp/1805123416/)

* Data Engineering with dbt [[Packt]](https://www.packtpub.com/en-in/product/data-engineering-with-dbt-9781803241883) [[Amazon]](https://www.amazon.com/Data-Engineering-dbt-cloud-based-dependable/dp/1803246286/)

## Get to Know the Author
**Serge Gershkovich** is a data architect with an extensive background in designing and maintaining enterprise-scale data warehouse platforms and reporting solutions.
After a decade of working with the SAP ecosystem, Serge discovered Snowflake and never looked back. His passion for the Data Cloud has led to his creating educational content and being named a Snowflake Data Superhero. Serge is currently engaged as a developer advocate at SqlDBM, an online database modeling tool.
Serge holds a B.Sc. degree in Information Systems from SUNY Stony Brook. Originally from Ukraine, he was raised in New York and has lived in London and Madrid.
He currently resides in Palma de Mallorca with his wife and son.


