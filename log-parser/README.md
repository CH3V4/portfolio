# Log Parser

**Problem**

Not every log source ships with a native Elastic integration. Some sources send logs in custom or non-standard formats that Elastic cannot parse out of the box — meaning the raw data lands in the SIEM but fields aren't extracted, events aren't structured, and the logs are essentially invisible to detection rules and dashboards.

**Solution**

A parsing script sits between the log source and Elastic. It reads the raw log output, extracts the relevant fields, normalizes them, and ingests the structured data into Elastic in a queryable format. Each parser is tailored to the specific log source's format, turning unreadable raw text into properly indexed, searchable events.

**Impact**

Log sources that were previously dark — ingested but unusable — became fully visible in the SIEM. Detection rules, alerts, and dashboards could now cover these sources, closing coverage gaps that would otherwise go undetected.

<!-- ![Log Parser — sample](screenshots/overview.png) -->
