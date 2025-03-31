# *** Grafana generic templates for Eyer ***
1. Make sure you have your credentials available (apiTokenRead, environment id)
2. Replace "apiTokenRead" in the template with your token (multiple entries possible)
3. If present in the template, replace "environment_key" with your environment id (multiple entries possible)
4. Save the template and import in Grafana

For additional instructions please see https://customer.support.eyer.ai/servicedesk/customer/portal/1/article/206897153 and https://customer.support.eyer.ai/servicedesk/customer/portal/1/article/141950977

### Dashboards available
1. AlertInvestigation - a dashboard where you can view live anomaly alerts, and get details down to nodes and metrics affected.
2. HistoricalAlertDrilldown - for past alerts. Based on alertID, you can view all alert updates and metrics affected.
3. MachineLearningStatusDashboard - view the status of the machine learning for your Eyer environment. How many metrics are properly learnt vs how many needs more data
4. Node_charting - chart metrics for any node in your Eyer environment
5. Top 20 Boomi regular processes - view Boomi regular processes sorted by highest latency
6. Top 20 BizTalk ports by count - view which BizTalk ports have the highest amount of transactions
7. Dependency Topology - select any node in your Eyer environment, and see its discovered dependencies
8. Single Metric Type Charting - select a metric type, and chart it across multiple nodes that have the same metric
9. Topology - view a complete topology discovered by the Eyer correlation engine. 
