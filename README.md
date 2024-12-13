Material for Data Products in a Data Engineering perspective
============================================================

# Table of Content (ToC)
* [Overview](#overview)
* [References](#references)
* [Data Products specifications](#data-products-specifications)
* [Books](#books)
  * [Data Products for all ages](#data-products-for-all-ages)
* [Articles](#articles)
  * [𝐇𝐨𝐰 𝐃𝐨 𝐘𝐨𝐮 𝐌𝐚𝐧𝐚𝐠𝐞 𝐃𝐚𝐭𝐚 𝐏𝐫𝐨𝐝𝐮𝐜𝐭𝐬?](#𝐇𝐨𝐰-𝐃𝐨-𝐘𝐨𝐮-𝐌𝐚𝐧𝐚𝐠𝐞-𝐃𝐚𝐭𝐚-𝐏𝐫𝐨𝐝𝐮𝐜𝐭𝐬)
  * [The Data Product Ecosystem: Core, Analytic, and Data Science Products](#the-data-product-ecosystem-core-analytic-and-data-science-products)
  * [Adopting a product mindset](#adopting-a-product-mindset)
  * [6 Essential Lessons for Building Great Data Products](#6-essential-lessons-for-building-great-data-products)
  * [The state of Data Products](#the-state-of-data-products)
  * [How To Build a Data Product with Databricks](#how-to-build-a-data-product-with-databricks)
  * [Data Pipelines for Data Products](#data-pipelines-for-data-products)
  * [How to Grow Product\-Minded Engineering Teams](#how-to-grow-product-minded-engineering-teams)
  * [A good engineer thinks like a product manager](#a-good-engineer-thinks-like-a-product-manager)
* [Frameworks](#frameworks)
  * [Data Mesh Manager](#data-mesh-manager)
  * [Data Product Portal](#data-product-portal)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

# Overview
[This project](https://github.com/data-engineering-helpers/data-products)
intends to document requirements and referential material to implement
data contracts in the perspective of data engineering on a
modern data stack (MDS).

Data contracts are essential to decouple data producers from data consumers,
while having both parties taking responsibility for their respective parts.

Even though the members of the GitHub organization may be employed by
some companies, they speak on their personal behalf and do not represent
these companies.

# References
* [Material for Data platform - Data products (this repository)](https://github.com/data-engineering-helpers/data-contracts)
* [Material for Data platform - Data quality](https://github.com/data-engineering-helpers/data-quality)
* [Material for Data platform - Data contracts](https://github.com/data-engineering-helpers/data-contracts)
* [Architecture principles for data engineering pipelines on the Modern Data Stack (MDS)](https://github.com/data-engineering-helpers/architecture-principles)
  * [Material for the Data platform - Architecture principles](https://github.com/data-engineering-helpers/architecture-principles/blob/main/material/README.md)
  * [Material for the Data platform - Modern Data Stack (MDS) in a box](https://github.com/data-engineering-helpers/mds-in-a-box/blob/main/README.md)
  * [Material for the Data platform - Data-lakes, data warehouses, data lake-houses](https://github.com/data-engineering-helpers/data-lakehouse)
  * [Material for the Data platform - Metadata](https://github.com/data-engineering-helpers/metadata/blob/main/README.md)
* Specifications/principles for a
  [data engineering pipeline deployment tool](https://github.com/data-engineering-helpers/data-pipeline-deployment)

# Data Products specifications
* Linux Foundation's Open Data Product Specification (ODPS): https://opendataproducts.org/
* Innoq's specification for Data Products: https://dataproduct-specification.com/
* Open Data Contract Specification (ODCS)
  * Reader-friendly, dedicated site: https://bitol-io.github.io/open-data-contract-standard/latest/
  * GitHub home page: https://github.com/bitol-io/open-data-contract-standard
* Innoq's Data Contract specification: https://datacontract.com/

# Books

## Data Products for all ages
* Title: Data Products for all ages
* Author: Jean-Georges Perrin
  ([Jean-Georges Perrin on LinkedIn](https://www.linkedin.com/in/jgperrin/))
* Available on Amazon: https://www.amazon.fr/dp/B0DPL3MCWJ
* ASIN: ‎ B0DPL3MCWJ
* ISBN-13: ‎ 979-8341255999
* Number of pages:‎ 36

# Articles

## 𝐇𝐨𝐰 𝐃𝐨 𝐘𝐨𝐮 𝐌𝐚𝐧𝐚𝐠𝐞 𝐃𝐚𝐭𝐚 𝐏𝐫𝐨𝐝𝐮𝐜𝐭𝐬?
* Title: 𝐃𝐚𝐭𝐚 𝐏𝐫𝐨𝐝𝐮𝐜𝐭𝐬 𝐖𝐢𝐥𝐥 𝐁𝐞 𝐭𝐡𝐞 𝐇𝐨𝐭 𝐓𝐨𝐩𝐢𝐜 𝐨𝐟 𝟐𝟎𝟐𝟓, 𝐁𝐮𝐭 𝐇𝐨𝐰 𝐃𝐨 𝐘𝐨𝐮 𝐌𝐚𝐧𝐚𝐠𝐞 𝐓𝐡𝐞𝐦?
* Author: Fouad Talaouit
  ([Fouad Talaouit on LinkedIn](https://www.linkedin.com/in/fouadtalaouit/))
* Date: Dec. 2024
* Link to the post:
  https://www.linkedin.com/posts/fouadtalaouit_dataproducts-datamanagement-datamesh-activity-7273218047044194305-2wC-/

## The Data Product Ecosystem: Core, Analytic, and Data Science Products
* Title: The Data Product Ecosystem: Core, Analytic, and Data Science Products
* Author: Fouad Talaouit
  ([Fouad Talaouit on LinkedIn](https://www.linkedin.com/in/fouadtalaouit/))
* Date: Dec. 2024
* Link to the article:
  https://www.linkedin.com/pulse/data-product-ecosystem-core-analytic-science-products-talaouit--iwr0e/

## Adopting a product mindset
* Title: Adopting a product mindset
* Author: Andrew Jones
  ([Andrew Jones on LinkedIn](https://www.linkedin.com/in/andrewrhysjones/))
* Date: Dec. 2024
* Link to the article:
  https://andrew-jones.com/newsletter/2024-12-06-adopting-a-product-mindset/

## 6 Essential Lessons for Building Great Data Products
* Title: 6 Essential Lessons for Building Great Data Products
* Author: Dr Sven Balnojan
  ([Dr Sven Balnojan on LinkedIn](https://www.linkedin.com/in/dr-sven-balnojan-a55b4072/),
  [Dr Sven Balnojan on Substack](https://substack.com/@finishslime))
* Date: Dec. 2024
* Link to the article:
  https://www.thdpth.com/p/6-essential-lessons-for-building
* Publisher: Substack

## The state of Data Products
* Title: The state of Data Products
* Date: July 2024
* Author: Wannes Rosiers
  ([Wannes Rosiers on LinkedIn](https://www.linkedin.com/in/wannes-rosiers/),
  [Wannes Rosiers on Medium](https://medium.com/@wannesrosiers))
* Link to the article on Medium:
  https://medium.com/conveyordata/the-state-of-data-products-9e1bc5c39bcb

## How To Build a Data Product with Databricks
* Title: How To Build a Data Product with Databricks
* Author: Jochen Christ
  ([Jochen Christ on LinkedIn](https://www.linkedin.com/in/jochenchrist/),
  [Jochen Christ on GitHub](https://github.com/jochenchrist))
* Date: Apr. 2024
* Link to the article:
  https://www.datamesh-architecture.com/howto/build-a-dataproduct-with-databricks
* Associated GitHub repository (with source code):
  https://github.com/datamesh-architecture/databricks-dataproduct-example

## Data Pipelines for Data Products
* Title: Data Pipelines for Data Products
* Author: Bruno Gonzales
  ([Bruno Gonzales on LinkedIn](https://www.linkedin.com/in/brunouy/),
  [Bruno Gonzales on Substack](https://substack.com/@dataqualityguru))  
* Date: Oct. 2023
* Publisher: Modern Data 101 on Substack
* Link to the article:
  https://moderndata101.substack.com/p/data-pipelines-for-data-products

## How to Grow Product-Minded Engineering Teams
* Title: How to Grow Product-Minded Engineering Teams
* Author: Nicola Ballotta
  ([Nicola Ballotta on LinkedIn](https://www.linkedin.com/in/nicolaballotta/),
  [Nicola Ballotta on Substack](https://substack.com/@hybridhacker))
* Date: Jan. 2024
* Link to the article:
  https://hybridhacker.email/p/how-to-grow-product-minded-engineering

## A good engineer thinks like a product manager
* Title: A good engineer thinks like a product manager
* Author: Gregor Ojstersek
  ([Gregor Ojstersek on LinkedIn](https://www.linkedin.com/in/gregorojstersek/),
  [Gregor Ojstersek on Substack](https://substack.com/@gregorojstersek))
* Date: Nov. 2023
* Link to the article:
  https://newsletter.eng-leadership.com/p/a-good-engineer-thinks-like-a-product

# Frameworks

## Data Mesh Manager
* Home page: https://datamesh-manager.com/
* Free demo: https://demo.datamesh-manager.com/
* Main company behind: [InnoQ](https://www.linkedin.com/company/innoq)
* Overview: Manage data products, agree on data contracts, and automate data governance. Get an enterprise data marketplace.

## Data Product Portal
* GitHub page: https://github.com/conveyordata/data-product-portal
* License: Apache License 2.0
* Overview:
  * The Data Product Portal enables to scale building data products across all departments in an organisation in a self-service manner.
    It does so by providing a guided setup for creating data products, with proper approval processes that will enable governance by design for data initiatives.
    The portal is a process tool that helps data professionals do their work more efficiently while providing governance and insights into how data is being used throughout the organisation.
  * Unlike traditional data catalogs that primarily focus on describing data, the Data Product Portal guides you through the entire data product development lifecycle.
    This includes self-service and secure access to tools, data platforms, data sources, and sharing concepts, ensuring control and oversight for business stakeholders.
  * Our goal is to bridge the gap between data governance, data platforms and data catalogs and provide a 360 view of all ongoing data initiatives that is easy to understand by everybody.
  * To read more about it, please checkout our
    [announcement blogpost](https://conveyordata.com/portal-introducing-new-open-source-data-product-portal?utm_source=github-portal-readme&utm_medium=referral)
