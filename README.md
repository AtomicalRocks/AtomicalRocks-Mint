# AtomicalRocks-Mint

### How to mint?
This tutorial is for those who already have the Atomicals environment installed. If you haven't installed it yet, we recommend checking https://github.com/atomicals/atomicals-js.

### Step 1
Before attempting to mint any AtomicalRocks, you have to check the already minted items:

```
Use get-container-items to query minted items (limit specifies the number of entries, suggested value is 10; offset indicates the starting point for the query, suggested value is 0).

$ yarn cli get-container-items "#atomicalrocks" limit offset
```
### Step 2
We have a total supply of 100 Atomicals Rocks.
To mint, you need to download the .json file of the item you want to mint.
You can find all 100 .json files here: https://github.com/AtomicalRocks/AtomicalRocks-Mint/tree/main/Rocks.

### Step 3
In your command line, run the following command:
```
yarn cli mint-item "#atomicalrocks" "item-name" "path/to/item-name.json" --satsbyte=1
```
Replace "item-name" with the number of the .json file you downloaded earlier.

Example:
```
yarn cli mint-item "#atomicalrocks" "2" "C:\Users\AtomicalRocks\Desktop\item-2.json" --satsbyte=60
```

###Done
Once your transaction is confirmed in the mempool, you will receive your AtomicalRock at your primary address.
