# coin_balance
Display crypto balance from one or more wallets, with online or offline balance

# you can found your coin id with this bash commmand, replace <UrCoin> by your coin
$ curl -s "https://api.coingecko.com/api/v3/coins/list" | awk 'BEGIN{ RS = "{|}"; FS="\n"  }{print }' | grep -i <UrCoin>

###### 1 : Set your coins in the variable of balance

##### 2 : set the path variable for your wallets path, make a set up like in ./wallet example

#### 3 : You can than put the programme in your bin

# this will work with a daemon core and offline when you put your balance in .json


