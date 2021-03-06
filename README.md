# Quest Submissions 

## Chapter 1 Day 1 Quest

## 1. Explain what the Blockchain is in your own words. 
 
 The Blockchain can be most closely compared to google cloud or Icloud in the sense that it stores data, however on the blockchain everything is open and data cannot be changed unless a transaction occurs or a smart contract has a function that allows data to be removed. The term Blockchain stems from the way the data is stored. On the Blockchain all data is collected in blocks and then chained together like a train with carts attached. The data is never ending and is transparent for anyone to see at any given moment. 

## 2. Explain what a Smart Contract is.

 Smart contracts are programs deployed by developers to give functionatliy and access to users to interact with the blockchain. Think of Smart contracts like the laws of the blockchain except with smart contracts there is no need for politions, campaigning, or having to vote your bill into a law. Smart Contracts can be deployed instataneiously without any approval from anybody other than the developer. There is no paper work or third party involved, with this comes great risk and reward.
 
 ## 3. Explain the difference between a script and a transaction.
 
 A transaction is an interaction with the blockchain in which data is being altered and funds are being exchanged between parties. A script however is free and its main function is to view data on the blockchain. 

## Chapter 1 Day 2 Quest 

## 1. What are the 5 Cadence Programming Language Pillars?

 1. Safety and Security 
 2. Clarity
 3. Approachability
 4. Developer Experience
 5. Resource Oriented Programming

## 2. In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful?

1.) Safety and Security are an important and vital role in every aspect of our lives. From the way we use to the internet to the way we're able to provide for our families all of it stems by how effectively we're able to provide Safety and Security for those we're responsible for, in this sense it'd be the developers and users interacting with the Cadence program. People can rally behind something they trust and trust is built in part by providing Safety and Security, Which is a great pivot for the next pillar, 2.) Clarity. It can be argued that without Clarity there is no Safety and Security. Im a firm believer that many of the worlds problems are misunderstandings/misconceptions which could be avoided if things were provided with a little more Clarity. Things should run smoothly for all parties involved and thats only possible if clarity is provided for all sides. The next two pillars go hand in hand in my opinion, 3.) Approachability and 4.) Developer Experience. Without the two how can one expect to reach the masses. Whether it be in our career, relationships, or in this case The Developer Experience things should be Approachable in the sense that the user doesnt run for the hills at the first sign of unfamiliarity. Change is constant and yet its one of the things humans fight the most, being able to provide a certain level of approachability for everybody while also supporting and maximizing the Developer Experience is the embodiment of what flow is all about. HAHA for someone who has never coded before and that is new to Blockchain this one took me awhile. How I understood this pillar is that while all other blockchains use a ledger like system to show proof of ownership, Cadence/Flow uses a 5.) Resourse Oriented Language that allows an assest to be directly tied to an account instead of on a single central smart contract. This means that no matter how many wallets I create all assests held amongst these wallets will show ownership from the account and not the individual wallet. As opposed to Ethereum where I can crete as many wallets as I please and the only way to track ownership of all my assests is if you did some fine detective work and found an instance where I may have interacted with a smart contract amongst the wallets themselves.

# Chapter 2 Day 1 Quest
![JacobTuckerContract](https://user-images.githubusercontent.com/106129460/173203493-618ec706-eb18-4415-9195-ee86b69e29d5.png)

![JACOBscript](https://user-images.githubusercontent.com/106129460/173203774-68780eaf-bddf-49b9-a959-80ff855d83a9.png)

# Chapter 2 Day 2 Quest

## 1. Explain why we wouldn't call changeGreeting in a script.

A script cannot modify or change the state. A script can only view data on the blockchain.

## 2. What does the AuthAccount mean in the prepare phase of the transaction?

It's pretty much a digital signature giving permission to the blockchain to access the data stored in your account.

## 3. What is the difference between the prepare phase and the execute phase in the transaction?

In the Execute phase you're calling functions and changing the data on the blockchain, on the prepare phase on the transaction you're accessing the data in your account. The prepare phase is capable of doing what the execute phase does but at the cost of clarity in reading the code. 

## 4. This is the hardest quest so far, so if it takes you some time, do not worry! I can help you in the Discord if you have questions.

## Add two new things inside your contract:

A variable named myNumber that has type Int (set it to 0 when the contract is deployed)
A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber
Add a script that reads myNumber from the contract

Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.

![myNumber contract](https://user-images.githubusercontent.com/106129460/173244737-eef51d2d-6f1f-4e14-9857-5a6590d8e217.png)

![myNumber Script](https://user-images.githubusercontent.com/106129460/173244746-072e56fb-081e-4a88-b04e-26216cba9f28.png)

![myNumber Transaction](https://user-images.githubusercontent.com/106129460/173244753-006a6767-592a-49b1-95b2-4299b585d1dc.png)

# Chapter 2 Day 3 Quest

## 1. In a script, initialize an array (that has length == 3) of your favourite people, represented as Strings, and log it.

![favorite people](https://user-images.githubusercontent.com/106129460/173716128-1f6973ef-3113-4bc5-8324-4e9d03316318.png)

## 2. In a script, initialize a dictionary that maps the Strings Facebook, Instagram, Twitter, YouTube, Reddit, and LinkedIn to a UInt64 that represents the order in which you use them from most to least. For example, YouTube --> 1, Reddit --> 2, etc. If you've never used one before, map it to 0!

![dictionary string social media](https://user-images.githubusercontent.com/106129460/173716145-cae9e8bc-2b5a-4888-b820-0cb19f6b0fab.png)

## 3. Explain what the force unwrap operator ! does, with an example different from the one I showed you (you can just change the type).

The force unwrap operator "!" foricibly uses an action if something is nil, takes the optional away.
Example with Error ![Force unwrap op](https://user-images.githubusercontent.com/106129460/173716857-5632eb14-d086-4bee-a1fb-25a795360755.png)

Example Fixed ![force unwrap op no error](https://user-images.githubusercontent.com/106129460/173716156-d3b0dc5b-a053-42e6-9d35-0f8a690651a0.png)

## 4. Using this picture below, explain What the error message means, Why we're getting this error, and How to fix it

![whats the error](https://user-images.githubusercontent.com/106129460/173717270-2f1df270-4831-4a8a-a509-634dc14d7b81.png)

### Answer
We're receiving an error message because the type in the Script is an optional. This means our type is either a String or nil. In order to fix the issue we'd use the force unwrap operator to unwrap our String as shown below ![! fixed example](https://user-images.githubusercontent.com/106129460/173718767-cb5b63cf-29cb-4041-b7b2-7e69bd1b3666.png)
### OR
We could make our String into an optional type by adding ? behind it as shown below
![fixed example](https://user-images.githubusercontent.com/106129460/173718669-3bb1cd57-d275-4561-a0bf-965978a07d7b.png)

# Chapter 2 Day 4 Quest

## 1. Deploy a new contract that has a Struct of your choosing inside of it (must be different than Profile).

## 2. Create a dictionary or array that contains the Struct you defined.

## 3. Create a function to add to that array/dictionary.

## 4. Add a transaction to call that function in step 3.

## 5. Add a script to read the Struct you defined.






