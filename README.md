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

**Overview**  
This dashboard provides real-time visibility into CPU utilization across multiple LPARs, helping you monitor system performance at a glance.  

**Key Features**  
- Multiple exploded panels showing live CPU usage for each LPAR  
- Instant view of utilization patterns across the environment  
- Identify peak usage periods and potential hotspots in real time  
- Highlight underutilized resources for better capacity balancing  

**Value**  
By breaking down CPU usage at the LPAR level, this dashboard makes it easier to detect imbalances, spot unusual spikes, and manage capacity proactively. It supports both day-to-day performance monitoring and longer-term capacity planning.  

![CPU Overview Usage](images/CPU%20Overview%20Usage.png)

---

## 4) CPU and Memory Utilization  

**Overview**  
This dashboard provides detailed performance metrics for individual LPARs, giving a clear view of both CPU and memory usage in real time.  

**Key Features**  
- Granular CPU utilization stats for each LPAR  
- Memory usage tracking alongside CPU metrics  
- Drill-down visibility into performance at the LPAR level  
- Helps identify high-load scenarios and resource bottlenecks  

**Value**  
By combining CPU and memory insights in one place, this dashboard makes it easier to diagnose performance issues, balance workloads, and ensure efficient resource utilization across LPARs. It’s an essential tool for administrators who need deep visibility into system performance.  

![CPU Utilization](images/CPU%20Utilization.png)

---

## 5) Storage Utilization  

**Overview**  
This dashboard provides a clear view of storage usage across all storage groups, helping you stay on top of capacity and usage patterns.  

**Key Features**  
- Overall insights into free and used space for all storage groups  
- Interactive graphs showing free vs. used space when a specific storage group is selected  
- Top 10 datasets consuming the most space within a storage group  
- Visual trends to track storage growth and usage patterns  

**Value**  
By highlighting both overall and granular storage usage, this dashboard helps you identify space hogs, prevent storage exhaustion, and plan capacity more effectively. It’s a practical tool for proactive storage management and ensuring critical systems always have the space they need.  

![Storage Utilization](images/Storage%20Utilization.png)

---

## 6) CTM Server Monitoring  

**Overview**  
This dashboard provides real-time monitoring of Control-M (CTM) servers, giving visibility into host availability, system resources, and overall server health.  

**Key Features**  
- Active vs. inactive hosts panel with real-time counts  
- List of active and inactive hosts for quick troubleshooting  
- Disk usage monitoring (total, free, and used space) across all servers  
- CPU usage percentage by host with color-coded thresholds  
- Memory utilization percentage by host with visual indicators  

**Value**  
By consolidating server health and performance data in one place, this dashboard makes it easy to detect resource constraints, identify failing or overloaded hosts, and prevent disruptions in Control-M scheduling. It enables proactive management of the CTM environment, ensuring automation workflows remain reliable and efficient.  

![CTM Server Monitoring Dashboard](images/CTM%20Server%20Monitoring%20Dashboard.png)

---

## 7) CTM Agent Status  

**Overview**  
This dashboard monitors the health and availability of Control-M agents, providing real-time insights into their operational status across Windows servers.  

**Key Features**  
- Current agent status with clear visual indicators (e.g., Running, Inactive)  
- Timestamp of the last inactive period for each agent  
- Detailed agent statistics including host, display name, state, start mode, and service type  
- Filters to focus on specific hosts or time ranges  

**Value**  
By tracking agent activity and historical downtime, this dashboard helps identify inactive or malfunctioning agents before they impact scheduling operations. It ensures Control-M agents remain available and reliable, strengthening the overall stability of the workload automation environment.  

![Agent Status](images/Agent%20Status.png)

---

## 8) ESP Batch Health Check  

**Overview**  
This dashboard provides a health check of ESP batch processing, giving real-time and historical visibility into job failures and incident generation.  

**Key Features**  
- Track the number of job failures in the last 12 hours with time-based trend charts  
- Monthly job failure comparisons across current, previous, and earlier months  
- Percentage increase or decrease in failures to highlight trends  
- Incident management panel showing incidents generated in the last 12 hours, with breakdown by status (Assigned, In Progress, New, Resolved)  

**Value**  
By combining short-term failure monitoring with long-term trend analysis, this dashboard helps teams quickly identify problem areas, measure reliability over time, and connect failures with incident management. It enables proactive intervention to reduce recurring issues and improve overall batch stability.

![ESP Health Check](images/ESP%20Health%20Check.png)
![ESP Health Check (Continued)](images/ESP%20Health%20Check_1.png)

---
