## Analysis of Bitcoin Transactions
Starting from three different sources of data, three CSV files, Transactions, Inputs and Outputs, that represent an abstraction of the Bitcoin transactions.  
The dataset starts from the genesis block and ends at height 100,001, which is the block mined on 29-12-2010.  
The data is slightly modified with respect to the original Bitcoin blockchain, and some transactions have been removed.  
Other than that, this data is an almost entirely accurate Bitcoin dataset, so the results that you will obtain would provide you some insights on a real cryptocurrency.
For more information, please visit the [Bitcoin Analysis](https://github.com/fedehsq/btc-analysis/blob/main/BitcoinAnalysis.pdf) file.

### Setup the environment
To setup the environment, you can follow these steps:
1. Open a terminal and execute the command `virtualenv venv` inside project root.
2. Now, you have to activate it, by executing the command `source venv/bin/activate`.
3. You have to install all requirements, let's do that with `pip install -r requirements.txt`.
