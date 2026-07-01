# Evaluations

**Problem**

Management and customers regularly request ad-hoc evaluations — alert or case counts over a period, a specific user's activity log, an endpoint's behavior on a given day. Each request meant manually querying the SIEM, assembling the data, and formatting it into something readable. With requests coming in frequently and covering different topics, it was a recurring time drain.

**Solution**

A collection of purpose-built scripts, one per evaluation type. For user and endpoint evaluations, each script collects a defined set of activity categories — network connections, process executions, and more — for the requested subject and time window, then exports everything into a structured Excel report. New evaluation types can be added as new scripts without touching existing ones.

**Impact**

Ad-hoc evaluation requests that previously required manual SIEM querying and formatting are now fulfilled by running the relevant script. Response time to management and customer requests dropped significantly, and the output is consistent and professional every time.

<!-- ![Evaluations — sample](screenshots/overview.png) -->
