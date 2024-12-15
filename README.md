# Solana-wallet-moonshot-alert
--> Insert your wallet with the price fetch API you want to use and your RPC endpoint.<br>
--> It will first fetch all the tokens from the wallet, fetch the price and value of the tokens, and save it in an xlsx file.<br>
--> Then it will constantly run every 120 seconds(since my price fetch API only allows mass query every 120 seconds) to fetch all the tokens from the wallet and their price and value.<br>
--> If the new value is 20% more than the value stored previously or more than 10 USDC it will send a notification to tg.<br>
--> Feel free to modify it according to your specifications.
