---
title: "I let Claude Code build my dbt models. The interesting part wasn't the code."
url: "https://blog.reccehq.com/i-let-claude-code-build-my-dbt-models.-the-interesting-part-wasnt-the-code"
date: "2026-02-25"
author: "dori@reccehq.com (Dori Wilson)"
feed_url: "https://blog.reccehq.com/rss.xml"
---
I've been building out our analytics warehouse at Recce. We recently had our devs dump our production databases into S3, then I set up the pipeline from S3 into Snowflake with dbt-core on top. We follow the usual STAR schema, medallion architecture: staging, intermediate, marts.
