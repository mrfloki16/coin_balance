# coinbal
Display crypto balance from one or more wallets, with online or offline balance

# You can found your coin id with this bash commmand, replace <UrCoin> by your coin
$ curl -s "https://api.coingecko.com/api/v3/coins/list" | awk 'BEGIN{ RS = "{|}"; FS="\n"  }{print }' | grep -i <UrCoin>
