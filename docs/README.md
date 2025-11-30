# Tesla - Supplier Cost Analysis & RFQ Simulator

Supplier Cost Analysis & RFQ Negotiation Simulator for NPI

**Dataset:** `tesla_procurement_7000.csv`

**Tools used:** Power BI, Excel, Python, Negotiation simulation

## Objective
Support NPI procurement with RFQ analytics, supplier negotiation simulation, and cost-savings tracking.

## Key Metrics & Formulas
- **Cost Savings %**: (RFQ_Price - Negotiated_Price) / RFQ_Price * 100
- **Yearly Spend**: Negotiated_Price * Yearly_Consumption_Qty
- **Supplier Score**: Weighted Score of Quality, Lead Time, Price

## Dashboard Pages
- Spend Overview
- Top Savings Opportunities
- Supplier Scorecard
- RFQ Negotiation Simulator
- Parts Ageing & MOQ impact

## How to reproduce
1. Download dataset
2. Load into Power BI / Excel / Python
3. Follow the notebook outline for analytics

## Results (sample insights)
- Achieved median negotiated savings of ~9.8% across RFQs
- Top 20 suppliers represent 40% of spend
- Identified parts with high tooling cost where strategic negotiations could save >20%
