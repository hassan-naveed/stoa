###### Endpoint

    https://boascan.io/gettransactionsummary?transaction=0x00a438...

HTTP Method: **GET**

Returns Hash, Input Address, Output Addresses, Time, Amount, Fee, Status, Type, Lock Height, Total Input, Total Output, Data Fees, Transaction Fees, Size, Payload, Inputs(Index, UTXO, Signature, Unlock Age, Bytes), Outputs(Index, UTXO, LockType, Bytes) of Transaction

| Query String | Explanation      | Example                                      |
| ------------ | ---------------- | -------------------------------------------- |
| transaction  | Transaction Hash | 0x0a8219f7486cbfj78346y85734758323049dd92398 |

Example Request JSON:<br/>
[{"response":"success","data":{"height":"23423", "timestamp":"2s", "hash":"0x902349....","merkleRoot":"0x093240...","signature":"0x83493.....","validators":"234","txCount":"123","enrolledCount":"322"}}]({"response":"success","data":{"height":"23423", "timestamp":"2s", "hash":"0x902349....","merkleRoot":"0x093240...","signature":"0x83493.....","validators":"234","txCount":"123","enrolledCount":"322"}})
<br/>
<br/>
Example Response JSON:<br/>
[{"response":"success","data":{"height":"23423", "timestamp":"2s", "hash":"0x902349....","merkleRoot":"0x093240...","signature":"0x83493.....","validators":"234","txCount":"123","enrolledCount":"322"}}]({"response":"success","data":{"height":"23423", "timestamp":"2s", "hash":"0x902349....","merkleRoot":"0x093240...","signature":"0x83493.....","validators":"234","txCount":"123","enrolledCount":"322"}})
