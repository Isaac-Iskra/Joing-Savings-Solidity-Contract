# Joing-Savings-Solidity-Contract

This class project looks at joint savings accounts for a solidity contract.  

Using JavaScript VM and pragma solidity ^0.5.0, I started off with defining the contract and establishing some variables, as seen in the below picture:

![image](https://user-images.githubusercontent.com/90321433/156080738-71c8f8e4-0c50-4692-9fdb-3672161cd8b2.png)

From there, I defined a function that accepts two arguments; a uint variable named 'amount' and a payable address named 'recipient', as seen in the below picture:

![image](https://user-images.githubusercontent.com/90321433/156080939-7c4d274d-d955-498d-af12-9da38a55d74b.png)

Next, I defined a public payable function named 'setAccounts' that will recieve two payable address accounts named 'account1' and 'account2' and added the default fallback function, as seen in the below picture:

![image](https://user-images.githubusercontent.com/90321433/156081077-257807dc-318a-445f-953b-56b42cf93331.png)

This resulted in the buttons appearing and the contract being deployed successfully, as seen in the picture below:

![image](https://user-images.githubusercontent.com/90321433/156081156-6fbb23f2-97f2-4e58-8645-fe265775e72b.png)

Next, we tested the deposit functionality, sending 1 ether as wei, sending 10 ether as wei, and sending 5 ether, as seen in the following pictures:

1) 1 ether as wei:

![image](https://user-images.githubusercontent.com/90321433/156081494-8ae7779c-c689-4dbd-b085-f5e68e9343a4.png)

dummy account addresses provided by the challenge instructions:

![image](https://user-images.githubusercontent.com/90321433/156082190-269cbddf-0114-41ab-81dc-455eeb1c5110.png)

confirmation of transaction:

![image](https://user-images.githubusercontent.com/90321433/156082317-a9bf821d-5bb9-452d-955d-ccb1e4859d48.png)

contract balance:

![image](https://user-images.githubusercontent.com/90321433/156082378-3472a24e-b0e6-4349-bfde-9079a144000b.png)

Now with the remaining sample transactions.

10 ehter as wei:

![image](https://user-images.githubusercontent.com/90321433/156083051-5d1dbd17-a7a6-4a8e-ad95-524525c7e6f4.png)

![image](https://user-images.githubusercontent.com/90321433/156082190-269cbddf-0114-41ab-81dc-455eeb1c5110.png)

![image](https://user-images.githubusercontent.com/90321433/156083177-7dc50aa5-0df9-44a1-b8a6-b8f419b03d6b.png)

![image](https://user-images.githubusercontent.com/90321433/156083223-bfe9b28b-0c85-43de-8e96-f2ec3c696203.png)

1 ether 

![image](https://user-images.githubusercontent.com/90321433/156083392-31279a1c-637a-4d14-9ab4-a389524118c2.png)

![image](https://user-images.githubusercontent.com/90321433/156083484-f39e7532-1017-4c26-b03b-e5202dd24847.png)

![image](https://user-images.githubusercontent.com/90321433/156083520-811f071a-245f-4ec3-b0dc-2d9647e11f6b.png)

From here, we're going to check to make sure that the 'withdraw' button is working properly.  This will be demonstrated by withdrawing 5 ether into accountOne and 10 ether into accountTwo.  There will also be screenshots of 'lastToWithdraw' and 'lastWithdrawAmount' povided.

Screenshot to demonstrate that I added an additional 10 either to the accounts from the last demo of 5 either:

![image](https://user-images.githubusercontent.com/90321433/156084075-3b46fa83-381d-4c2a-aeaf-fcef2443d5bf.png)

![image](https://user-images.githubusercontent.com/90321433/156084089-8f66d1a7-237a-4b18-8e1b-506e07248b3b.png)

accountOne:

![image](https://user-images.githubusercontent.com/90321433/156084158-a6cf0348-3128-4109-b606-c355f325a673.png)

![image](https://user-images.githubusercontent.com/90321433/156084187-ab51a46d-4116-423f-91d0-778dff818d26.png)

![image](https://user-images.githubusercontent.com/90321433/156084224-0e2f8bce-8eaf-4cd1-b4d2-87f8500bb985.png)

accounTwo:

![image](https://user-images.githubusercontent.com/90321433/156084290-2796c2bf-8c2e-4477-9305-ee8e7e362123.png)

![image](https://user-images.githubusercontent.com/90321433/156084323-da26391f-9d9d-4a0b-8a52-2a95377d8b80.png)

![image](https://user-images.githubusercontent.com/90321433/156084354-b7679082-c71f-4232-b6dc-2e75075d9476.png)

The resulting balance of the contract is now zero.
