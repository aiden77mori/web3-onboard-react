# React Demo

A repository to demonstrate a basic integration of 
[Web3-Onboard](https://github.com/blocknative/web3-onboard) official docs for W3O can be found [here](https://onboard.blocknative.com/docs/modules/core#install).
This project uses [React App Rewired](https://www.npmjs.com/package/react-app-rewired) for building, checkout `config-overrides.js` for details.
For detailed documentation, head to [docs.blocknative.com](https://docs.blocknative.com)


<div align="center">
  <img style="border-radius: 8px" width="75%" src="assets/react-demo-updated.png">
</div>

View live demo [here](https://reactdemo.blocknative.com/)!

## Getting started

Clone the repo:

```bash
git clone https://github.com/aiden77mori/web3-onboard-react.git
```

Navigate to the project directory:

```bash
cd web3-onboard-react
```

Install the dependencies:

```bash
yarn
```

Start the development server:

```bash
yarn start
```

The project will be running on [localhost:3000](http://localhost:3000)

### SSL
Some wallets require that the website within which it runs be using a https 
connection. If you are testing one of these wallets, Ledger is one, then you have
two options:
 1. Setup a valid certificate for localhost using [this guide](https://www.freecodecamp.org/news/how-to-set-up-https-locally-with-create-react-app/).
 2. Allow invalid certificates for resources loaded from localhost by navigating here within a chrome based browser: [chrome://flags/#allow-insecure-localhost](chrome://flags/#allow-insecure-localhost)
