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
  ##### A smart contract is a program that self-executes when conditions are met. It is transparent, fast, and accurate but the efficacy of the program is entirely             dependant on the developers skill level and intentions.
  
> ###### 3. Explain the difference between a script and a transaction.
 ##### Both script and transaction are Cadence snippets, but are entirely different in terms of functionality. Transactions can access signing accounts, fetch their            storage values, executes on those values, and can contain post conditions. Scripts do not have permission to change data on the blockchain and can only read from        the public account storage.
```diff
- Day_2
```

> ###### 1. What are the 5 Cadence Programming Language Pillars?
 ##### Safety and Security: Safety entails that the smart contract is bug-free and able to carry out it's function. Security is prevention of attacks in the network and        smart contracts. Both safey and security are important because of the immutable nature of blockchain technology.
 ##### Clarity: Code should be easy to read, especially Smart Contract code so that we, as users, can verify it is safe. This is achieved by making the code declarative        and allowing the developer to express their intentions directly. Cadence makes those intentions very clear by design, which, along with readability, make         auditing and reviewing more efficient.
 ##### Approachability: Prior knowledge of programming languages should allow for smooth transtion to Cadence.
 ##### Developer Experience: It should be easy for the developer to have debugging support as they are coding, making the proccess seamless for them from start to        finish.
 ##### Resource Oriented Programming: Cadence’s strong static type system ensures that resources can only exist in one location at a time and cannot be copied or lost          because of a coding mistake. Cadence’s resources directly tie an asset’s ownership to the account that owns it by saving the resource in the account’s storage.          As a result, ownership isn’t centralized in a smart contract’s storage. Each account owns its assets, and the assets can be transferred freely between accounts          without the need for arbitration by a central smart contract.
> ###### 2. In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful (you don't have to answer this for #5)?
 ##### The 5 Cadence Pillars are useful because in reality, programming languages all strive to perfect these areas so more developers will use their language and build        a vast ecosystem.

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
![alt text](https://github.com/thetafuelz/quest-submissions/blob/39e442a6e4d4629dcdeadf71e3d9c191fcdfc2c3/img/Ch2D2_1.JPG)
![alt text](https://github.com/thetafuelz/quest-submissions/blob/d441b0fcef9e8067a2f4794fe0a9adfda1900a95/img/Ch2D2_2.JPG)
![alt text](https://github.com/thetafuelz/quest-submissions/blob/d441b0fcef9e8067a2f4794fe0a9adfda1900a95/img/Ch2D2_3.JPG)
```diff
- Day_3
```
> ###### 1. In a script, initialize an array (that has length == 3) of your favourite people, represented as Strings, and log it.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/dc004595da7c67199033a8c2e35e76b7c4554b80/img/C2D3_Q1.JPG) 
> ###### 2. In a script, initialize a dictionary that maps the Strings Facebook, Instagram, Twitter, YouTube, Reddit, and LinkedIn to a UInt64 that represents the order in which you use them from most to least. For example, YouTube --> 1, Reddit --> 2, etc. If you've never used one before, map it to 0!
![alt text](https://github.com/thetafuelz/quest-submissions/blob/dc004595da7c67199033a8c2e35e76b7c4554b80/img/C2D3_Q2.JPG) 
> ###### 3. Explain what the force unwrap operator ! does, with an example different from the one I showed you (you can just change the type).
   ##### A force unwrap operator ! returns the value inside an optional if it contains a value, or panics and aborts the execution if the optional has no value,                  the optional value is nil.
   ![alt text](https://github.com/thetafuelz/quest-submissions/blob/449a71bf5ef0cb0c40d02850b1ca15f3e0af9356/img/C2D3_Q3.JPG)
   
> ###### 4. Using this picture below, explain...a)What the error message means b)Why we're getting this error c)How to fix it
  ##### a) The error message "mismatched types. expected 'String', got 'String?'" means it was expecting a string but receieved a string optional.
  ##### b) We are getting this message because the output can also be nil so an unwrap operator must be used. 
  ##### c) We can fix this error by placing an force unwrap operator (!) after the return statement to unwrap the optional type and return the actual value type.
```diff

- Day_4
```
> ###### 1. Deploy a new contract that has a Struct of your choosing inside of it (must be different than Profile).
> ###### 2. Create a dictionary or array that contains the Struct you defined.
> ###### 3. Create a function to add to that array/dictionary.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/f85569f8132df2c11f17375f106ac04bb84136e7/img/C2D4_Q123.JPG)
> ###### 4. Add a transaction to call that function in step 3.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/f85569f8132df2c11f17375f106ac04bb84136e7/img/C2D4_Q4.JPG)
> ###### 5. Add a script to read the Struct you defined
![alt text](https://github.com/thetafuelz/quest-submissions/blob/f85569f8132df2c11f17375f106ac04bb84136e7/img/C2D4_Q5.JPG)

```diff
@@ Chapter_3 Quests @@
```
```diff
- Day_1
```
> ###### 1. In words, list 3 reasons why structs are different from resources.
 ##### Structs can be copied, overwritten, and created at any time. Resources cannot be copied, cannot be lost/overwritten, and cannot be created whenver you want. Aside from that resources can only exist in 1 location at a time and must be used EXACTLY ONCE. Use ```create``` keyword to create and must be moved or destroyed using ```destroy ``` at the end of a function. Overall resources are much harder to deal with.
 
> ###### 2. Describe a situation where a resource might be better to use than a struct.
##### Resources are better utilized when creating NFT's. They can only have one owner, cannot be copied, and cannot be accidentally or maliciously lost or duplicated.  They also can only be created in the contract and nowhere else. This will keep the owner's mind at ease knowing that their NFT is safe and stored in their account.

> ###### 3. What is the keyword to make a new resource?
##### ```create```is used to make a new resource. 

> ###### 4. Can a resource be created in a script or transaction (assuming there isn't a public function to create one)?
##### No, a resource cannot be created in a script or transaction. It can only be created in the contract, unlike structs.

> ###### 5. What is the type of the resource below?
##### The resource type is called Jacob.?

> ###### 6. Let's play the "I Spy" game from when we were kids. I Spy 4 things wrong with this code. Please fix them.
##### 1. pub fun createJacob(): ```@``` Jacob {
##### 2.&3. let myJacob ```<-``` ```create``` Jacob() 
##### 4. return ```<-``` myJacob

```diff
- Day_2
```
>###### 1. Write your own smart contract that contains two state variables: an array of resources, and a dictionary of resources. Add functions to remove and add to each of them. They must be different from the examples above.
```
pub contract Test {

    pub var arrayOfBallerz: @[Ballerz]

    pub var dictionaryOfBallerz: @{String: Ballerz}

    pub resource Ballerz {
        pub let ballerzName: String
        init() {
            self.ballerzName = "Player"
        }
    }

    pub fun addToBaller(ballerz: @Ballerz) {
        self.arrayOfBallerz.append(<- ballerz)
    }

    pub fun removeFromBallerz(index: Int): @Ballerz {
        return <- self.arrayOfBallerz.remove(at: index)
    }


    pub fun addBallerz(ballerz: @Ballerz) {
        let key = ballerz.ballerzName     
        let oldBallerzName <- self.dictionaryOfBallerz[key] <- ballerz
        destroy oldBallerzName
    }

    pub fun removeBallerz(key: String): @Ballerz {
        let ballerz <- self.dictionaryOfBallerz.remove(key: key)!
        return <- ballerz
    }

    init() {
        self.dictionaryOfBallerz <- {}
        self.arrayOfBallerz <- []
    }

}```

```diff
- Day_3
```
>###### 1. Define your own contract that stores a dictionary of resources. Add a function to get a reference to one of the resources in the dictionary.
>###### 2. Create a script that reads information from that resource using the reference from the function you defined in part 1.
>###### 3. Explain, in your own words, why references can be useful in Cadence.
#####

```diff
- Day_4
```
>###### 1. Explain, in your own words, the 2 things resource interfaces can be used for (we went over both in today's content)
#####
>###### 2. Define your own contract. Make your own resource interface and a resource that implements the interface. Create 2 functions. In the 1st function, show an example of not restricting the type of the resource and accessing its content. In the 2nd function, show an example of restricting the type of the resource and NOT being able to access its content.
>###### 3. How would we fix this code?
#####

```diff
- Day_5
```
>###### 1. For today's quest, you will be looking at a contract and a script. You will be looking at 4 variables (a, b, c, d) and 3 functions (publicFunc, contractFunc, privateFunc) defined in SomeContract. In each AREA (1, 2, 3, and 4), I want you to do the following: for each variable (a, b, c, and d), tell me in which areas they can be read (read scope) and which areas they can be modified (write scope). For each function (publicFunc, contractFunc, and privateFunc), simply tell me where they can be called.

```diff
@@ Chapter_4 Quests @@
```
```diff
- Day_1
```
>###### 1. Explain what lives inside of an account.
#####
>###### 2. What is the difference between the /storage/, /public/, and /private/ paths?
#####
>###### 3. What does .save() do? What does .load() do? What does .borrow() do?
#####
>###### 4. Explain why we couldn't save something to our account storage inside of a script.
#####
>###### 5. Explain why I couldn't save something to your account.
#####
>###### 6. Define a contract that returns a resource that has at least 1 field in it. Then, write 2 transactions:
            i. A transaction that first saves the resource to account storage, then loads it out of account storage, 
            logs a field inside the resource, and destroys it.
            ii. A transaction that first saves the resource to account storage, then borrows a reference to it, 
            and logs a field inside the resource.
            

```diff
- Day_2
```
>###### 1. What does .link() do?
#####
>###### 2. In your own words (no code), explain how we can use resource interfaces to only expose certain things to the /public/ path.
#####
>###### 3. Deploy a contract that contains a resource that implements a resource interface. Then, do the following:

            i. In a transaction, save the resource to storage and link it to the public with the restrictive interface.

            ii. Run a script that tries to access a non-exposed field in the resource interface, and see the error pop up.

            iii. Run the script and access something you CAN read from. Return it from the script.

```diff
- Day_3
```
>###### 1. Why did we add a Collection to this contract? List the two main reasons.
#####
>###### 2. What do you have to do if you have resources "nested" inside of another resource? ("Nested resources")
#####
>###### 3. Brainstorm some extra things we may want to add to this contract. Think about what might be problematic with this contract and how we could fix it.

          Idea #1: Do we really want everyone to be able to mint an NFT? 🤔.

          Idea #2: If we want to read information about our NFTs inside our Collection, right now we have to take it out of the Collection to do so. Is this good?
          
```diff
- Day_4
```
>###### 1. Because we had a LOT to talk about during this Chapter, I want you to do the following:
          Take our NFT contract so far and add comments to every single resource or function explaining what it's doing in your own words. 
          Something like this:

```diff
@@ Chapter_5 Quests @@
```
```diff
- Day_1
```
>###### 1. Describe what an event is, and why it might be useful to a client.
#####
>###### 2. Deploy a contract with an event in it, and emit the event somewhere else in the contract indicating that it happened.
#####
>###### 3. Using the contract in step 2), add some pre conditions and post conditions to your contract to get used to writing them out.
#####
>###### 4. For each of the functions below (numberOne, numberTwo, numberThree), follow the instructions.

```diff
- Day_2
```
>###### 1. Explain why standards can be beneficial to the Flow ecosystem.
#####
>###### 2. What is YOUR favourite food?
#####
>###### 3. Please fix this code (Hint: There are two things wrong):

```diff
- Day_3
```
>###### 1. What does "force casting" with as! do? Why is it useful in our Collection?
#####
>###### 2. What does auth do? When do we use it?
#####
>###### 3. This last quest will be your most difficult yet. Take this contract:
            and add a function called borrowAuthNFT just like we did in the section called "The Problem" above. Then, find a way to make it publically accessible to other people so they can read our NFT's metadata. Then, run a script to display the NFTs metadata for a certain id.

You will have to write all the transactions to set up the accounts, mint the NFTs, and then the scripts to read the NFT's metadata. We have done most of this in the chapters up to this point, so you can look for help there :)
