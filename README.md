# cryptoRest
rest crypto implementation


https://api.binance.com/api/v1/exchangeInfo

{
    "timezone": "UTC",
    "serverTime": 1556741474070,
    "rateLimits": [],
    "exchangeFilters": [],
    "symbols": [{
        "symbol": "ETHBTC",
        "status": "TRADING",
        "baseAsset": "ETH",
        "baseAssetPrecision": 8,
        "quoteAsset": "BTC",
        "quotePrecision": 8,
        "orderTypes": [
            "LIMIT",
            "LIMIT_MAKER",
            "MARKET",
            "STOP_LOSS_LIMIT",
            "TAKE_PROFIT_LIMIT"
        ],
        "icebergAllowed": true,
        "isSpotTradingAllowed": true,
        "isMarginTradingAllowed": true,
        "filters": [{
                "filterType": "PRICE_FILTER",
                "minPrice": "0.00000000",
                "maxPrice": "0.00000000",
                "tickSize": "0.00000100"
            },
            {
                "filterType": "PERCENT_PRICE",
                "multiplierUp": "10",
                "multiplierDown": "0.1",
                "avgPriceMins": 5
            },
            {
                "filterType": "LOT_SIZE",
                "minQty": "0.00100000",
                "maxQty": "100000.00000000",
                "stepSize": "0.00100000"
            },
            {
                "filterType": "MIN_NOTIONAL",
                "minNotional": "0.00100000",
                "applyToMarket": true,
                "avgPriceMins": 5
            },
            {
                "filterType": "ICEBERG_PARTS",
                "limit": 10
            },
            {
                "filterType": "MAX_NUM_ALGO_ORDERS",
                "maxNumAlgoOrders": 5
            }
        ]
    }]
}
