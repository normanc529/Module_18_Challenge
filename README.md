# PyChain Ledger

This application creates a streamlit instance that creates a functioning mock blockchain. 

A record class is defined which stores info about the transaction such as sender_id, receiver_id, amount, etc

After, a block class is defined which holds the creator_id (of the block), the hash of the previous block, and the nonce.

Uses sha256 encryption on the info

PyChain class is the block chain which records the list of blocks, the winner of mining/validation, shows proof of work, and validates if the blocks are legitamate.

Streamlit is then used to create a user interface that allows user input, display transactions on the ledger, and inspect individual blocks for information

![image](https://user-images.githubusercontent.com/75395061/117410724-a67f0800-aec7-11eb-87e7-0cdc0166f40c.png)


