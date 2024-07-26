# Demo App Setup Guide  ==>> dapp app by me for localnet=======>>>> https://garden-finance-lyart.vercel.app/   ==>>>> usage of garden finance sdk is at  last
In this guide will walk you through setting up and running our demo app that uses the [Garden SDK](https://docs.garden.finance/developers/sdk/) to swap WBTC (Wrapped Bitcoin) for BTC (Bitcoin). 
## Live Demo

You can try out the live version of our dApp here: [Garden Finance Demo](https://garden-finance-lyart.vercel.app/){app by me dapp}

## Features

Here’s what our demo app offers:

- **Merry Integration**: Provides a complete multichain environment for performing swaps. merry helps in performing multichain environment for performing swaps
- you have to download this and download steps are below.
- 
- **Swap Interface**: Easily swap from WBTC to BTC. this is a ui for swapping WBTC TO BTC.
- 
- **Transaction Management**: See and track the latest transactions.
- 
- **Garden SDK Integration**: Utilizes Garden SDK for executing swaps. as this task is of graden finance u should be integrating Garden sdk.
- 
- **State Management**: Uses [zustand](https://zustand-demo.pmnd.rs/) to manage the state of the app.

## Environment Setup

To get everything running, follow these steps:

### 1. Install Merry

Firstly, you need to install Merry, which sets up the multichain environment necessary for our dApp.

Open your terminal and run:
```bash
curl https://get.merry.dev | bash
```

###2. Start Merry

Next, you need to start Merry. You have two options:

- **With Explorer**: This will open an explorer interface.
  ```bash
  merry go
  ```

- **Without Explorer**: This runs Merry in headless mode, which is useful for automated setups.
  ```bash
  merry go --headless
  ```

### 3. Fund Your EVM Address

To use the dApp, you need to fund your Ethereum address. This step will give you the necessary tokens to interact with the app.

Run the following command, replacing `<EVM Address>` with your actual Ethereum address:
```bash
merry faucet --to <EVM Address>
```

## Project Setup

Now, let’s set up and run the demo app on your local machine:

### 1. Clone the Repository

Firstly, you need to clone the repository containing the demo app’s code.

In your terminal, enter:
```bash
git clone https://github.com/gardenfi/demo-app
cd demo-app
```

### 2. Install Dependencies

Next, install all the necessary dependencies required for the app to run.

Run:
```bash
bun install
```

### 3. Run the Development Server

Finally, start the development server to see the dApp in action.

Use the following command:
```bash
bun run dev
```

## Preview

Once the server is running, you’ll see the dApp interface, which looks like this:

![dApp Preview](https://github.com/Sushants-Git/demo-app/assets/100516354/bf939a2f-3ac1-40f6-882c-c779ee4928ee)

## Additional Notes

- Ensure that you have [Merry](https://docs.garden.finance/developers/merry/) and its components (Orderbook, Filler, Faucet, and the necessary blockchain nodes) correctly set up before running the dApp.
- For more details on using the Garden SDK, check out the [Garden SDK documentation](https://docs.garden.finance/developers/sdk/).

  Usage of GARDEN sdk;
1. Swapping Assets
The primary functionality of the Garden SDK revolves around asset swapping.

2. Multichain Transactions
With the Garden SDK, developers can manage transactions seamlessly across multiple blockchains.

3. Orderbook Management
The SDK provides tools for managing orderbooks, enabling developers to create, match, and execute trades based on predefined rules and market conditions.

4. Community and Support
Developers using the Garden SDK benefit from a supportive community and comprehensive documentation.

If you have any questions or need help, feel free to reach out!
