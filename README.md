# Ethereum Solidity Simple Bank
> It's how _I_ like it, fork before using it.

### Setup
```bash
  # clone the repository
  $ git clone https://github.com/mir-nawaz/simpleBank
  # change the current directory
  $ cd simpleBank
  # install ganache and truffle
  $ npm install -g ganache-cli truffle
  # open a new terminal, run below command and keep it alive
  $ ganache-cli
  # compile smart contracts
  $ truffle compile
  # run migrations
  $ truffle migrate
  # run tests
  $ truffle test
```

### Structure
```bash
.
├── README.md           # you're here
├── build               # build folder for solidity 
├── contracts           # contains smart contracts
├── migrations          # contains migrations
├── tests               # contains unit tests
```

**Suggestion:** Every folder name is _singular_ like `contracts`, `migrations`. If you want to add more folders as per your need, make sure they should be singular too (for e.g. `util`, `helper` etc) only for the sake of consistency.

### License
MIT