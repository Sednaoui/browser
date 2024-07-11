# Getting Started with a Lit SDK Browser Implementation

This is a very simple example repository for getting started with a browser implementation of the Lit SDK. All it will do is connect an instance of the `LitNodeClient` to the Lit Network. If you are searching for more developed uses of Lit, the [Developer Guides Code](https://github.com/LIT-Protocol/developer-guides-code) repository is for you. 

## Using This Repository

After downloading this repository, you will need to install the necessary dependencies and run the environment setup with the following commands:

```
npm install
```
```
npm run dev
```

Afterward, your terminal should inform you that the application is being displayed at `http://localhost:5173/`. Clicking the `Connect` button will send a log to your browser, informing you of the connection to the Lit Network.

# Other Frameworks

If you would like to use frameworks other than React, a repository similar to this one can be setup using the steps below:
1. `npm create vite@latest`
2. Choose project name, framework, and configuration of choice.
3. `npm install @lit-protocol/lit-node-client`
4. Be sure to use Polyfills since this is a browser implementation. Make your `vite.config` file similar to the one in this repository.


