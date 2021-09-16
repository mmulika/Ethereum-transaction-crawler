
# EthereumTransactionsCrawler

Web application that collects data from the Ethereum blockchain about transactions associated with a specific wallet address that the user inputs. The app gets information on the wallets (addresses) and amounts of ETH associated with transactions made to and from a certain given wallet and then store them in a MongoDB database and shows them in a simple human-readable way through a web page. The web app collects transaction data starting from a given block.

## Install & Run

```sh
https://github.com/mmulika/Ethereum-transaction-crawler.git
cd Ethereum-transaction-crawler
npm install
mongod &
npm start
```

Then visit [http://localhost:3800/](http://localhost:3800/)

![Screenshot (71)](https://user-images.githubusercontent.com/48745848/133569793-0e82e8cb-85c3-4674-b0a6-7ce5d832fe5b.png)![Screenshot (72)](https://user-images.githubusercontent.com/48745848/133569833-f6469342-5cf6-46ff-9748-19845e7dc36d.png)
