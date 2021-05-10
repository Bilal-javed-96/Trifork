

## Cloud Formation Template
This file is a JSON code for infrastructure represented in **_Reference Architecture_** file. 
It is used to deploy a highly available infrastructure with fault tolerance, cost optimization and elasticity.
Following resources are deployed through this template.

1. VPC with two Public and Private subnets,
2. Route Tables,Internet Gateway
3. Security Groups
4. Laumch Configuration and Autoscalling Group
5. Application Load Balancer and its supporting components
6. Route 53 record


## Linux Dashboard and Windows Dashboard

These are Grafana Dashboards that i deployed for a client a month ago.
Grafana Dashboard uses **Prometheus** as a datasource which collects metrics from windows and linux instances using **wmi** and **node** exporters.It visualizes metrics like uptime,memory,cpu utilization and disk usage etc.
