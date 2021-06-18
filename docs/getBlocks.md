Endpoint

    https://boascan.io/getmaxlatestblocks

HTTP Method: **GET**
<br/>
<br/>
Returns Height, Hash, Merkle Root, Signature, Validators. TX Count, Enrollment Count, Timestamp of Blocks

| Parameter | Explanation  | Example                              |
| --------- | ------------ | ------------------------------------ |
| address   | Get Balance  | 0f960607-0607-4382-aaca-6ebe086349f0 |
| apikey    | Your API Key | 0f960607-0607-4382-aaca-6ebe086349f0 |

Example Response JSON:<br/>
[{"response":"success","data":{"height":"23423", "timestamp":"2s", "hash":"0x902349....","merkleRoot":"0x093240...","signature":"0x83493.....","validators":"234","txCount":"123","enrolledCount":"322"}}]({"response":"success","data":{"height":"23423", "timestamp":"2s", "hash":"0x902349....","merkleRoot":"0x093240...","signature":"0x83493.....","validators":"234","txCount":"123","enrolledCount":"322"}})
