# solana-wallet-moonshot-alert
--> insert your wallet with price fetch api you want to use and your RPC endpoint.
--> it will first fetch all the token from the wallet and will fetch the price and value of the tokens and will save it in a xlsx file.
--> then it will constantly run every 120 seconds(since my price fetch api only allows to use mass query every 120 seconds) to fetch all the tokens from the wallet and fetch its price and value.
--> if the new value is 20% more than value stored previously or more than 10 USDC it will send a notification to tg.
--> Feel free to modify it according to your specifications.
