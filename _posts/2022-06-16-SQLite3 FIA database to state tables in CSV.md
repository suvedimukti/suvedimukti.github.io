---
title:  "Geospatial Data Visualization Using Geopandas"
mathjax: true
layout: post
categories:
  - github
  - website
---


# FIA database to state tables (*CSV)
 [Mukti Subedi](suvedimukti@gmail.com)

The United States Department of Agriculture (USDA) run Forest Inventory and Analysis (FIA) program. FIA Datamart allows to download raw data files, standard tables, 
SQLite databases, and a desktop EVALIDator reporting tool. DataMart also provides access to the FIA State reports, FIADB most recent load history, API EVALIDator, 
and FIADB User Guides.

Out of these data, SQLite database, and raw data files are important for analysist who is interested to run his/her own analysis. Usually, raw state tables  (in csv) are 
easy to use as only few of them are required to have full access to time-series FIA data. However, due to some internal reporting inconsistencies, FIA raw data are not available
for public since April 13, 2022.

Inabiliiy to access raw data hamper people to use rFIA package. In light of this, this brief document shows the necessary process to create state raw tables based on 
SQLite 3 database which is available for download from here <https://apps.fs.usda.gov/fia/datamart/datamart_sqlite.html>.


Full instructions on how to convert download SQlite db, install necessary packagees in R, convert SQLite db tables to raw state tables, and open in R using **rFIA** package is given in this document [click here to read it](https://github.com/suvedimukti/suvedimukti.github.io/blob/master/_posts/SQLIte_FIADB_TO_StateTables.pdf)
