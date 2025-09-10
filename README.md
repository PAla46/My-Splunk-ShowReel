# My-Splunk-ShowReel

Welcome to **My Splunk ShowReel**, a collection of dashboards I’ve built to turn complex data into clear insights. From monitoring system health to keeping batch jobs on track, these dashboards provide real-time visibility that makes decision-making easier.

Each one comes with visuals and simple explanations so you can see how it works and why it matters.

---

## 1) File Transmissions  

**Overview**  
This dashboard provides visibility into all file transfers handled by Connect:Direct, making it easier to understand and monitor transmission activity across the network.  

**Key Features**  
- Filter by inbound or outbound transmissions  
- Select specific source and destination nodes  
- View detailed records of individual file transfers  
- Pie chart showing distribution of file volumes across nodes  

**Value**  
By combining granular transfer data with visual summaries, this dashboard helps you spot workload imbalances, monitor throughput, and quickly troubleshoot failures or delays. It’s a practical tool for ensuring smooth and reliable data flows between systems.  

![File Transmissions](images/File%20Transmissions.png)

---

## 2) TWS Batch Health Check  

**Overview**  
This dashboard provides a comprehensive health check of all jobs submitted through OPC/TWS, giving you a clear picture of batch processing performance and stability.  

**Key Features**  
- Track failed job counts over the last 12 hours  
- Monitor overdue jobs in real time  
- View abend counts by application team, with filters for the past 24 hours, 7 days, and 30 days  
- Analyze abend trends with percentage increase or decrease month over month  
- Panel showing incidents generated in the last 12 hours  

**Value**  
With both real-time and historical insights, this dashboard helps operations teams quickly identify problem areas, monitor recurring failures, and measure long-term trends. It supports proactive incident management and ensures batch workflows run reliably without disruption.  

![TWS Batch Health Check](images/TWS%20Batch%20Health%20Check.png)

---

## 3) CPU Overview Usage

Get a high-level snapshot of CPU utilization trends across all monitored servers. This dashboard highlights peak usage periods, underutilized resources, and potential bottlenecks, enabling proactive resource management. It's perfect for capacity planning and spotting unusual spikes that might indicate underlying issues.

![CPU Overview Usage](images/CPU%20Overview%20Usage.png)

---

## 4) CPU Utilization

Dive into granular CPU metrics with this dashboard that visualizes real-time CPU load, core-by-core usage, and process-level performance. Ideal for system administrators who need to diagnose high-load scenarios or optimize workload distribution. It provides actionable insights into how CPU resources are allocated and consumed.

![CPU Utilization](images/CPU%20Utilization.png)

---

## 5) Storage Utilization

Monitor your storage landscape with this dashboard that tracks disk usage, available capacity, and growth trends across critical storage devices. Prevent outages by detecting storage exhaustion early and planning expansions accordingly. This dashboard is key for data lifecycle management and ensuring sufficient space for business operations.

![Storage Utilization](images/Storage%20Utilization.png)

---

## 6) CTM Server Monitoring Dashboard

Focus on the health and operational status of CTM (Control-M) servers with this dedicated dashboard. It tracks server availability, job execution statuses, and performance metrics, allowing for swift troubleshooting of scheduling issues or server downtime. Essential for maintaining automation workflows and job orchestration.

![CTM Server Monitoring Dashboard](images/CTM%20Server%20Monitoring%20Dashboard.png)

---

## 7) Agent Status

Quickly assess the connectivity and operational status of agents deployed across your infrastructure. This dashboard helps identify inactive or malfunctioning agents that could impact data collection or monitoring coverage. It's an indispensable tool for ensuring your monitoring ecosystem remains robust and responsive.

![Agent Status](images/Agent%20Status.png)

---

## 8) ESP Health Check

This comprehensive dashboard performs a health assessment of your ESP (Event Stream Processing) system. It visualizes system performance, error rates, and throughput, enabling you to ensure that event processing pipelines are stable and efficient. By identifying potential issues proactively, you can maintain high availability and data integrity.

![ESP Health Check](images/ESP%20Health%20Check.png)
![ESP Health Check (Continued)](images/ESP%20Health%20Check_1.png)

---
