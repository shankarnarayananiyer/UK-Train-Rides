**🚆 UK Train Rides Analysis | Power BI Dashboard**

**📌 Project Overview**

This project analyzes UK train ticket purchases and journey performance to uncover insights related to revenue, customer behavior, punctuality, delays, and refunds. Using Power BI, I built an end-to-end analytics solution that transforms raw transactional data into actionable insights for business, operations, and customer experience teams.

The dashboards are designed for multiple stakeholders:

Executives → High-level performance & revenue visibility

Operations teams → Punctuality, delays, and route performance

Customer & commercial teams → Pricing, refunds, and purchase behavior

📂 Dataset Description

Source: Maven Analytics – UK Train Rides Dataset

Granularity: One row per ticket purchase / journey

Scope: Ticketing, journey details, delays, and refund behavior

Key data fields include:

Ticket purchase details (channel, payment method, ticket type, class)

Pricing & discount indicators (railcard, advance/off-peak/anytime)

Journey information (stations, dates, times)

🧱 Data Modeling Approach

Although the source data was a single flat table, it was treated as a fact table and remodeled into a star schema to enable scalable analysis and efficient DAX calculations.

Data model enhancements:

📅 Date dimension (purchase date & journey date)

⏰ Time attributes (departure, arrival, purchase time)

🚉 Station & route attributes

🎟️ Ticket characteristics

This approach reflects real-world BI best practices and improves performance, readability, and extensibility.

📊 Key KPIs & Metrics

The report includes business-critical metrics such as:

Total Revenue

Total Journeys

On-Time Performance (%)

Delay & Cancellation Rates

Average Delay Duration

Refund Request Rate

Revenue at Risk due to delays

Advanced DAX measures were used for time intelligence, ratios, and performance benchmarking.

📈 Dashboard Pages & Analysis
1️⃣ Executive Overview Dashboard

Purpose: Provide senior stakeholders with a high-level view of business performance, punctuality, and customer impact.

Key focus areas:

Overall revenue and journey volume

On-time vs delayed vs cancelled journeys

Refund request rate as an indicator of customer dissatisfaction

Ticket sales split by purchase channel and ticket type

Business questions answered:

How is the rail network performing overall?

Are delays and cancellations impacting revenue and customer experience?

Which ticket types and channels contribute most to revenue?

2️⃣ Operations & Punctuality Dashboard

Purpose: Enable operations teams to identify delay patterns and performance issues across routes and time periods.

Key focus areas:

On-time performance by route and station

Delay and cancellation rates

Average arrival delay (scheduled vs actual arrival time)

Breakdown of delay reasons

Business questions answered:

Which routes and stations are most affected by delays?

What are the primary reasons for delays and cancellations?

When do delays occur most frequently (time of day, date)?

3️⃣ Customer & Ticket Insights Dashboard

Purpose: Analyze customer behavior, pricing, and refund drivers to support commercial and customer experience decisions.

Key focus areas:

Ticket type and class distribution

Railcard usage and discount impact

Refund requests by journey status and delay reason

Purchase behavior (online vs station)

Business questions answered:

How do different ticket types and discounts impact revenue?

What factors drive refund requests?

Do purchase channels or ticket characteristics influence customer outcomes?

💡 Key Insights (Examples)

A small number of routes account for a disproportionately high share of delays and refund requests

Peak-hour journeys show significantly lower punctuality compared to off-peak travel

Advance and Off-Peak tickets drive volume but increase sensitivity to delays

Certain delay reasons consistently lead to higher refund rates, increasing revenue risk

🛠️ Tools & Skills Demonstrated

Power BI (Data modeling, DAX, dashboard design)

DAX (KPIs, ratios, time intelligence)

Data storytelling & stakeholder-focused design

Business & operational analytics

🚀 Potential Enhancements

Predictive modeling for delay likelihood

Customer segmentation using purchase patterns

Integration with operational cost data

SLA benchmarking across routes and stations

📎 Files Included

UK Train Rides Report.pbix – Power BI report file
railway - Raw sales dataset
railway_data_dictionary

📬 Contact

If you’d like to discuss this project or similar analytics work, feel free to connect with me on LinkedIn: https://www.linkedin.com/in/shankar-narayanan-iyer/ or explore my other projects on GitHub.
