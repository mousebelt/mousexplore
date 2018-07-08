# mousexplore
The MouseXplore Block Explorer

This project is created by MouseBelt and No Rest Labs to serve as a multi-currency block explorer. It supports both testnet and livenet transactions for cryptocurrencies, and is made to be easily branded and forked.

### Project Structure

There are two components: A frontend that serves as a ui, and a backend "vcoins" layer that serves enriched blockchain information through a Rest API.

[**mousexplore-frontend**](https://github.com/norestlabs/mousexplore-frontend) - This is the frontend, it is a React app. It supports toggling between cryptocurrencies and is mobile responsive. You can alter the config file to select any of the cryptocurrencies you would like to support and their hosting location, or add one of your own. Pull requests are welcome against the repo.

[**mousexplore-vcoins**](https://github.com/norestlabs/mousexplore-vcoins) - This is the backend, a nodejs cron and rest API that connects to mongodb and the specific node you would like to serve information from. To setup, clone the backend repo, then follow the specific setup instructions in the folder to share data. Pull requests are welcome to add new features, blockchains or any fixes you see that should be made. You are also welcome to copy it and add your own cryptocurrency. We recommend using whichever existing blockchain is closet to your application for this reason.

