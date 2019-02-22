# Data-Preparation-for-Data-Science-Using-SAS
Best practices how to prepare data for Data Science and Analytics, Tips/Tricks and Code Examples on how to implement this with SAS Software. Companion and Download Site for the SAS Press Book "Data Preparation for Analytics Using SAS" by Gerhard Svolba

[Link @SAS-Press](https://www.sas.com/store/prodBK_60502_en.html?storeCode=SAS_US&storeCode=SAS_US) [Link @amazon.com](https://www.amazon.com/Data-Preparation-Analytics-Using-Press-ebook/dp/B001UQ6X2C/ref=sr_1_1?keywords=data+preparation+for+analytics&qid=1550836793&s=gateway&sr=8-1)

[Paper Efficient “One-Row-per-Subject” Data Mart Construction
for Data Mining  @SAS Global Forum](http://www2.sas.com/proceedings/sugi31/078-31.pdf)

## The Structure and Use of This Book
This book has been written for Data Scientists, Statisticians, Analysts, SAS Users, and all people that are involved in the data preparation process for analytics. The goal of the book is to give practical advice in the form of SAS coding tips and tricks as well as conceptual background information on data structures and considerations from the business point of view.
This book will allow the reader to
* View analytic data preparation in light of its business environment and to consider the underlying business questions in data preparation
* Learn about data models and relevant analytic data structures such as the one-row-per-subject data mart, the multiple-rows-per-subject data mart, and the longitudinal data mart
* Use powerful SAS macros to change between the various data mart structures
* Consider the specifics of predictive modeling for data mart creation
* Learn how to create meaningful derived variables for all data mart types
* Illustrate how to create a one-row-per-subject data mart from various data sources and data structures
* Learn the concepts and considerations for data preparation for time series analysis
* Illustrate how scoring can be done with various SAS procedures and with SAS Enterprise Miner
* Learn about the power of SAS for analytic data preparation and the data mart requirements of various SAS procedures
* Benefit from many do’s and don’ts and from practical examples for data mart building

- [Book Excerpt](https://www.sas.com/storefront/aux/en/spdataprep/60502_excerpt.pdf)
- [Table of Contents](https://www.sas.com/storefront/aux/en/spdataprep/60502_toc.pdf)

## Overview of the Main Parts of the Book
This book has been structured into five parts plus an appendix.
### Part 1, Data Preparation: Business Point of View
The intended audience for Part 1 is anyone who is involved in the data preparation process for analytics. This part addresses the three persona groups that are usually integrated in the data preparation process: business people, IT people, and analysts. This part of the book is free from technical considerations or SAS code.
In this part, we deal with the definition of the business questions and with various considerations and features of analytic business questions. We investigate different points of view from IT people, business people, and statisticians on analytic data preparation and also take a look at business-relevant properties of data sources.
Business people who are the consumers of analytic results rather than being involved in the data preparation and analysis process benefit from these chapters by getting a deeper understanding of the reasons for certain requirements and difficulties. Also, IT people benefit from this part of the book by exploring the reasons made by the analyst concerning data requirements.
### Part 2, Data Structures and Data Modeling
The intended audience for Part 2 is IT people and analysts. This part deals with data models and structures of both the available source data and the resulting analysis table. In this part, we deal with data sources and their structures in the source systems. By exploring the terms analysis subject and multiple observation, we define the most common data mart structures for analytics, namely the one-row-per-subject data mart, the multiple-rows-per-subject data mart, and the longitudinal data mart.
Additionally we look at general features of data marts and special considerations for predictive modeling. In this part, we start considering data preparation from a technical point of view. We do this by showing a number of examples from a conceptual point of view, i.e., without SAS coding.
Whereas business people can benefit from the concepts in this part of the book, the chapters mainly address IT people and analysts by showing the data preparation concepts for analytics. Analysts will probably find in these chapters the explicit formulation and rationale of data structures, which they use intuitively in their daily work.
### Part 3, Data Mart Coding and Content
The intended audience for Part 3 is analysts and SAS programmers. In this part of the book, we start to get practical. This part explains how to fill a data mart with content. By using a similar structure as Part 2, we show with SAS code examples and macros how to create an analytic data mart from the source data. Here we run through data extraction from the source data, restructuring of the data (transposing), aggregating data, and creating derived variables.
The aim of this part is to help the analyst and SAS programmer to speed up his or her work by providing SAS code examples, macros, and tips and tricks. It will also help the reader to learn about methods to create powerful derived variables that are essential for a meaningful analysis.
### Part 4, Sampling, Scoring, and Automation
The intended audience for Part 4 is analysts and SAS programmers. This part contains chapters that deal with important aspects of data preparation, which did not fit into the previous part. Here we deal with topics such as sampling of observations, data preparation and processing considerations of scoring, and additional tips and tricks in data preparation.
### Part 5, Case Studies
The intended audience for Part 5 is analysts and SAS programmers. However, business people might be interested to see practical examples of steps that are needed to get from business questions to an analytic data mart.
In this part we put together what we learned in the previous parts by preparing data for special business questions. These case studies present the source data and their data model and show all of the SAS code needed to create an analytic data mart with relevant derived variables.
 
