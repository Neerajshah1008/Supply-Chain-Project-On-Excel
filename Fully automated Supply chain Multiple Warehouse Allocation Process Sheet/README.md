🟩 Sheet Details:

🔹 Purchase Order Details
•	A – style_id: Unique style ID of the product listed in the PO.

•	B – scan_identifier: Product's scan code used by the seller; acts as the primary identifier.

•	C – po_identifier: Unique PO number for platforms such as POSI Tech.

🔹 PO Status & Metrics

•	AZ – Discontinued Check: Indicates if the product is discontinued (Yes/No).

•	BA – PO Fill %: Percentage of product quantity filled against the PO raised.

•	BB – PO Quantity: Total quantity raised for a given product in the PO.
________________________________________
🏬 Warehouse Inventory (Live Availability)

•	BC to BE – Warehouse Inventory: Available inventory for the respective product from:

o	BC – Bangalore (BLR)

o	BD – Gurugram (GGR)

o	BE – Mumbai (MUM)
________________________________________
📈 Sales Data & Tagging

•	BG to BI – D2C Sales (DRR): Daily Run Rate of D2C sales over the past 2 months for:

o	BG – BLR

o	BH – GGR

o	BI – MUM

•	BK – Tag: Frequency of sale (e.g., Fast = F, Superfast = SF), based on recent D2C sales trends.

•	BL – Safety Stock Days: Number of days of stock buffer to maintain for D2C sales, based on product velocity and classification.
________________________________________

🧮 Safety Stock & Allocation

•	BM to BO – Safety Stock Calculation: Computes safety stock required per warehouse for D2C sales based on days from BL.

•	BP to BS – Excess Inventory: Determines excess stock available which can be reallocated to B2B partners.
________________________________________

🚚 Automated Inventory Allocation Across Warehouses

BU to BW – Multi-Warehouse Allocation: These three columns automatically allocate inventory for each product from all three warehouses (BLR, GGR, and 
MUM) to maximize fulfillment against raised POs.

• No manual input is required to switch warehouse names.

• The system intelligently pulls available stock from each location for optimal allocation.

• This enables more efficient inventory usage and faster response to PO demands.
