Material for Data Products in a Data Engineering perspective
============================================================

# Table of Content (ToC)
* [Overview](#overview)
  * [Other repositories of Data Engineering helpers](#other-repositories-of-data-engineering-helpers)
* [Data product specifications](#data-product-specifications)
* [Data contract specifications](#data-contract-specifications)
* [Books](#books)
  * [Data Products for all ages](#data-products-for-all-ages)
* [Articles](#articles)
  * [The Data Product Testing Strategy: Handbook](#the-data-product-testing-strategy-handbook)
  * [Building Data Fabric starting from Data Products](#building-data-fabric-starting-from-data-products)
  * [The data mesh challenge](#the-data-mesh-challenge)
  * [Data Products, Platform and Where to Close the Gaps](#data-products-platform-and-where-to-close-the-gaps)
  * [What is a data marketplace, and do you need one?](#what-is-a-data-marketplace)
  * [Rethinking the Medallion Architecture](#rethinking-the-medallion-architecture)
  * [The data mesh challenge](#the-data-mesh-challenge)
  * [Rethinking the Medallion Architecture](#rethinking-the-medallion-architecture)
  * [From Data Catalog to Data Marketplace](#from-data-catalog-to-data-marketplace)
  * [Designing data products](#designing-data-products)
  * [Exploring the Integration of OpenLineage with ODPS](#exploring-the-integration-of-openlineage-with-odps)
  * [How Do You Manage Data Products?](#how-do-you-manage-data-products)
  * [The Data Product Ecosystem: Core, Analytic, and Data Science Products](#the-data-product-ecosystem-core-analytic-and-data-science-products)
  * [Adopting a product mindset](#adopting-a-product-mindset)
  * [6 Essential Lessons for Building Great Data Products](#6-essential-lessons-for-building-great-data-products)
  * [The data product marketplace](#the-data-product-marketplace)
  * [The Data Product Trap](#the-data-product-trap)
  * [Where Exactly Data Becomes Product](#where-exactly-data-becomes-product)
  * [The state of Data Products](#the-state-of-data-products)
  * [Data-as-a-Product and Data-Contract](#data-as-a-product-and-data-contract)
  * [How To Build a Data Product with Databricks](#how-to-build-a-data-product-with-databricks)
  * [How to Grow Product\-Minded Engineering Teams](#how-to-grow-product-minded-engineering-teams)
  * [A good engineer thinks like a product manager](#a-good-engineer-thinks-like-a-product-manager)
  * [Data Pipelines for Data Products](#data-pipelines-for-data-products)
* [Frameworks](#frameworks)
  * [Data Marketplace](#data-marketplace)
  * [Data Mesh Architecture \- Data product canvas](#data-mesh-architecture---data-product-canvas)
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

## Other repositories of Data Engineering helpers
* [Data Engineering Helpers - Knowledge Sharing - Data contracts](https://github.com/data-engineering-helpers/data-contracts)
* [Data Engineering Helpers - Knowledge Sharing - Data quality](https://github.com/data-engineering-helpers/data-quality)
* [Data Engineering Helpers - Knowledge Sharing - Architecture principles](https://github.com/data-engineering-helpers/architecture-principles)
* [Data Engineering Helpers - Knowledge Sharing - Data life cycle](https://github.com/data-engineering-helpers/data-life-cycle)
* [Data Engineering Helpers - Knowledge Sharing - Data management](https://github.com/data-engineering-helpers/data-management)
* [Data Engineering Helpers - Knowledge Sharing - Data lakehouse](https://github.com/data-engineering-helpers/data-lakehouse)
* [Data Engineering Helpers - Knowledge Sharing - Metadata](https://github.com/data-engineering-helpers/metadata)
* [Data Engineering Helpers - Knowledge Sharing - Data pipeline deployment](https://github.com/data-engineering-helpers/data-pipeline-deployment)
* [Data Engineering Helpers - Knowledge Sharing - Semantic layer](https://github.com/data-engineering-helpers/semantic-layer)

# Data product specifications
* Linux Foundation's Open Data Product Specification (ODPS): https://opendataproducts.org/
* Innoq's specification for Data Products: https://dataproduct-specification.com/
* Open Data Mesh (ODM)'s Data Product Descriptor Specification (DPDS): https://github.com/opendatamesh-initiative/odm-specification-dpdescriptor

# Data contract specifications
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

## The Data Product Testing Strategy: Handbook
* Title: The Data Product Testing Strategy: Handbook
* Date: Mar. 2025
* Authors: Manisha Jain, Animesh Kumar, Shubhanshu Jain, and Samadrita Ghosh
* Link to the article on Substack:
  https://moderndata101.substack.com/p/the-data-product-testing-strategy

## Building Data Fabric starting from Data Products
* Title: Building Data Fabric starting from Data Products
* Date: Jan. 2025
* Author: Paolo Platter
  ([Paolo Platter on LinkedIn](https://www.linkedin.com/in/paoloplatter/),
  [Paolo Platter on Medium](https://p-platter.medium.com/))
* Link to the article on Medium:
  https://medium.com/agile-lab-engineering/building-data-fabric-starting-from-data-products-00cd2bf0285b

## The data mesh challenge
* Title: The data mesh challenge: closing the gap between strategy and operation at scale
* Date: Jan. 2025
* Author: Zhamak Dehghani
  ([Zhamak Dehghani on LinkedIn](https://www.linkedin.com/in/zhamak-dehghani/),
  [Zhamak Dehghani on Nextdata contact page](https://www.nextdata.com/#contact))
* Link to the article on the Nextdata blog:
  https://www.nextdata.com/our-pov/the-data-mesh-challenge-how-to-close-the-gap-between-inception-and-operation-at-scale

## Data Products, Platform and Where to Close the Gaps
* Title: Speed-to-Value Funnel: Data Products + Platform and Where to Close the Gaps
* Date: Jan. 2025
* Author: Travis Thompson
  ([Travis Thompson on LinkedIn](https://www.linkedin.com/in/travis-w-thompson/))
* Link to the article on Substack:
  https://moderndata101.substack.com/p/speed-to-value-funnel-data-products

## What is a data marketplace
* Title: What is a data marketplace, and do you need one?
* Link to the post on LinkedIn:
  https://www.linkedin.com/posts/modern-data-101_a-data-marketplaces-positioning-ugcPost-7295784619419828225-h7ih
* Link to the article on ThoughtWorks:
  https://www.thoughtworks.com/insights/blog/data-mesh/boosting-data-product-adoption-with-an-exceptional-marketplace-experience

## End-to-End Guide to Building Data Products
* Title: End-to-End Guide to Building Data Products
* Dates: 2023-2025
* Authors: Modern Data 101
* Link to the series of articles: https://moderndata101.substack.com/p/end-to-end-guide-to-building-data
  * [Chapter 1 - The Data Product Strategy - Becoming Metrics-First](https://moderndata101.substack.com/p/the-data-product-strategy-becoming)
  * ...
  * [Chapter 14 - Building Data Platforms: The Mistake Organisations Make](https://moderndata101.substack.com/p/building-data-platforms-the-mistake)

## Rethinking the Medallion Architecture
* Title: The End of the Bronze Age: Rethinking the Medallion Architecture
* Authors:
  * Adam Bellemare
    ([Adam Bellemare on LinkedIn](https://www.linkedin.com/in/adambellemare/),
    [Adam Bellemare on InfoQ](https://www.infoq.com/profile/Adam-Bellemare/))
  * Thomas Betts
    ([Thomas Betts on LinkedIn](https://www.linkedin.com/in/thomasbetts/),
    [Thomas Betts on InfoQ](https://www.infoq.com/profile/Thomas-Betts/))
* Date: Feb. 2025
* Link to the article on InfoQ:
  https://www.infoq.com/articles/rethinking-medallion-architecture/

## Defining data products
* Title: Defining data products
* Author: Jean-George Perrin
* Date: Jan. 2025
* Link to the article: https://medium.com/data-mesh-learning/defining-data-products-a-community-effort-77363611e5c5

## The data mesh challenge
* Title: The data mesh challenge: closing the gap between strategy and operation at scale
* Author: Zhamak Dehghani
  ([Zhamak Dehghani on LinkedIn](https://www.linkedin.com/in/zhamak-dehghani),
  [Zhamak Dehghani on NextData](https://www.nextdata.com/company))
* Date: Jan. 2025
* Link to the post on LinkedIn: https://www.linkedin.com/feed/update/urn:li:activity:7290825660632076288/
* Link to the post on NextData blog:
  https://www.nextdata.com/our-pov/the-data-mesh-challenge-how-to-close-the-gap-between-inception-and-operation-at-scale

## Rethinking the Medallion Architecture
* Title: The End of the Bronze Age: Rethinking the Medallion Architecture
* Author: Adam Bellemare
  ([Adam Bellemare on LinkedIn](https://www.linkedin.com/in/adambellemare/),
  [Adam Bellemare on InfoQ](https://www.infoq.com/profile/Adam-Bellemare/))
* Editor: Thomas Betts
  ([Thomas Betts on LinkedIn](https://www.linkedin.com/in/thomasbetts/),
  [Thomas Betts on InfoQ](https://www.infoq.com/profile/Thomas-Betts/))
* Date: Jan. 2025
* Link to the article on InfoQ:
  https://www.infoq.com/articles/rethinking-medallion-architecture/
* Link to a post on LinkedIn by
  [Sean Falconer](https://www.linkedin.com/in/seanf/):
  https://www.linkedin.com/posts/seanf_weve-built-a-system-where-every-team-hacks-activity-7290740834822430721-IB5O

## From Data Catalog to Data Marketplace
* Title: From Data Catalog 📚 to Data Marketplace 🛒
* Author: Jochen Christ
  ([Jochen Christ on LinkedIn](https://www.linkedin.com/in/jochenchrist/))
* Date: Jan. 2025
* Link to the LinkedIn post:
  https://www.linkedin.com/posts/jochenchrist_datamarketplace-datamarketplace-dataproducts-activity-7281953125140246528-BExu/
* Link to the Data Mesh Manager blog post:
  https://datamesh-manager.com/learn/data-catalog-vs-data-marketplace

## Designing data products
* Title: Designing data products
* Date: Dec. 2024
* Author: Kiran Prakash
* Link to the article on Martin Flowler's blog:
  https://martinfowler.com/articles/designing-data-products.html

## Exploring the Integration of OpenLineage with ODPS
* Title: Exploring the Integration of OpenLineage with ODPS
* Author: Jarkko Moilanen
  ([Jarkko Moilanen on LinkedIn](https://www.linkedin.com/in/jarkkomoilanen/))
  * Jarkko Moilanen is one of the main maintainers of the Linux Foundation's Open Data Product Specification (ODPS)
* Date: Dec. 2024
* Link to the post:
  https://www.linkedin.com/posts/jarkkomoilanen_datalineage-openlineage-datagovernance-activity-7275156333790715905-t5-7/

## How Do You Manage Data Products?
* Title: Data Products Will Be the Hot Topic of 2025, But How Do You Manage Them?
* Author: Fouad Talaouit
  ([Fouad Talaouit on LinkedIn](https://www.linkedin.com/in/fouadtalaouit/))
* Date: Dec. 2024
* Link to the post on LinkedIn:
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

## The data product marketplace
* Title: The Data Product Marketplace: A Single Interface for Business
* Date: Ot. 2024
* Author: Arielle Rolland
  ([Arielle Rolland on LinkedIn](https://www.linkedin.com/in/arielle-rolland-458405106/),
  [Arielle Rolland on Substack](https://substack.com/@ariellerolland))
* Link to the article on Substack:
  https://moderndata101.substack.com/p/the-data-product-marketplace-a-single

## The Data Product Trap
* Title: The Data Product Trap
* Date: Oct. 2024
* Author: Paolo Platter
  ([Paolo Platter on LinkedIn](https://www.linkedin.com/in/paoloplatter/),
  [Paolo Platter on Medium](https://p-platter.medium.com/))
* Link to the article on Medium:
  https://medium.com/agile-lab-engineering/the-data-product-trap-e33bf8aeefa0

## Where Exactly Data Becomes Product
* Title: Where Exactly Data Becomes Product: Illustrated Guide to Data Products in Action
* Date: Aug. 2024
* Authors:
  * Animesh Kumar
  * Travis Thompson
    ([Travis Thompson on LinkedIn](https://www.linkedin.com/in/travis-w-thompson/))
* Link to the article on Substack:
  https://moderndata101.substack.com/p/where-exactly-data-becomes-product

## The state of Data Products
* Title: The state of Data Products
* Date: July 2024
* Author: Wannes Rosiers
  ([Wannes Rosiers on LinkedIn](https://www.linkedin.com/in/wannes-rosiers/),
  [Wannes Rosiers on Medium](https://medium.com/@wannesrosiers))
* Link to the article on Medium:
  https://medium.com/conveyordata/the-state-of-data-products-9e1bc5c39bcb

## Data-as-a-Product and Data-Contract: An evolutionary approach to data maturity
* Title: Data-as-a-Product and Data-Contract: An evolutionary approach to data maturity
* Date: Apr. 2024
* Author: Olivier Wulveryck
  ([Olivier Wulveryck on LinkedIn](https://www.linkedin.com/in/olivierwulveryck/))
* Link to the article on Olivier's blog:
  https://blog.owulveryck.info/2024/04/09/data-as-a-product-and-data-contract-an-evolutionary-approach-to-data-maturity.html

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

## Data Pipelines for Data Products
* Title: Data Pipelines for Data Products
* Author: Bruno Gonzales
  ([Bruno Gonzales on LinkedIn](https://www.linkedin.com/in/brunouy/),
  [Bruno Gonzales on Substack](https://substack.com/@dataqualityguru))  
* Date: Oct. 2023
* Publisher: Modern Data 101 on Substack
* Link to the article:
  https://moderndata101.substack.com/p/data-pipelines-for-data-products

# Frameworks

## Data Marketplace
* Article, by Charlotte Ledoux, Apr. 2025, on Substack:
  https://charlotteledoux.substack.com/p/scaling-data-governance-without-falling
* A “Data Product Marketplace”:
  * is a place where trusted, high-quality data is accessible and reusable across teams
  * is a platform that enables organizations to publish, discover, and exchange data assets
    in a structured and governed way
  * functions like an online store for data, where users can browse, request,
    and access data assets whether internally within a company or externally between organizations


## Data Mesh Architecture - Data product canvas
* Home page: https://www.datamesh-architecture.com/data-product-canvas

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
