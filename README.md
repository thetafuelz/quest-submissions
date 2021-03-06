##### quest-submissions
```diff
@@ Chapter_1 Quests @@
```

```diff
- CH.1 Day_1
```

> ###### 1. Explain what the Blockchain is in your own words.
  ##### A blockchain is a public, decentralized, distributed, digital ledger that records blocks of data(transactions) connected by cryptography.
  
> ###### 2. Explain what a Smart Contract is. You can read this to help you, but you don't have to: https://www.ibm.com/topics/smart-contracts
  ##### A smart contract is a program that self-executes when conditions are met. It is transparent, fast, and accurate but the efficacy of the program is entirely             dependant on the developers skill level and intentions.
  
> ###### 3. Explain the difference between a script and a transaction.
 ##### Both script and transaction are Cadence snippets, but are entirely different in terms of functionality. Transactions can access signing accounts, fetch their            storage values, executes on those values, and can contain post conditions. Scripts do not have permission to change data on the blockchain and can only read from        the public account storage.
```diff
- CH.1 Day_2
```

> ###### 1. What are the 5 Cadence Programming Language Pillars?
 ##### Safety and Security: Safety entails that the smart contract is bug-free and able to carry out it's function. Security is prevention of attacks in the network and        smart contracts. Both safey and security are important because of the immutable nature of blockchain technology.
 ##### Clarity: Code should be easy to read, especially Smart Contract code so that we, as users, can verify it is safe. This is achieved by making the code declarative        and allowing the developer to express their intentions directly. Cadence makes those intentions very clear by design, which, along with readability, make         auditing and reviewing more efficient.
 ##### Approachability: Prior knowledge of programming languages should allow for smooth transtion to Cadence.
 ##### Developer Experience: It should be easy for the developer to have debugging support as they are coding, making the proccess seamless for them from start to        finish.
 ##### Resource Oriented Programming: Cadence???s strong static type system ensures that resources can only exist in one location at a time and cannot be copied or lost          because of a coding mistake. Cadence???s resources directly tie an asset???s ownership to the account that owns it by saving the resource in the account???s storage.          As a result, ownership isn???t centralized in a smart contract???s storage. Each account owns its assets, and the assets can be transferred freely between accounts          without the need for arbitration by a central smart contract.
> ###### 2. In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful (you don't have to answer this for #5)?
 ##### The 5 Cadence Pillars are useful because in reality, programming languages all strive to perfect these areas so more developers will use their language and build        a vast ecosystem.

```diff
@@ Chapter_2 Quests @@
```
```diff
- CH.2 Day_1
```
1.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/cdb392f51b2696468bb0311c9df76b82480a7e8d/img/Ch2D1.JPG)
2.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/cdb392f51b2696468bb0311c9df76b82480a7e8d/img/Ch2D2.JPG)

```diff
- CH.2 Day_2
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
- CH.2 Day_3
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

- CH.2 Day_4
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
- CH.3 Day_1
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
- CH.3 Day_2
```
>###### 1. Write your own smart contract that contains two state variables: an array of resources, and a dictionary of resources. Add functions to remove and add to each of them. They must be different from the examples above.
```cadence
pub contract Test {

    pub var arrayOf: @[Ballerz]

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

}
```
/end

```diff
- CH.3 Day_3
```
>###### 1. Define your own contract that stores a dictionary of resources. Add a function to get a reference to one of the resources in the dictionary.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/6227408663b9a3d2fa060441c00aa80a4f2f645d/img/Ch3D3_Q1.JPG)

>###### 2. Create a script that reads information from that resource using the reference from the function you defined in part 1.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/6227408663b9a3d2fa060441c00aa80a4f2f645d/img/Ch3D3_Q2.JPG)

>###### 3. Explain, in your own words, why references can be useful in Cadence.
##### References are extrememly useful, esp. with ```resources```, because it allows you to keep the object at it's current location and still be able to reference as well as update it.

```diff
- CH.3 Day_4
```
>###### 1. Explain, in your own words, the 2 things resource interfaces can be used for (we went over both in today's content)
##### There are 3 kinds of interfaces: structure, resource, and contract. Resource interfaces can be used for restricting access to parts of the resource and secondly can be used as a requirement for something to be implemented.
>###### 2. Define your own contract. Make your own resource interface and a resource that implements the interface. Create 2 functions. In the 1st function, show an example of not restricting the type of the resource and accessing its content. In the 2nd function, show an example of restricting the type of the resource and NOT being able to access its content.
```cadence

```
>###### 3. How would we fix this code?
![alt text](https://github.com/thetafuelz/quest-submissions/blob/12bad649c48d08b0a04bde15e23bde867cbed8ab/img/Ch3D4_Q3.JPG)

```diff
- CH.3 Day_5
```
>###### 1. For today's quest, you will be looking at a contract and a script. You will be looking at 4 variables (a, b, c, d) and 3 functions (publicFunc, contractFunc, privateFunc) defined in SomeContract. In each AREA (1, 2, 3, and 4), I want you to do the following: for each variable (a, b, c, and d), tell me in which areas they can be read (read scope) and which areas they can be modified (write scope). For each function (publicFunc, contractFunc, and privateFunc), simply tell me where they can be called.
>
```cadence
access(all) contract SomeContract {
    pub var testStruct: SomeStruct

    pub struct SomeStruct {

        //
        // 4 Variables
        //

        pub(set) var a: String

        pub var b: String

        access(contract) var c: String

        access(self) var d: String

        //
        // 3 Functions
        //

        pub fun publicFunc() {}

        access(contract) fun contractFunc() {}

        access(self) fun privateFunc() {}


        pub fun structFunc() {
            /**************/
            /*** AREA 1 ***/
            /**************/

            // (a) Read: Y Write: Y
            // (b) Read: Y Write: Y
            // (c) Read: Y Write: Y
            // (d) Read: Y Write: Y

            // publicFunc() - Called Here: Y
            // contractFunc() - Called Here: Y
            // privateFunc() - Called Here: Y
        }

        init() {
            self.a = "a"
            self.b = "b"
            self.c = "c"
            self.d = "d"
        }
    }

    pub resource SomeResource {
        pub var e: Int

        pub fun resourceFunc() {
            /**************/
            /*** AREA 2 ***/
            /**************/

            // (a) Read: Y Write: Y
            // (b) Read: Y Write: N
            // (c) Read: Y Write: N
            // (d) Read: N Write: N

            // publicFunc() - Called Here: Y
            // contractFunc() - Called Here: Y
            // privateFunc() - Called Here: N
        }

        init() {
            self.e = 17
        }
    }

    pub fun createSomeResource(): @SomeResource {
        return <- create SomeResource()
    }

    pub fun questsAreFun() {
        /**************/
        /*** AREA 3 ****/
        /**************/
        // (a) Read: Y Write: Y
        // (b) Read: Y Write: N
        // (c) Read: Y Write: N
        // (d) Read: N Write: N

        // publicFunc() - Called Here: Y
        // contractFunc() - Called Here: Y
        // privateFunc() - Called Here: N
    }

    init() {
        self.testStruct = SomeStruct()
    }
}



import SomeContract from 0x01

pub fun main() {
  /**************/
  /*** AREA 4 ***/
  /**************/
  
  // (a) Read: Y Write: N
  // (b) Read: Y Write: N
  // (c) Read: N Write: N
  // (d) Read: N Write: N

  // publicFunc() - Called Here: Y
  // contractFunc() - Called Here: N
  // privateFunc() - Called Here: N

}
```

>
```diff
@@ Chapter_4 Quests @@
```

```diff
- CH.4 Day_1
```
>###### 1. Explain what lives inside of an account.
##### Inside of an account, there is contract code and account storage.
##### A contract gets deployed to an account where it stays and each account can have multiple contracts. All of your data (i.e.NFTs) are stored in the account storage where you can make it accessible via three different paths: ```storage```, ```private```, and ```public```
>###### 2. What is the difference between the /storage/, /public/, and /private/ paths?
##### In ```storage``` only you, the account holder have access to this data, ```private``` can only be accessed by who you give permission to, and ```public``` is viewable by everyone.
>###### 3. What does .save() do? What does .load() do? What does .borrow() do?
##### ```.save()``` saves data inside the account ```storage```,```.load()``` takes out the stored data from account storage and ```.borrow()``` gets a reference to a resource in account ```storage```.
>###### 4. Explain why we couldn't save something to our account storage inside of a script.
##### We can't save to our account storage inside of a script because we can only read what is stored and you need AuthAccount to access storage.
>###### 5. Explain why I couldn't save something to your account.
##### You need permission, in this case AuthAccount to sign off on the transaction giving access to save something to the account.

>###### 6. Define a contract that returns a resource that has at least 1 field in it. Then, write 2 transactions:
![alt text](https://github.com/thetafuelz/quest-submissions/blob/7d793cb344f25e99208b122025243ec002b732f8/img/Ch4D1_Q6a.JPG)
            i. A transaction that first saves the resource to account storage, then loads it out of account storage, 
            logs a field inside the resource, and destroys it.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/7d793cb344f25e99208b122025243ec002b732f8/img/Ch4D1_Q6b.JPG)       
            ii. A transaction that first saves the resource to account storage, then borrows a reference to it, 
            and logs a field inside the resource.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/7d793cb344f25e99208b122025243ec002b732f8/img/Ch4D1_Q6c.JPG)

```diff
- CH.4 Day_2
```
>###### 1. What does .link() do?
##### .link() function is used to assign references to the /public/ or /private/ path so others can access the data.
>###### 2. In your own words (no code), explain how we can use resource interfaces to only expose certain things to the /public/ path.
##### We can use the resource interface to only expose certain fields that we want to be seen by the user.
>###### 3. Deploy a contract that contains a resource that implements a resource interface. Then, do the following:
![alt text](https://github.com/thetafuelz/quest-submissions/blob/b578236e7e613ec09c54be56a39c6d504d9ce7e0/img/Ch4D2_Q2a.JPG)
            i. In a transaction, save the resource to storage and link it to the public with the restrictive interface.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/b578236e7e613ec09c54be56a39c6d504d9ce7e0/img/Ch4D2_Q2b.JPG)
            ii. Run a script that tries to access a non-exposed field in the resource interface, and see the error pop up.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/b578236e7e613ec09c54be56a39c6d504d9ce7e0/img/Ch4D2_Q2c.JPG)
            iii. Run the script and access something you CAN read from. Return it from the script.
![alt text](https://github.com/thetafuelz/quest-submissions/blob/b578236e7e613ec09c54be56a39c6d504d9ce7e0/img/Ch4D2_Q2d.JPG)


```diff
- CH.4 Day_3
```
>###### 1. Why did we add a Collection to this contract? List the two main reasons.
##### The two main reasons a ```Collection```is used is 1) reduce the # of storage paths to 1 and 2) all others to deposit into that collection.
>###### 2. What do you have to do if you have resources "nested" inside of another resource? ("Nested resources")
##### When you have resources "nested" inside of another resource you must use the ```destroy``` function to manually remove those resources
>###### 3. Brainstorm some extra things we may want to add to this contract. Think about what might be problematic with this contract and how we could fix it.
          Idea #1: Do we really want everyone to be able to mint an NFT? ????
##### No we do not want everyone to be able to mint an NFT. We could use resource interfaces to implement this restriction.          
          Idea #2: If we want to read information about our NFTs inside our Collection, right now we have to take it out of the Collection to do so. Is this good?
##### No, moving around data to read is neither a good idea or is it safe. We could use references for this purpose. 

```diff
- CH.4 Day_4
```
>###### 1. Because we had a LOT to talk about during this Chapter, I want you to do the following:
          Take our NFT contract so far and add comments to every single resource or function explaining what it's doing in your own words. 
          Something like this:
          
```cadence
          pub contract CryptoPoops {
  pub var totalSupply: UInt64

  // This is an NFT resource that contains a name,
  // favouriteFood, and luckyNumber
  pub resource NFT {
    pub let id: UInt64

    pub let name: String
    pub let favouriteFood: String
    pub let luckyNumber: Int

    init(_name: String, _favouriteFood: String, _luckyNumber: Int) {
      self.id = self.uuid

      self.name = _name
      self.favouriteFood = _favouriteFood
      self.luckyNumber = _luckyNumber
    }
  }

  // This is a resource interface that limit what we want exposed to the /public/ path from the /storage/CollectionPublic
  // Allows the collection to be viewed as public, making deposit, get, and borrow an NFT available for others to use 
  pub resource interface CollectionPublic {
    pub fun deposit(token: @NFT)
    pub fun getIDs(): [UInt64]
    pub fun borrowNFT(id: UInt64): &NFT
  }
  // This resource Collection links to the resource interface allowing to view ids of the NFTs
  pub resource Collection: CollectionPublic {
    pub var ownedNFTs: @{UInt64: NFT}
    // This function deposits NFTs into the account
    pub fun deposit(token: @NFT) {
      self.ownedNFTs[token.id] <-! token
    }
    // This functioni withdraws NFTs
    pub fun withdraw(withdrawID: UInt64): @NFT {
      let nft <- self.ownedNFTs.remove(key: withdrawID) 
              ?? panic("This NFT does not exist in this Collection.")
      return <- nft
    }
    // This function gets the ownedNFT ids
    pub fun getIDs(): [UInt64] {
      return self.ownedNFTs.keys
    }
    // This function borrows NFT and then returns an NFT reference.
    pub fun borrowNFT(id: UInt64): &NFT {
      return &self.ownedNFTs[id] as &NFT
    }

    init() {
      self.ownedNFTs <- {}
    }
    // This function destorys the nested resource
    destroy() {
      destroy self.ownedNFTs
    }
  }
  // This function creates a new collection
  pub fun createEmptyCollection(): @Collection {
    return <- create Collection()
  }
  // This resource allows the owner that deployed the contract to mint the allowed NFT
  pub resource Minter {
    // This function creates an NFT with three metadatas with value types of 1 Integer and 2 strings
    pub fun createNFT(name: String, favouriteFood: String, luckyNumber: Int): @NFT {
      return <- create NFT(_name: name, _favouriteFood: favouriteFood, _luckyNumber: luckyNumber)
    }
    // This function creates the minter role
    pub fun createMinter(): @Minter {
      return <- create Minter()
    }

  }
  // This initializes total supply and saves the minter role in storage
  init() {
    self.totalSupply = 0
    self.account.save(<- create Minter(), to: /storage/Minter)
  }
}
```

```diff
@@ Chapter_5 Quests @@
```

```diff
- CH.5 Day_1
```

>###### 1. Describe what an event is, and why it might be useful to a client.
##### Events, which are only declared in a contract, is a special value that allows us to be updated without having to specifically check for updates. This saves time and is a feature that is desirable int he NFT space
>###### 2. Deploy a contract with an event in it, and emit the event somewhere else in the contract indicating that it happened.
>###### 3. Using the contract in step 2), add some pre conditions and post conditions to your contract to get used to writing them out.

>##### Answer for Questions 2&3 

```cadence
  pub contract Test {

   pub event NewBallerz (ballerzName: String, ballerzType: String)

   pub resource interface IBallerz {
        pub var ballerzName: String
    }

    pub resource Ballerz: IBallerz {
        pub var ballerzName: String
        pub var ballerzType: String
        
    // Post condition to check that the Ballerz is not a Human
    pub fun checkBallerzType(newBallerzType: String): String {
        post {
        result != "Human": "This Ballerz cannot be a Human"
        }
        return newBallerzType
        
        init() {
            self.ballerzName = "Iverson"
            self.ballerzType = "Alien" 
        }
    }

    pub fun createBallerz(newBallerzName: String, newBallerzType: String): @Ballerz {
        // Precondition that name is not less than 3 letters
        pre {
            newBallerzName.length > 3: "Please return a real name"
        }

        let ballerzAdded <- create Ballerz()
      

        emit NewBallerz (ballerzName: newBallerzName, ballerzType: newBallerzType)
        
        return <- ballerzAdded   
    }


    init() {
    }

} 
```

>###### 4. For each of the functions below (numberOne, numberTwo, numberThree), follow the instructions.

```cadence
  pub contract Test {

  // TODO
  // Tell me whether or not this function will log the name.
  // name: 'Jacob'
  // ANSWER: Yes, it will log 'Jacob' as it meets the condition length of 5.
  pub fun numberOne(name: String) {
    pre {
      name.length == 5: "This name is not cool enough."
    }
    log(name)
  }

  // TODO
  // Tell me whether or not this function will return a value.
  // name: 'Jacob'
  // ANSWER: Yes, it will return 'Jacob Tucker' since "Tucker" was concatenated to "Jacob"
  pub fun numberTwo(name: String): String {
    pre {
      name.length >= 0: "You must input a valid name."
    }
    post {
      result == "Jacob Tucker"
    }
    return name.concat(" Tucker")
  }

  pub resource TestResource {
    pub var number: Int

    // TODO
    // Tell me whether or not this function will log the updated number.
    // Also, tell me the value of `self.number` after it's run.
    // ANSWER: No, it will not log the updated number since the post condition has not been met. 
    pub fun numberThree(): Int {
      post {
        before(self.number) == result + 1
      }
      self.number = self.number + 1
      return self.number
    }

    init() {
      self.number = 0
    }

  }

} 
```
/end

```diff
- CH.5 Day_2
```
>###### 1. Explain why standards can be beneficial to the Flow ecosystem.
##### Standards provide a uniform way of calling multiple functions since they are under one generic type.
>###### 2. What is YOUR favourite food?
##### Chicago Pizza or anything that is == "edible"
>###### 3. Please fix this code (Hint: There are two things wrong):
```cadence
pub contract interface ITest {
  pub var number: Int
  
  pub fun updateNumber(newNumber: Int) {
    pre {
      newNumber >= 0: "We don't like negative numbers for some reason. We're mean."
    }
    post {
      self.number == newNumber: "Didn't update the number to be the new number."
    }
  }

  pub resource interface IStuff {
    pub var favouriteActivity: String
  }

  pub resource Stuff:IStuff { // Resource Stuff should implement resource Interface IStuff
    pub var favouriteActivity: String
  }
}
____________________________________________________________________________________________
pub contract Test: ITest { // Contract Test should implement ITest
  pub var number: Int
  
  pub fun updateNumber(newNumber: Int) {
    self.number = 5
  }

  pub resource interface IStuff {
    pub var favouriteActivity: String
  }

  pub resource Stuff: IStuff {
    pub var favouriteActivity: String

    init() {
      self.favouriteActivity = "Playing League of Legends."
    }
  }

  init() {
    self.number = 0
  }
}
```diff
- CH.5 Day_3
```
>###### 1. What does "force casting" with as! do? Why is it useful in our Collection?
##### "Force casting" ```as!``` attempts to cast the object to the left of the operator as the type to the right of the operator. This is useful in making sure that the correct token is used, otherwise the cast will fail and the state is revverted.
>###### 2. What does auth do? When do we use it?
##### ```auth``` is used to downcast references. We can use this when want to change from a generic type to a more specific type.
>###### 3. This last quest will be your most difficult yet. Take this contract:
            and add a function called borrowAuthNFT just like we did in the section called "The Problem" above. Then, find a way to make it publically accessible to other people so they can read our NFT's metadata. Then, run a script to display the NFTs metadata for a certain id.

You will have to write all the transactions to set up the accounts, mint the NFTs, and then the scripts to read the NFT's metadata. We have done most of this in the chapters up to this point, so you can look for help there :)
```cadence
import NonFungibleToken from 0x02
pub contract CryptoPoops: NonFungibleToken {
  pub var totalSupply: UInt64

  pub event ContractInitialized()
  pub event Withdraw(id: UInt64, from: Address?)
  pub event Deposit(id: UInt64, to: Address?)

  pub resource NFT: NonFungibleToken.INFT {
    pub let id: UInt64

    pub let name: String
    pub let favouriteFood: String
    pub let luckyNumber: Int

    init(_name: String, _favouriteFood: String, _luckyNumber: Int) {
      self.id = self.uuid

      self.name = _name
      self.favouriteFood = _favouriteFood
      self.luckyNumber = _luckyNumber
    }
  }

  pub resource Collection: NonFungibleToken.Provider, NonFungibleToken.Receiver, NonFungibleToken.CollectionPublic {
    pub var ownedNFTs: @{UInt64: NonFungibleToken.NFT}

    pub fun withdraw(withdrawID: UInt64): @NonFungibleToken.NFT {
      let nft <- self.ownedNFTs.remove(key: withdrawID) 
            ?? panic("This NFT does not exist in this Collection.")
      emit Withdraw(id: nft.id, from: self.owner?.address)
      return <- nft
    }

    pub fun deposit(token: @NonFungibleToken.NFT) {
      let nft <- token as! @NFT
      emit Deposit(id: nft.id, to: self.owner?.address)
      self.ownedNFTs[nft.id] <-! nft
    }

    pub fun getIDs(): [UInt64] {
      return self.ownedNFTs.keys
    }

    pub fun borrowNFT(id: UInt64): &NonFungibleToken.NFT {
      return &self.ownedNFTs[id] as &NonFungibleToken.NFT
    }

    init() {
      self.ownedNFTs <- {}
    }

    destroy() {
      destroy self.ownedNFTs
    }
  }

  pub fun createEmptyCollection(): @NonFungibleToken.Collection {
    return <- create Collection()
  }

  pub resource Minter {

    pub fun createNFT(name: String, favouriteFood: String, luckyNumber: Int): @NFT {
      return <- create NFT(_name: name, _favouriteFood: favouriteFood, _luckyNumber: luckyNumber)
    }

    pub fun createMinter(): @Minter {
      return <- create Minter()
    }

  }

  init() {
    self.totalSupply = 0
    emit ContractInitialized()
    self.account.save(<- create Minter(), to: /storage/Minter)
  }
}
```
>##### Contract

```cadence
import NonFungibleToken from 0x02

pub contract CryptoPoops: NonFungibleToken {
  pub var totalSupply: UInt64

  pub event ContractInitialized()
  pub event Withdraw(id: UInt64, from: Address?)
  pub event Deposit(id: UInt64, to: Address?)

  pub resource NFT: NonFungibleToken.INFT {
    pub let id: UInt64

    pub let name: String
    pub let favouriteFood: String
    pub let luckyNumber: Int

    init() {
      self.id = CryptoPoops.totalSupply

      self.name = "Jacob"
      self.favouriteFood = "Pizza"
      self.luckyNumber = 64
    }
  }

  pub resource interface MyCollectionPublic {
    pub fun deposit(token: @NonFungibleToken.NFT)
    pub fun getIDs(): [UInt64]
    pub fun borrowNFT(id: UInt64): & NonFungibleToken.NFT
    pub fun borrowAuthNFT(id: UInt64): &NFT
  }

  pub resource Collection: NonFungibleToken.Provider, NonFungibleToken.Receiver, NonFungibleToken.CollectionPublic, MyCollectionPublic {
    pub var ownedNFTs: @{UInt64: NonFungibleToken.NFT}

    pub fun withdraw(withdrawID: UInt64): @NonFungibleToken.NFT {
      let nft <- self.ownedNFTs.remove(key: withdrawID) 
            ?? panic("This NFT does not exist in this Collection.")
      emit Withdraw(id: nft.id, from: self.owner?.address)
      return <- nft
    }

    pub fun deposit(token: @NonFungibleToken.NFT) {
      let nft <- token as! @NFT
      emit Deposit(id: nft.id, to: self.owner?.address)
      self.ownedNFTs[nft.id] <-! nft
    }

    pub fun getIDs(): [UInt64] {
      return self.ownedNFTs.keys
    }

    pub fun borrowNFT(id: UInt64): &NonFungibleToken.NFT {
      return &self.ownedNFTs[id] as &NonFungibleToken.NFT
    }

    pub fun borrowAuthNFT(id: UInt64): &NFT {
      let ref = &self.ownedNFTs[id] as auth &NonFungibleToken.NFT
      return ref as! &NFT
    }

    init() {
      self.ownedNFTs <- {}
    }

    destroy() {
      destroy self.ownedNFTs
    }
  }

  pub fun createEmptyCollection(): @NonFungibleToken.Collection {
    return <- create Collection()
  }

  pub resource Minter {
    pub fun createNFT(): @NFT {
      return <- create NFT()
    }

    pub fun createMinter(): @Minter {
      return <- create Minter()
    }
  }

  init() {
    self.totalSupply = 0
    emit ContractInitialized()
    self.account.save(<- create Minter(), to: /storage/Minter)
  }
}
```
>##### Contract Interface
```cadence
    pub resource interface INFT {
        
        pub let id: UInt64
    }

    pub resource NFT: INFT {
        pub let id: UInt64
    }

        pub resource interface Provider {
        
        pub fun withdraw(withdrawID: UInt64): @NFT {
            post {
                result.id == withdrawID: "The ID of the withdrawn token must be the same as the requested ID"
            }
        }
    }

        pub resource interface Receiver {
        pub fun deposit(token: @NFT)
    }

  pub resource interface CollectionPublic {
        pub fun deposit(token: @NFT)
        pub fun getIDs(): [UInt64]
        pub fun borrowNFT(id: UInt64): &NFT
    }


    pub resource Collection: Provider, Receiver, CollectionPublic {

    pub var ownedNFTs: @{UInt64: NFT}
    pub fun withdraw(withdrawID: UInt64): @NFT
    pub fun deposit(token: @NFT)
    pub fun getIDs(): [UInt64]
    pub fun borrowNFT(id: UInt64): &NFT {
            pre {
                self.ownedNFTs[id] != nil: "NFT does not exist in the collection!"
            }
        }
        pub fun borrowAuthNFT(id: UInt64): &NFT
    }
        pub fun createEmptyCollection(): @Collection {
        post {
            result.getIDs().length == 0: "The created collection must be empty!"
        }
    }
}
```
>##### Create Collection
```cadence
import CryptoPoops from 0x01
import NonFungibleToken from 0x02

transaction {
  prepare(acct: AuthAccount) {
    acct.save(<- CryptoPoops.createEmptyCollection(), to: /storage/Collection)
    acct.link<&CryptoPoops.Collection{NonFungibleToken.CollectionPublic, CryptoPoops.MyCollectionPublic}>(/public/Collection, target: /storage/Collection)
  }

  execute {
    log("Created CryptoPoops collection in your storage!")
  }
}
```
>##### Deposit NFT
```cadence
import CryptoPoops from 0x01
import NonFungibleToken from 0x02

transaction(recipient: Address) {

    prepare(acct: AuthAccount) {
        let nftMinter = acct.borrow<&CryptoPoops.Minter>(from: /storage/Minter)!

        let publicReference = getAccount(recipient).getCapability(/public/Collection)
                                .borrow<&CryptoPoops.Collection{NonFungibleToken.CollectionPublic}>()
                                ?? panic ("You do not have a collection ... yet.")
        
        publicReference.deposit(token: <- nftMinter.createNFT())
    }

    execute {
        log("You have recieved a new NFT in your collection!")
    }
}
```
>##### Read name Script
```cadence
import CryptoPoops from 0x01
import NonFungibleToken from 0x02

pub fun main(account: Address, id: UInt64): String  {

  let publicReference = getAccount(account).getCapability(/public/Collection)
                            .borrow<&CryptoPoops.Collection{CryptoPoops.MyCollectionPublic}>()
                            ?? panic ("Collection does not exist.")

  return publicReference.borrowAuthNFT(id: id).name
}
```
