# Cloudera_Database
Creation and management of a database using VirtualBox and Cloudera

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
## General info
This project consists in the creation and management of a database using VirtualBox and the Cloudera data platform. The datasets used have been downloaded from the Banco Mundial website (https://www.bancomundial.org/es/home) and contain information on the total arable land surface (hectares per capita) and the percentage of rural population by country and year. The datasets are the following:

[API_SP.RUR.TOTL.ZS_DS2_es_csv_v2_2601419.csv](https://github.com/IsabelManzaneque/Cloudera_Database/files/7623423/API_SP.RUR.TOTL.ZS_DS2_es_csv_v2_2601419.csv)

[API_AG.LND.ARBL.HA.PC_DS2_es_csv_v2_2593504.csv](https://github.com/IsabelManzaneque/Cloudera_Database/files/7623424/API_AG.LND.ARBL.HA.PC_DS2_es_csv_v2_2593504.csv)

All the HiveQL commands used to develop this project have been implemented through a Jupyter Notebook

## Technologies
Project is created with:
* Oracle VM VirtualBox
* cloudera 5.12.0
## Setup
To run this project in Cloudera:
```
Download adn install Oracle VirtualBox
Download Cloudera VM and import into VirtualBox
To run the VM, click the start icon on the top area of the VirtualBox window
Once the Cloudera VM is up and running, load the project's Jupyter Notebook using a shared folder
Open the Cloudera VM console and execute:  $/home/cloudera/anaconda2/bin/jupyter notebook
Find and execute the project's notebook

```
