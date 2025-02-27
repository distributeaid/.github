# Distribute Aid

Distribute Aid organizes the world's largest mutual aid supply-chain. Our processes are designed to prioritize the needs of our frontline partners while minimizing costs and shipping complications.

We take a long-term approach, participating in both the emergency response longer term recovery phases of acute crises (war, natural disasters), as well as responding to ongoing crisis (refugees, poverty). This allows us to maintain our network and operational capacity in a region, so that our partners can depend on us and we are collectively ready to respond to newly emerging crises there.

![DA Circular Economy](https://github.com/user-attachments/assets/9689126a-dfb0-49e5-8e29-4fbfdce5c053)

## ⛑️ Responses

We are currently responding to support:

- Refugees in Europe (France, Greece, Italy, the Balkans)
- Civillians in Ukraine
- Displaced People in the Levant (Gaza, West Bank, Lebanon)
- Disaster Response in the SouthEast US
- Mutual Aid Groups in the US

In the past we've also responded to:

- COVID-19 in Europe, the US, and Lebanon
- Afghans Evacuated to the US

## 👋 Contributing

The foundation of grassroots aid movements is built by everyday folks putting in a few hours every week, and you should be proud to be a part of it. Through your work with Distribute Aid you will make it easier for hundreds of grassroots organizations and thousands of aid workers to improve the lives of hundreds of thousands of people. We're on track to save our frontline partners hundreds of hours of work, and deliver up to $10,000,000 worth of aid each year!

We take a people-first approach at Distribute Aid, and will do our best to match you up with work that fits your skill set and interests. If you're not already in touch yet, please introduce yourself by emailing <tech@distributeaid.org> and let us know what technologies you are familiar with as well as how much time you are willing to commit as a contributor. One of our tech leads will help get you onboarded to our Open Source Contributors team and started on your first contribution.

Our tech team is fully remote. It's possible to work asynchronously using Github Issues, Github Pull Requests, and Slack. As a contributor, you're also welcome to drop into our weekly Tech Hangs on Wednesdays and Thursdays at 18 - 20 CET (12 - 2pm EST). We have a monthly Tech meeting at 18 CET (12pm EST) during the first Wednesday of each month that everyone is encouraged to attend (or at least contribute an update to the slides and catchup on the zoom recording if you can't make it).

Please read our [Code of Conduct](https://github.com/distributeaid/.github/blob/saga/CODE_OF_CONDUCT.md).

## Projects

### 🕊️ DA Landing Site

> New Website (trying to launch): <https://github.com/distributeaid/next-website-v2>

> Designs for New Website: <https://www.figma.com/design/Yq8LKeIVka701hYL45heud/Colors-for-DA>

> Previous Website (currently live): <https://github.com/distributeaid/distributeaid.org>

Distribute Aid's landing site. This includes typical information about the organization, our work and impact, how to contact us, and where to donate. It is also the public-facing frontend to share information and insights from our other projects, such as the Needs for each region we work in and the shipments we're sending to meet those needs.

Technology: ⚙ TypeScript, NextJS, React, Radix UI, Tailwind

### 🚚 Shipment Data Reporting Pipeline

> Backend (trying to launch): <https://github.com/distributeaid/aggregated-public-information>

> Frontend: Per-shipment and summary data will be shown through the landing site (see above) on Shipment pages, Response pages, and supply-chain visualizations.

Our Shipment Data Reporting Pipeline ingests data that we record for each shipment, proccesses it into impact stats, and presents it through a public API that is consumed by our landing site as well as shared with researchers and other thrid parties. Data handled by the pipeline includes:

* Product Information such as Cost, Weight, Volume, # Needs Met
* Shipment Data such as Summaries, Routes, Cargo, and Cost
* Economic & Currency Comparisons

Technology: ⚙ Postgres, TypeScript, NodeJS, Strapi, Jest, Supertest

### 📋 Needs Assessment

> New Needs Assessment Backend: <https://github.com/distributeaid/aggregated-public-information>

> Frontend: The needs assessment forms and summary response data will be displayed on our landing site (see above).

> Old Needs Assessment Frontend: <https://github.com/distributeaid/needs-assessment>

> Old Needs Assessment Backend: <https://github.com/distributeaid/needs-assessment-storage>

The goal of this project is to provide a way for Distribute Aid to run needs assessment using forms that can be modified using low-code or zero-code approach. These forms need to provide validation and flow logic.

Technology: ⚙ Postgres, TypeScript, NodeJS, Strapi, Jest, Supertest
