#  Hello World Ethereum app

main code is in `contracts/HelloWorld.sol`
## Running

1. Install packages

```npm install```

2. Start truffle development local environment 

```npm run truffle-dev```

3. Inside truffle environment run the followin JS code line by line

```var hw```

```HelloWorld.deployed().then( function(deployed) { hw = deployed; } );```

```hw.SayHello.call()```

4. Quit truffle environment

`.exit`