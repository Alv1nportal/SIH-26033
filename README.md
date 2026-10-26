# Smart India Hackathon Workshop
# Date: 26/10/2026
## Reference Number: 26000971
## Name: Alvin Gladious A

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
Solution name: FarmConnect AI

FarmConnect AI is a digital marketplace that connects farmers, Farmer Producer Organizations (FPOs), consumers, retailers, hotels, supermarkets, and bulk buyers directly. It aims to reduce the number of intermediaries in the agricultural supply chain, helping farmers receive better prices while consumers purchase fresh produce at affordable rates.

The platform will allow farmers to list available crops, quantities, quality, prices, and harvest dates. Buyers can compare products and place orders directly. A built-in logistics system will coordinate collection, storage, delivery, and transportation.

The platform will also use Artificial Intelligence (AI) to forecast demand, suggest suitable prices, reduce food wastage, and optimize delivery routes.

Key features:
- Direct farmer-to-consumer and farmer-to-business trading.
- Live crop listings with quantity, quality, and pricing details.
- AI-based demand forecasting and price recommendations.
- Shared transportation and delivery scheduling.
- Digital payments and order tracking.
- Regional language support for farmers.
- Ratings and transparent transaction records.
## Technical Approach
Frontend	- HTML, CSS, JavaScript, React	- Farmer and buyer interface
Backend	- Python with FastAPI	- Business logic and APIs
Database -	PostgreSQL	- Users, crop listings, orders, and payments
AI/ML	- Python, Scikit-learn	- Demand prediction and price recommendations
Maps and routing -	OpenStreetMap with OSRM	- Delivery route optimization
Authentication	- OTP-based login and role-based access -	Secure user accounts
Payments	- UPI payment gateway integration	- Digital transactions
Deployment	- Cloud hosting -	Accessible web platform
<img width="955" height="660" alt="Screenshot 2026-10-26 090416" src="https://github.com/user-attachments/assets/cc125625-1c95-4b36-8820-d92b6be2acdb" />

## Feasibility and Viability
Technical feasibility: The solution can be developed using existing web technologies, open-source mapping tools, and Python-based machine-learning libraries. An initial prototype can use sample crop and order data.

Economic feasibility: The platform can start with a small pilot in one district and expand gradually. Revenue options include a transparent service fee on completed orders, subscriptions for bulk buyers, and logistics service partnerships.

Operational feasibility: FPOs and farmer groups can help farmers register products, aggregate orders, and coordinate deliveries. Local collection centres and transport partners can support areas where individual deliveries are expensive.

Solutions for the common Problems and Challanges:
Limited digital literacy	- Simple interface, local languages, assisted registration
Unreliable supply or quality	- Verified sellers, quality grading and inventory updates
High delivery costs -	Group nearby orders and share transport
Uncertain demand	- AI forecasts and advance bulk orders
Payment disputes	- Digital receipts, order records and grievance support
Poor connectivity	- Lightweight mobile-friendly design and SMS notifications

## Impact and Benefits
For farmers
Better access to buyers, greater price transparency, reduced dependence on intermediaries, and improved market planning.

For consumers
Access to fresher produce, more competitive prices, transparent product information, and convenient ordering.

For logistics providers
Better vehicle utilization, coordinated pickups, fewer unnecessary trips, and more efficient deliveries.

For the environment and society
Potential reduction in food wastage, avoidable transportation, and emissions, alongside stronger rural market access.

Suggested success metrics:
- Increase in the average net earnings received by participating farmers.
- Difference between farmer selling prices and consumer purchase prices.
- Reduction in average delivery cost per order.
- Percentage of orders delivered on time.
- Reduction in unsold or wasted produce.
- Number of active farmers, FPOs, and buyers using the platform.

## Research and References
1. National Agriculture Market (e-NAM) - Government of India. Background on digital agricultural
trading, price discovery, and market integration.
2. AGMARKNET market-price data - Government of India's Open Government Data Platform. A potential
source of historical minimum, maximum, and modal mandi prices for developing price-analysis and
forecasting models. 
3. e-NAM logistics module - Reference for agricultural transport and supply-chain services.
4. OpenStreetMap - Open geographic data for mapping farms, collection centres, and buyers.
5. OSRM (Open Source Routing Machine) - Open-source routing engine for road-route calculations.
