## **RICO TRADE** ##: ## *A clone of Kite trading platform by Zerodha*#

Deployed on Vercel (https://ricotrade.vercel.app/)

This use charts.js for data visualisation

## **API Endpoints used in RicoTrade-Trade**

GET (https://backend4rt.onrender.com/allholdings)
Fetches the latest data about holdings from the MongoDB database used in Holdings.js.

GET (https://backend4rt.onrender.com/allpositions)
Fetches the latest data about positions from the MongoDB database used in Positions.js.

POST (https://backend4rt.onrender.com/newOrder)
Adds new data to the MongoDB database about the orders of users used in BuyActionWindow.js.
