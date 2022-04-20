# Spotify-test-app
This is a test app to find out the way to integrate smart contracts

Pages Includes: 
-------------------------

1.

![Screenshot 2022-04-20 at 02-37-41 React App](https://user-images.githubusercontent.com/87312799/164199642-3b231152-b3e5-46ed-9a43-b4da048a3cdf.png)


2.

![Screenshot 2022-04-20 at 02-38-13 React App](https://user-images.githubusercontent.com/87312799/164199740-81c4a782-1d02-448d-b065-372e1d1b605c.png)


3.

![Screenshot 2022-04-20 at 02-38-30 React App](https://user-images.githubusercontent.com/87312799/164199791-6b18bb00-1da5-4403-95c1-57a6e845871c.png)


4.

![Screenshot 2022-04-20 at 02-38-44 React App](https://user-images.githubusercontent.com/87312799/164199826-79c0f695-8500-4a04-9104-a9b825599f0c.png)


How to Deploy the Smart Contract

There isn’t a lot to it, so I’m going to try to be quick and thorough with this using screenshots. The first step is compiling your smart contract. You can do this in the second menu from the left menu bar.

![sc1](https://user-images.githubusercontent.com/87312799/164201933-a3eb55b1-2eba-456d-95a9-327b79c98cf7.png)


Select the contract you want to compile, and click the big blue button. If everything will go right it won’t return an error. It might update some artifacts and warn about that, but we don’t have to worry about that.

Then, in the third menu item from the left menu bar, we can deploy the contract. In one of my latest articles, I’ve talked about this for testing using Remix. But now we want to select “Injected web3” instead of the JavaScript VM.

![sc2](https://user-images.githubusercontent.com/87312799/164202078-cd9d7c2c-8183-4452-9ddf-73ea29724dc6.png)


Before clicking the nice-looking orange button, check the network you’re on. You can check this in MetaMask. You can see that I’m on a “Custom” 80001 network, this is the Polygon Mumbai testnet.

![sc3](https://user-images.githubusercontent.com/87312799/164202264-16d244b3-5d95-4b1d-981c-dc59586ac107.png)


The network you’re connected to is the network it will try to deploy on. So let’s click the orange button and accept the transaction. You’ll get a popup from MetaMask to do this.

![sc4](https://user-images.githubusercontent.com/87312799/164202456-6c44cba6-afbe-41d4-a0c5-f088e3d1395a.png)


You can check out the deployment fees, and reject the transaction if it’s too expensive. But since I’m on Polygon it’s negligible.

After accepting the fees and waiting a bit for the chain to confirm the transaction, you’ll see the newly deployed contract come up below the “deploy” button. Just like you get when deploying to the JavaScript VM.

![sc5](https://user-images.githubusercontent.com/87312799/164202553-59f79559-0547-4379-bfec-a53978c1e95a.png)


Copy the address by clicking the highlighted button, and keep it somewhere. This is the contract address. You can check that address on EtherScan or PolygonScan depending on where you deployed it. Also, keep in mind to go to the testnet versions of those sites if you’ve deployed to a testnet.
