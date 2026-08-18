# Lights, Camera, Success — A BI & CRM Transformation of Atelier Cinema

A business intelligence and CRM solution for **Atelier**, a small independent dine-in cinema in
Dublin facing declining attendance, weak session profitability, and no way to track or retain
customers. The project turns a fragmented, spreadsheet-run operation into a connected system:
a relational data model, three interactive **Tableau** dashboards, and a **Salesforce** CRM with
automated marketing and service workflows.

*MSc Data Analytics — Business Intelligence & Business Analytics. Group project (3 members).*

## The business problem

Atelier competes with multiplexes and streaming on one side and premium boutique cinemas on the
other. Five gaps were identified through gap analysis, SWOT, Porter's Five Forces and a Balanced
Scorecard: weak session profitability, low dine-in sales with an over-large menu, disconnected
ticketing and food systems, no customer retention mechanism, and thin experience differentiation.

## The solution

- **Relational data model** — 11 datasets (movies, screenings, ticket sales, food, customers,
  surveys, campaigns) modelled with an ERD and data dictionary, generated in Mockaroo and enriched
  with real Kaggle film and Irish market data, validated in Excel.
- **Tableau dashboards** — three role-based dashboards: cinema performance & scheduling, concession
  performance & prospection, and customer experience & campaigns.
- **Salesforce CRM** — custom objects (Customer, Survey, Campaign, Screening, Ticket Booking, Food
  Preorder, Supplier, Inventory) with record-triggered flows for satisfaction alerts, campaign
  routing, tier-based email automation, and linking food preorders to bookings.

## Selected results & insights

- **Session yield** analysis pinpointed low-return screening windows for rescheduling or removal
- **Concession** dashboards exposed a declining food-sales trend and the highest-margin products
- **Channel test:** SMS outperformed email on engagement (354 vs 190 opens; 153 vs 33 conversions)
- **Satisfaction by experience** showed sports broadcasts rating highest, guiding future programming

## Tools

Salesforce (CRM, custom objects, record-triggered flows, email automation) · Tableau ·
Mockaroo · Excel (validation) · data modelling (ERD, data dictionary)

## Repository structure

```
.
├── report/                 # project report (cover sheet & confidential pages removed)
├── presentation powerpoint/                 # presentation deck (PDF)
├── images/                 # 4 dashboard screenshots
└── README.md
```

> The report in this repository has the submission cover sheet and internal identifiers removed.
> All customer data shown is synthetic (generated in Mockaroo).

## Team & contribution

Group project by Chanlin Naicker, Marcio Pereira de Lima and Ya Wai Thone
(MSc Data Analytics, National College of Ireland).

**My contribution (Ya Wai Thone):**

- **System design** — data capture points, overall system architecture, and the end-to-end CRM
  integration plan from customer intake through to marketing
- **Data & KPIs** — designed and maintained the customer, survey and marketing-campaign datasets
  and defined the customer/engagement KPIs
- **Tableau** — built the Customer Experience & Campaign dashboard (channel engagement, satisfaction
  by experience, campaign success, dietary preference by tier)
- **Salesforce** — created the Customer, Survey and Campaign objects with correct relationships, and
  implemented the automation flows: survey-score checker, campaign routing, and tier-based email
  campaigns
- Contributed the stakeholder-views and database-design sections of the report

[LinkedIn](https://www.linkedin.com/in/ya-wai-thone/) · [GitHub](https://github.com/yawaithone)
