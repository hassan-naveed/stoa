###### Endpoint

    https://boascan.io/getblocksummary?block=0x0a8…

HTTP Method: **GET**

Returns Height, Hash, Previous Hash, Merkle Root, Signature, Random Seed, Timestamp, Block Size, Total Reward, Version, No. of Transactions, Transaction Volume, Total Fees, Total Received BOA, Total Sent BOA of block

| Query String | Explanation                | Example                                     |
| ------------ | -------------------------- | ------------------------------------------- |
| block        | Block Hash or Block Height | 0x0000009230428342374236748234322 or 327556 |

Example Response JSON:<br/>
[{"response":"success","data":{"height":"23423", "timestamp":"2s", "hash":"0x902349....","merkleRoot":"0x093240...","signature":"0x83493.....","validators":"234","txCount":"123","enrolledCount":"322"}}]({"response":"success","data":{"height":"23423", "timestamp":"2s", "hash":"0x902349....","merkleRoot":"0x093240...","signature":"0x83493.....","validators":"234","txCount":"123","enrolledCount":"322"}})
