# Codius Smart Oracle system

Welcome to Codius. To get started, check out the [Codius whitepaper](https://github.com/codius/codius/wiki/Smart-Oracles:-A-Simple,-Powerful-Approach-to-Smart-Contracts) and go to [codius.org](http://codius.org).

To get involved in the community check out the [forum](https://groups.google.com/forum/#!forum/codius) and the chat room on Gitter: [![Gitter chat](https://badges.gitter.im/codius/codius-chat.png)](https://gitter.im/codius/codius-chat)


## Project Status

As of Monday, August 4th, all of the Codius code is open source!

+ [__codius-engine__](https://github.com/codius/codius-engine) - the system responsible for executing contract code
+ [__codius-host__](https://github.com/codius/codius-host) - the smart oracle software that allows users to upload code, get unique tokens for their contract, and in the near future will handle billing
+ [__codius-cli__](https://github.com/codius/codius-cli) - the command line interface for interacting with the engine
+ [__node-sandbox__](https://github.com/codius/node-sandbox) - the pure javascript sandbox we're using while we work on getting Google's Native Client integrated
+ [__example-helloworld__](https://github.com/codius/example-helloworld) - a simple hello world contract
+ [__example-require__](https://github.com/codius/example-require) - a sample contract demonstrating how require works inside the sandbox
+ [__example-bitcoin__](https://github.com/codius/example-bitcoin) - a sample bitcoin contract that demonstrates how bitcoinjs can be used inside the sandbox
+ [__example-webserver__](https://github.com/codius/example-webserver/) - a sample contract demonstrating running a simple webserver inside a contract


We pulled multiple late nights to try to wrangle together an impressive demo for you all but we'll need a couple more days to make that happen. That said, we wanted to get all of this open sourced as soon as we could to get you involved in building this!

If you're interested, play around with the code, ask us questions on the forum or live chat, and feel free to submit pull requests!

## Project Roadmap

- &#10003; Develop Javascript prototype of engine, host, and sandbox (8/4)
- &#10003; Open source all code (8/4)
- &#9744; Multisig Bitcoin demo enabling decentralized pull payment API (+ spending limits)
- &#9744; Use [chain.com](https://chain.com) or other similar mechanism to give contracts access to blockchain data
- &#9744; Fully port Express.js into a contract
- &#9744; Get Python interpreter running in Native Client and integrated into codius-engine
- &#9744; Set up basic codius-host billing system to fund [tokens](https://github.com/codius/codius-host/commit/818c8d4d2fdbea9fb62caaa0f7a601a8b2fea530)
- &#9744; Finish [porting Node.js](https://github.com/codius/codius-lang-nodejs) to Native Client
- &#9744; Automatic mechanism for finding Codius hosts
- &#9744; Create a contract insurance/identity scheme to enable contract enforcement without escrow