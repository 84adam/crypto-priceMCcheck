# crypto-priceMCcheck
Check Top Cryptocurrency Prices/Market Cap via Command-Line

---

Draft/Plan <WIP>

---

# COMMAND-LINE CRYPTO-CURRENCY PRICE CHECKER 
# <WIP: started 7/24/17>
# based on: https://coinmarketcap.com/api/
# refer to: https://jsonformatter.org/ for JSON formatting/beautifying tools

# global crypto-currency market data

# get JSON-formatted data using coinmarketcap.com API: https://api.coinmarketcap.com/v1/global/

# # example:
# # {
# #    "total_market_cap_usd": 94818837047.0, 
# #    "total_24h_volume_usd": 2219944167.0, 
# #    "bitcoin_percentage_of_market_cap": 47.35, 
# #    "active_currencies": 823, 
# #    "active_assets": 176, 
# #    "active_markets": 4695
# # }

---

# store this in a variable or database or text file


---

# NOTE: bitcoin_percentage_of_market_cap: 47.35
# TODO: create <coin>_percentage_of_market_cap function; run it against top 20 coins; add this to JSON data

---

# get JSON for top 20 coins using coinmarket: https://api.coinmarketcap.com/v1/ticker/?limit=20

# # example of top 3:
# # [
# #     {
# #         "id": "bitcoin", 
# #         "name": "Bitcoin", 
# #         "symbol": "BTC", 
# #         "rank": "1", 
# #         "price_usd": "2725.94", 
# #         "price_btc": "1.0", 
# #         "24h_volume_usd": "862126000.0", 
# #         "market_cap_usd": "44889177067.0", 
# #         "available_supply": "16467412.0", 
# #         "total_supply": "16467412.0", 
# #         "percent_change_1h": "-0.2", 
# #         "percent_change_24h": "-1.1", 
# #         "percent_change_7d": "28.17", 
# #         "last_updated": "1500922482"
# #     }, 
# #     {
# #         "id": "ethereum", 
# #         "name": "Ethereum", 
# #         "symbol": "ETH", 
# #         "rank": "2", 
# #         "price_usd": "223.813", 
# #         "price_btc": "0.0818608", 
# #         "24h_volume_usd": "459778000.0", 
# #         "market_cap_usd": "20931526820.0", 
# #         "available_supply": "93522391.0", 
# #         "total_supply": "93522391.0", 
# #         "percent_change_1h": "-0.21", 
# #         "percent_change_24h": "-1.65", 
# #         "percent_change_7d": "25.96", 
# #         "last_updated": "1500922468"
# #     }, 
# #     {
# #         "id": "ripple", 
# #         "name": "Ripple", 
# #         "symbol": "XRP", 
# #         "rank": "3", 
# #         "price_usd": "0.191885", 
# #         "price_btc": "0.00007018", 
# #         "24h_volume_usd": "67452600.0", 
# #         "market_cap_usd": "7347542946.0", 
# #         "available_supply": "38291387790.0", 
# #         "total_supply": "99994578575.0", 
# #         "percent_change_1h": "-0.09", 
# #         "percent_change_24h": "-1.66", 
# #         "percent_change_7d": "18.72", 
# #         "last_updated": "1500922442"
# #     }
# # ]





# Check against: List of Top 50 non-minable and non-premined coins: https://coinmarketcap.com/currencies/views/filter-non-mineable-and-premined/
