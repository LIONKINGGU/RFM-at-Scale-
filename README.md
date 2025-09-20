# RFM-at-Scale-
Optimized SQL on BigQuery, Visualized in Looker Studio
RFM Segmentation — BigQuery + Looker Studio

Turn raw retail transactions into actionable customer segments (Champions, Loyal, New, At-Risk Loyalists, At-Risk) using scalable SQL on BigQuery and a lightweight Looker Studio dashboard. This repo includes production-style SQL with partitioning, clustering, and incremental refresh to keep costs low and performance high.

✨ What you get

Clean, reproducible SQL pipeline

RFM_clean_tbl → de-dup, flags, winsorization

customer_orders → nets returns at invoice level

customer_segments → RFM scoring + labels

Optimized tables (partitioned by date, clustered by keys)

Optional search index for fast text filters

A starter Looker Studio dashboard layout (segments, revenue, heatmap, drill)

https://lookerstudio.google.com/reporting/721c490a-bc78-4a4f-906a-8b09c3c6659f
