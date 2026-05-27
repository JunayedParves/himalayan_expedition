# Himalayan Expedition Risk & Underwriting Dashboard 🏔️📊

An interactive, cinematic data visualization platform designed to act as a visual underwriting engine for high-altitude expedition insurance.

Built using historical data from the Himalayan Database (1905–2024), this project translates 11,425 expeditions, 89,000 climbers, and 1,158 fatalities into actionable actuarial intelligence for non-life insurance modeling.

🔗 [View the Live Dashboard Here](https://junayedparves.github.io/himalayan_expedition/)

🎯 Business Context & Actuarial Insights

To a non-life insurance company, the Himalayas represent a classic high-severity, low-frequency risk environment. Standard travel policies explicitly exclude mountaineering, requiring highly specialized coverage (SAR Evacuation, Repatriation, AD&D, and Commercial Liability).

This dashboard analyzes historical loss data to inform critical underwriting functions:

Dynamic Pricing & Risk Tiering (The Danger Matrix):
By plotting Summit Probability against Mortality Incidence, the dashboard categorizes peaks by risk tiers. While Everest represents high frequency/exposure, peaks like Annapurna I represent extreme severity, requiring massive premium multipliers or outright coverage declinations.

Mandating Risk Mitigators (O2 Analysis):
Data proves that climbing without supplemental oxygen above 8,000m triples mortality risk. Insurers can use this quantitative baseline to mandate strict policy conditions (e.g., voiding coverage if O2 is not used above 7,500m).

Catastrophe (CAT) Modeling & Clash Risk:
Historical anomaly tracking (e.g., 1996 storm, 2014/2015 avalanches and earthquakes) allows insurers to model "Black Swan" events. This helps calculate Clash Risk—the financial impact of a single catastrophic event triggering multiple policy payouts simultaneously.

Seasonality Adjustments:
Heatmap analysis demonstrates that Winter ascents carry disproportionate mortality rates compared to Spring windows, allowing underwriters to strictly limit policy validity dates.

🛠️ Technical Stack

Frontend Structure: Semantic HTML5

Styling: Tailwind CSS (with custom Glassmorphism and cinematic gradients)

Data Visualization: ECharts (Canvas-rendered for high performance with large datasets)

Animations: GSAP (ScrollTrigger) & Vanilla JavaScript (Custom Canvas Snowfall)

Data Processing: JavaScript (Data aggregated and mapped from raw exped.csv, peaks.csv, and members.csv flat files).

MOST IMPORTANT INSURANCE USERS OF THIS DASHBOARD
1. Underwriters (Risk pricing).
2. Actuaries (Fatality modeling).
3. Claims Teams (Rescue analysis).
4. Reinsurers (Catastrophe exposure).
5. Product Teams (New insurance products).
6. Brokers(Client risk advisory).
7. Adventure Tourism Companies (Operational planning).


👨‍💻 About the Author

I am a Data Analyst specializing in General Insurance (Non-Life). I leverage tools like SQL, Power BI, Excel, and custom web dashboards to solve complex business questions, model risk, and translate raw data into strategic business intelligence.
