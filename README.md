# Mint-ERC20-Token-----LW3
A Simple Soldity Project to create/mint ERC20 token. Made in Remix, and payed using SepoliaETH.

 </br>
 </br>
  </br>
   </br>
    </br>


// My Created Token // 
```
Contract Address:  0xEf4394B5221422f6925827E855AB84A90a2D1C75
```
Can be checked on the 'Sepolia Etherscan'.


 </br>
  </br>


   
// Notes //
 </br>

|  The '5000' in the code mentions the amount of token to be created. Feel free to change that if you want a different amount.
 </br>

|  This code doesn't have feature to increase token later on, after deployment.
To add MINT functionality, use the below code. Copy it inside the contract, at the end.
```
    //to mint more of this token
    function mint() public {
        _mint(msg.sender, 5000 * (10 ** 18));
    }
```
    
(Again, the 5000 here is just a random number set by me. Feel free to assign a different value, that is to be minted everytime the mint function is called/executed)



