This is documentation on ethereum

# Ethereum Documentation<hr>
<h3>What is ethereum ?</h3>
<p>
Ethereum is a platform for building <strong>decentralized applications</strong> and for running <strong>smart contracts</strong> without any issues like application downtime (or) third-party interference. Allows anyone to write smart contracts, where we can create our own arbitary rules for ownership, transaction formats and state transition formats.
</p>
<h3>What are decentralized applications ?</h3>
<p>
Decentralized applications are applications which will not depend on any server (or) trusted third party. These applications hava a capability to communicate with each other directly using <strong>peer-to-peer network</strong>.
</p>
<h4>--->How Peer-to-Peer network works ?</h4>
<p>
By using <strong>Digital Signature</strong> concept the peer-to-peer network will work.
</p>
<h4>--->How Digital Signature works ?</h4>
<p>
Digital signature will work based on private keys and public keys. For example, A wants to send message to B so here before  sending message directly to B, first A will encypt the message using his private key after encryption one message signature will be generated, now A will send his public key and message signature to B and B will decrypt the message using A's public key and his message signature.
</p>
<h3>What is smart contract ?</h3>
<p>
A smart contract is a piece of software code that stores some set of rules for negotiating the terms of a contract and it automatically verifies the contract, if it is valid contract then it will be executed, otherwise that contract will be rejected. Smart contracts stores an information about an application, such as domain registration information or membership records.<br>
Smart contracts can be written using <b>Solidity</b> programming language.
</p>
<h3>Bitcoin vs Ethereum</h3>
<p>
There are three basic diffrences between bitcoin and ethereum:<br>
1)Bitcoin is a separate currency, whereas ethereum is a platform which maintains it's own currency called <strong>Ether</strong>.<br>
2)Bitcoin mining is based on <strong>Proof of Work(POW)</strong> algorithm and ethereum mining is based on <strong>Proof of Stake(POS)</strong> algorithm.<br>
3)By using bitcoin we can only run transaction applications, whereas by using ethereum we can run any kind of applications like transaction, voting etc.
</p>
<h3>What is Ether ?</h3>
<p>
Ether is a cryptocurrency in ethereum platform. Ether is not exactly digital currency, it is a digital asset bearer (like a bond or other security) and ether should be considered as “fuel” for the apps on the decentralized ethereum network.
</p>
<h4>--->Gas</h4>
<p>
Gas is the amount of fuel required to execute or performing the transaction computational operations.
</p>
<h4>--->GasPrice</h4>
<p>
GasPrice is the amount which will be paid to validate your transaction. If you pay more gasprice then your transaction may get validated as much as fast, otherwise takes more time to validate our transactions.
</p>
<h4>--->Transaction Fee</h4>
<p>
Transaction fee is equals to the multiplication of both gas and gasprice(<b>Gas*GasPrice</b>).
</p>
<h3>Features of Ethereum</h3>
<p>
1)Cryptocurrency.<br>
2)Smart contracts.<br>
3)Decentralized Autonomous Organizations(DAO).<br>
4)Smart property.
</p>
<h4>What is DAO ?</h4>
<p>
DAO's are organizations that exist entirely on blockchain and are governed by it's protocols. They uses a kind of voting system to manage their distributions.<br>
* Anyone with internet access could hold DAO tokens and buy them.<br>
* DAO creators could set whatever rules they voted on.
</p>
<h4>What is Smart Property ?</h4>
<p>
Smart propertie's are assets like house, vehicles, shares and bonds. By using smart propertie's we can control our ownership via blockchain.
</p>
<h4>What are the principles of ethereum ?</h4>
<p>
1)Simplicity.<br>
2)Universality.<br>
3)Agility.<br>
4)Non-discrimination.<br>
5)Modularity.
</p>
<h3>What is simplicity ?</h3>
<p>
Writing code in ethereum platform is simple and easier. For example, namecoin will be written under 2 lines of code and any currencies can be built under 20 lines of code.
</p>
<h3>What is universality ?</h3>
<p>
We can run our smart contracts in any system from anywhere without any restrictions.
</p>
<h4>What is Agility ?</h4>
<p>
A continuous improvement which means we can't say that there is an end point for this contract (or) for cryptocurrency.
</p>
<h4>What is Non-discrimination ?</h4>
<p>
No restrictions in ethereum while building smart contracts. We can bulit our smart contracts under our own constraints.
</p>
<h4>What is Modularity ?</h4>
<p>
Modularity is nothing but wherever the modifications we did in the code. The recompiling part should be reflected on that part only instead of recompiling the entire application agin.
</p>
<h3>What are ethereum limitations ?</h3>
<p>
1)Lack of turing-completeness.<br>
2)Value-blindness.<br>
3)Lack of state.<br>
4)Blockchain blindness.
</p>
<h4>
What is the purpose of Lack of turing-completeness ?
</h4>
<p>
Avoids infinite loop repetitions.
</p>
<h4>What is the purpose of value-blindness ?</h4>
<p>
Avoids sending more money than the exist (or) actual money.
</p>
<h4>What is the purpose of lack of state ?</h4>
<p>
Avoids lack of state problem by maintaing state transaction functions and <b>UTXO</b>
</p>
<h4>
--->UTXO
</h4>
<p>
"Unspent Transaction output's", the benefit of UTXO is we can't spent illegal transactions like spending more money than the existing money, if we spent like that UTXO will return an error.
</p>
<h4>What is the purpose of blockchain blindness ?</h4>
<p>
UTXO's are blind blockchain data such as nonce, timestamp and previous block hash. This several limits applications in gambling.
</p>
<h3>Ethereum state transition function</h3>
<p>
It maintains <b>state, transaction and state'</b>. State will maintain the transactions and from state one by one transaction will goes to the transaction part, here the opeartions of the transactions are completed and after completing each transaction operation that will move into the state' part which means the state of the transaction has been chenged.<br>
To compute transaction operations we require some fields like initial gas, startgas and gasprice.
</p>
<h3>
What is ethereum account ?
</h3>
<p>
In ethereum, every state is made up of some objects those objects are called "accounts".<br>
Every ethereum account contains four fiels:<br>
1)Nonce.<br>
2)Ether balance.<br>
3)Contract code.<br>
4)Storage.
</p>
<h3>
What is Mining and who are Miners ?
</h3>
<p>
Mining is a part of validating 
each block of transactions using some alporithms like co sensun, pow etc.<br><br>
The miners will have a responsibilty to validate blocks.
</p>
<h3>Messages and Transactions</h3>
<h4>--->Messages</h4>
<p>
In ethereum messages are virtual objects that are never serialized which means whatever the messages we sent that are not received in a same manner that may received randomly and exist only in the Ethereum execution environment.<br>
A message contains:<br>
* The sender of the message (implicit).<br>
* The recipient of the message.<br>
* The amount of ether to transfer alongside the message.<br>
* An optional data field.<br>
* A STARTGAS value.
</p>
<h4>--->Transactions</h4>
<p>
In ethereum a transaction refer to the signed data package that stores a message to be sent from an externally owned account.<br>
Transactions contain:<br>
* The recipient of the message.<br>
* A signature identifying the sender.<br>
* The amount of ether to transfer from the sender to the recipient.<br>
* An optional data field.<br>
* A STARTGAS value, representing the maximum number of computational steps the transaction execution is allowed to take.<br>
* A GASPRICE value, representing the fee the sender pays per computational step.<br>
</p>
<h3>Code Execution</h3>
<p>
code execution is an infinite loop that consists of repeatedly carrying out the operation at the current program counter (which begins at zero) and then incrementing the program counter by one, until the end of the code is reached or an error or STOP or RETURN instruction is detected.<br>
The operations have access to three types of space in which to store data:<br>
* The stack, a last-in-first-out container to which values can be pushed and popped.<br>
* Memory, an infinitely expandable byte array.<br>
* The contract's long-term storage, a key/value store. Unlike stack and memory, which reset after computation ends, storage persists for the long term.<br>
* The code can also access the value, sender and data of the incoming message, as well as block header data, and the code can also return a byte array of data as an output.<br>
* Ethereum virtual machine is running, its full computational state can be defined by the tuple (block_state, transaction, message, code, memory, stack, pc, gas).
</p>
<h3>Blockchain and Mining</h3>
<p>
Here we will onserved some differences between bitcoin and ethereum those are bitcoin contains a copy of transaction list and ethereum contains both the transaction list and the recent state we used.<br>
To validate a block we need to follow below algorithm steps:<br>
1)First, check if the previous block is existed and valid.<br>
2)second, check that the timestamp of the block is greater than that of the referenced previous block and less than 15 minutes into the future.<br>
3)Third, check block number, difficulty, transaction root, uncle root and gas limit (various low-level Ethereum-specific concepts) are valid.<br>
4)Check that the proof of work on the block is valid.<br>
5)Let S[0] be the state at the end of the previous block.<br>
6)Let TX be the block's transaction list, with n transactions. For all i in 0...n-1, set S[i+1] = APPLY(S[i],TX[i]). If any applications returns an error, or if the total gas consumed in the block up until this point exceeds the GASLIMIT, return an error.<br>
7)Let S_FINAL be S[n], but adding the block reward paid to the miner.<br>
8)Check if the <b>Merkle tree</b> root of the state S_FINAL is equal to the final state root provided in the block header. If it is, the block is valid; otherwise, it is not valid.<br>
</p>
<h4>--->Merkle Tree</h4>
<p>
Merkle tree structure can be formed by transactions and their hash values. First, it takes transactions as leaf nodes and generates hash values for each and every transactions then it pairs (or) combines two hash values say H0 and H1 as H01, so same like that it does pairing for all transactions untill one hash value reached that is root hash value and at last that root hash value will be stored in the block header and that hash value will be used for next blocks (or) for further references.<br>
Below is the example merkle tree structure:<br>
<img src="https://i.imgur.com/eNrvk9u.png" width="100%"/>
</p>

