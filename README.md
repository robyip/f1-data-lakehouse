# f1-data-lakehouse
A data lakehouse for F1 races data 

Infrastructure built and deployed using Terraform

Development language: Python

Storage: Delta Lake using Parquet

All F1 source files loaded into landing zone

Triggering a step function to create f1 bronze tables with meta data 

Create normalised Silver tables

Create gold star schema for reporting

