# mousexplore
The MouseXplore Block Explorer

This project is created by MouseBelt and No Rest Labs to serve as a multi-currency block explorer. It supports both testnet and livenet transactions for cryptocurrencies, and is made to be easily branded and forked.

### Getting Started

This is a repository containing the latest release, and both paired submodules. You will need both the frontend and backend module to run this application (we have a [sample hosted deployment](https://mousexplore.mousebelt.com) available online as well).

To get started, you will need to host the frontend and backend on whichever instances you wish to run the explorer on. You can also download the latest releases recursively from this module using the following commands.

##### Using HTTPS:
```
git clone --recurse-submodules -j8 https://github.com/norestlabs/mousexplore.git
```

##### Using SSH:
```
git clone --recurse-submodules -j8 git@github.com:norestlabs/mousexplore
```

### Project Structure

There are two components: A frontend that serves as a ui, and a backend "vcoins" layer that serves enriched blockchain information through a Rest API.

[**mousexplore-frontend**](https://github.com/norestlabs/mousexplore-frontend) - This is the frontend, it is a React app. It supports toggling between cryptocurrencies and is mobile responsive. You can alter the config file to select any of the cryptocurrencies you would like to support and their hosting location, or add one of your own. Pull requests are welcome against the repo.

[**mousexplore-vcoins**](https://github.com/norestlabs/mousexplore-vcoins) - This is the backend, a nodejs cron and rest API that connects to mongodb and the specific node you would like to serve information from. To setup, clone the backend repo, then follow the specific setup instructions in the folder to share data. Pull requests are welcome to add new features, blockchains or any fixes you see that should be made. You are also welcome to copy it and add your own cryptocurrency. We recommend using whichever existing blockchain is closet to your application for this reason.

### Documentation

The [**API Docs**](https://github.com/norestlabs/mousexplore-vcoins/wiki) can be found inside of the vcoins repo. MouseBelt maintains APIs for the cryptocurrencies listed in the repo, you are welcome to host them yourself!

### Contributing

If you see a change you would like to make, please file an issue in the appropriate repository. If you are unsure or have a general request, file it inside this one. 

### Usage

You are free to copy this repository and use however you like, under the MIT license. If you do end up using it, send a link! We'd love to see more copies out in the wild.
