Direction for running application 
Import coins.zip in eclipse enviroment
Run CoinApplication as a java application 
open crome browser and enter below URL
http://localhost:8080/coin-Exchange/quantity/25
here quanitity is the number of coins to be converted 
output will be in following format
{"message":"Valid Request","currencyValue":{"0.25":100}}
please test with invalid case scenarios e.g
http://localhost:8080/coin-Exchange/quantity/-25
{"message":"Invalid Request","currencyValue":null}

