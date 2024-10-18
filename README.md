# Team members
```
Suyash Kamath 21102B0044
Atharv Deshmukh 21102B0053
Vivek Yadav 21102B0042
Atish Limje 21102B0036
```
 
 # Install hardhat
 npm install --save-dev hardhat
 
# Open 3 terminals

Navigate to project in each of them


# First Terminal 

  npm start


# Second Terminal 

 npx hardhat node
 
 # Third Terminal 

npx hardhat run scripts/deploy.js --network localhost

It will give a string in your terminal  which is contractAddress. 

You should copy this string and paste in src/App.js as a value of contractAddress.


# Your app start Running ...


```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

