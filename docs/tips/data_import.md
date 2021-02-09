---
layout: default
title: Data Import 
parent: Tips and Tricks
nav_order: 1
---

# Data Import
{: .no_toc }

REDCap offers two options when it comes to importing data into an already existing project. The first option explained within this post is the use of the Data Import Tool and the second option is making use of REDCaps API to programmatically import data.

There are two primary options for importing data in to your REDCap project.

---

## Data Import Options
{: .no_toc .text-delta }

2. TOC
{:toc}

---

## Data import tool 

REDCaps Data Import tool allows a user to bulk upload records into REDCap all at once. This can be used for a whole array of reasons like uploading historical data, upload data collected from alternative data sources, record reassignment/modifications, import of data from one REDCap project to another.

Manual Import into REDCap via a CSV file (or excel file saved as a CSV).

[Data Import Tool](https://redcap.c2e2.ca/surveys/?s=DLT9TCWTL4){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## API based import

API' stands for 'Application Programming Interface'. An API is just a defined way for a program to accomplish a task. The REDCap API is an interface that allows external applications to connect to REDCap remotely, and is used for programmatically retrieving or modifying data or settings within REDCap, such as performing automated data imports/exports for a specified REDCap project.

Make use of the `Import Records` API method to programmatically import data into a REDCap project in an autonomous manner.
