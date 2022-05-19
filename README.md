##### quest-submissions
```diff
@@ Chapter_1 Quests @@
```

```diff
- Day_1
```

> ###### 1. Explain what the Blockchain is in your own words.
  ##### A blockchain is a public, decentralized, distributed, digital ledger that records blocks of data(transactions) connected by cryptography.
  
> ###### 2. Explain what a Smart Contract is. You can read this to help you, but you don't have to: https://www.ibm.com/topics/smart-contracts
  ##### A smart contract is a program that self-executes when conditions are met. It is transparent, fast, and accurate but the efficacy of the program is entirely dependant on the developers skill level and intentions.
  
> ###### 3. Explain the difference between a script and a transaction.
 ##### Both script and transaction are Cadence snippets, but are entirely different in terms of functionality. Transactions can access signing accounts, fetch their storage values, executes on those values, and can contain post conditions. Scripts do not have permission to change data on the blockchain and can only read from the public account storage.
```diff
- Day_2
```

> ###### 1. What are the 5 Cadence Programming Language Pillars?
 ##### Safety and Security: Safety entails that the smart contract is bug-free and able to carry out it's function. Security is prevention of attacks in the network and smart contracts. Both safey and security are important because of the immutable nature of blockchain technology.
 ##### Clarity: Code should be easy to read, especially Smart Contract code so that we, as users, can verify it is safe. This is achieved by making the code declarative and allowing the developer to express their intentions directly. Cadence makes those intentions very clear by design, which, along with readability, make auditing and reviewing more efficient.
 ##### Approachability: Prior knowledge of programming languages should allow for smooth transtion to Cadence.
 ##### Developer Experience: It should be easy for the developer to have debugging support as they are coding, making the proccess seamless for them from start to finish.
 ##### Resource Oriented Programming: Cadence’s strong static type system ensures that resources can only exist in one location at a time and cannot be copied or lost because of a coding mistake. Cadence’s resources directly tie an asset’s ownership to the account that owns it by saving the resource in the account’s storage. As a result, ownership isn’t centralized in a smart contract’s storage. Each account owns its assets, and the assets can be transferred freely between accounts without the need for arbitration by a central smart contract.
> ###### 2. In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful (you don't have to answer this for #5)?
 ##### The 5 Cadence Pillars are useful because in reality, programming languages all strive to perfect these areas so more developers will use their language and build a vast ecosystem.

```diff
@@ Chapter_2 Quests @@
```
```diff
- Day_1
```
1.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/cdb392f51b2696468bb0311c9df76b82480a7e8d/img/Ch2D1.JPG)
2.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/cdb392f51b2696468bb0311c9df76b82480a7e8d/img/Ch2D2.JPG)

```diff
- Day_2
```
> ###### 1. Explain why we wouldn't call changeGreeting in a script.
   ##### We wouldn't call changeGreeting in a script because a script is only to view state not modify it, so changing the greeting can only be done in the transaction.
> ###### 2. What does the AuthAccount mean in the prepare phase of the transaction?
   ##### AuthAccount means you can access your data that is stored on your account unlike Ethereum where the data is stored on the smart contract.
> ###### 3. What is the difference between the prepare phase and the execute phase in the transaction?
   ##### Prepare phase accesses data and the execute phase chases data on the smart contract.
> ###### 4. This is the hardest quest so far, so if it takes you some time, do not worry! I can help you in the Discord if you have questions.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/cdb392f51b2696468bb0311c9df76b82480a7e8d/img/Ch2D2_1.JPG)
![alt text](https://github.com/thetafuelz/quest-submissions/blob/cdb392f51b2696468bb0311c9df76b82480a7e8d/img/Ch2D2_2.JPG)
![alt text](https://github.com/thetafuelz/quest-submissions/blob/cdb392f51b2696468bb0311c9df76b82480a7e8d/img/Ch2D2_3.JPG)
```diff
- Day_3
```
> ###### 1. In a script, initialize an array (that has length == 3) of your favourite people, represented as Strings, and log it.

> ###### 2. In a script, initialize a dictionary that maps the Strings Facebook, Instagram, Twitter, YouTube, Reddit, and LinkedIn to a UInt64 that represents the order in which you use them from most to least. For example, YouTube --> 1, Reddit --> 2, etc. If you've never used one before, map it to 0!

> ###### 3. Explain what the force unwrap operator ! does, with an example different from the one I showed you (you can just change the type).

> ###### 4. Using this picture below, explain...

What the error message means
Why we're getting this error
How to fix it

```diff
- Day_4
```
> ###### 1. Deploy a new contract that has a Struct of your choosing inside of it (must be different than Profile).

> ###### 2. Create a dictionary or array that contains the Struct you defined.

> ###### 3. Create a function to add to that array/dictionary.

> ###### 4. Add a transaction to call that function in step 3.

> ###### 5. Add a script to read the Struct you defined
https://github.com/thetafuelz/quest-submissions/blob/39e442a6e4d4629dcdeadf71e3d9c191fcdfc2c3/img/Ch2D2_1.JPG
https://github.com/thetafuelz/quest-submissions/blob/d441b0fcef9e8067a2f4794fe0a9adfda1900a95/img/Ch2D2_2.JPG
https://github.com/thetafuelz/quest-submissions/blob/d441b0fcef9e8067a2f4794fe0a9adfda1900a95/img/Ch2D2_3.JPG
```diff
@@ Chapter_3 Quests @@
```
```diff
- Day_1
```
```diff
- Day_2
```
```diff
- Day_3
```
```diff
- Day_4
```
```diff
- Day_5
```
```diff
@@ Chapter_4 Quests @@
```
```diff
- Day_1
```
```diff
- Day_2
```
```diff
- Day_3
```
```diff
- Day_4
```
```diff
@@ Chapter_5 Quests @@
```
```diff
- Day_1
```
```diff
- Day_3
```
```diff
- Day_3
```
