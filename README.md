Dynamic Data Reporting with n8n (Crypto, Weather, Google Sheets, Email)
Description
This project demonstrates an automated workflow that collects and reports on live data from multiple public APIs, including cryptocurrency prices and weather forecasts. Using n8n’s no-code visual workflow builder, the system retrieves up-to-date information, formats it for easy reading, and delivers it to Google Sheets for dynamic dashboards and record-keeping. Optionally, key daily updates can also be sent automatically by email, ensuring you always have timely insight into the latest numbers.

Why This Approach?
Real business value:
Transforms raw API feeds into digestible daily reports — a jumpstart for data-driven decisions.

Safe and demo-ready:
Only uses open/public data sources, so there are no privacy or compliance risks.

Modular and flexible:
Swap public APIs for internal business data (e.g., Swisscom metrics) with no changes to the overall workflow.

Rapid prototyping:
n8n’s visual interface lets you build, modify, and expand automations in minutes.

Creates actionable visibility:
Builds the habit of structured daily status reporting.

Resources to Explore
CoinGecko Public Crypto API
OpenWeatherMap API
n8n Google Sheets Node
n8n Community: Creating Dynamic Dashboards
(Optional for future/roadmap: OpenAI GPT, n8n OpenAI node)
Workflow Roadmap
1. Connect Public Data Sources

CoinGecko API for live Bitcoin & Ethereum prices
OpenWeatherMap API for 5-day weather forecast
n8n HTTP Request node pulls data on a daily schedule
2. Format and Process Data

Set/Function nodes extract, calculate, and format daily metrics
3. Publish to Dashboard

Push results to Google Sheets for tracking and visualization
4. Automated Email Updates

Optionally, send a daily summary by email for fast insights
5. Test & Monitor

Manually or scheduled; confirm results appear; adapt fields or layout as needed
6. Optimize & Extend

Easily swap data sources, add new metrics, or integrate with services like Notion, Markdown, or business APIs
How is this Useful?
Accelerates daily monitoring and reporting for operational or business data
Can be instantly reused for internal KPIs, helpdesk stats, network monitoring, and more
Fully open/modular — ready for any business data source!
Visual workflow builder enables non-developers to own their automation solutions
How to Import and Use the Workflow
Get started in minutes:

Download the workflow:
Click workflow.json in this repository and save it to your computer.

Open your n8n instance:
Visit n8n.io or your self-hosted n8n server.

Import the workflow:

Click the Import button (usually at the top right in the n8n editor).
Select and upload the downloaded workflow.json file.
Configure credentials:

Set up your own Google Sheets, OpenWeatherMap, Gmail, etc., credentials if required.
This workflow uses public data APIs; no sensitive keys are included.
Activate the workflow:

Optionally adjust the schedule or outputs as needed for your environment.
Toggle to activate and you’re set!
n8n official docs: Importing and exporting workflows.

Roadmap: AI & Advanced Insights (Optional/Future)
If/when OpenAI (GPT) is integrated, the workflow can automatically summarize trends, flag anomalies, or generate strategic insights—no manual analysis required.

Want to automate your data reporting? Clone this repo, import the workflow JSON to n8n, and start your mornings smarter!
