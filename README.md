# cmsDapp :sparkles:
The aim is to make the system adopt paperless transactions and at the same time, maintain data integrity using blockchain.So we are trying to develop Dapp as a service :heart_eyes:

 <h3> Tech stack used: :octocat: </h3>

<li>Ethereumjs</li>
<li>Maticjs</li>
<li>nodejs</li>
<li>truffle</li>
<li>ganache-cli</li>
<li>solidity</li>

<h3>Installation :gem: </h3>
1.<h4>Voting Dapp</h4>

## 

1. **:round_pushpin: clone the repository.**

   ```shell
   $git clone https://github.com/Aman-zishan/cmsDapp.git

   ```
2. **:checkered_flag: navigate to election folder.**

   ```shell
   $cd election

   ```
3. **:construction: install the dependencies.**

   ```shell
   $npm install

   ```
4. **:diamonds: Run the truffle.**

   ```shell
   #This command executes the smart contract sequentially and sets local blockchain network.(make sure ganache is running)
   
   $truffle migrate --reset

   ```
5. **:dart: Deploy!**
    ```shell
    
    #This command runs the client side application.
    
   $npm run deploy

   ```
   
  <h3>Installation :gem: </h3>
  
2. <h4>Mark submission Dapp</h4> 
  
   
   1. **:round_pushpin: navigate to maticdapp folder.**

   ```shell
   $cd maticdapp

   ```
1. **:checkered_flag: install the dependencies.**

   ```shell
   $npm install

   ```
 3. **:construction: navigate to dapp-ui.**

   ```shell
   $cd dapp-ui

   ```
4. **:diamonds: install dependencies**
    ```shell
   $npm install
5. **:dart: deploy**
    ```shell
   $npm run dev
   ```


