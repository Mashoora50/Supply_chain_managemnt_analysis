Supply Chain Analysis Dashboard
Overview
Supplychainanalysispf.pbix is a Power BI report for reviewing
supply-chain performance across regions, warehouses, transport modes,
and time. It brings together order and delivery indicators with delay
and quantity comparisons to help identify operational bottlenecks and
improvement opportunities.

What the report contains
The report includes the following visual areas and measures, based on
the fields used in the Power BI report:
- KPI cards: Total Oder (as named in the model), OTIF %, OT %, and
  IF %.
- Regional performance: OTIF % and the OT % / IF % indicators by
  region.
- Performance over time: OTIF % by Month Year.
- Warehouse delays: Average Delay by Warehouse Location.
- Transport performance: Average Delay by TransportMode.
- Order and delivery quantities: DeliveredQty compared with
  OrderedQty by Month Year.
- Report filters: Month Year, TransportMode, Warehouse Location,
  and Region.
The report uses model tables named Fact_SCM, DIM, Date_Table, and
measuress.

Improvement Recommendations
1. Improve Warehouse Stock Planning: Optimize inventory levels, improve demand forecasting, and prevent stock shortages or excess stock.
2. Optimize Truck Transport Routing: Reduce delivery delays, optimize truck routes, improve vehicle utilization, and reduce transportation costs.
3. Focus on Low-Performing Regions: Identify regions with low OTIF performance and implement targeted improvements to increase delivery efficiency.
4. Improve Supplier Coordination: Strengthen supplier communication, improve delivery schedules, and ensure timely and accurate order fulfillment.
