###### Endpoint

    https://boascan.io/getaddresssummary?address=GHSDNF…

HTTP Method: **GET**

Returns Address, No. of Transactions, Total Received, Total Sent, Freezing Total Amount, Reward Total Amount, Final Balance of Address

| Query String | Explanation    | Example                            |
| ------------ | -------------- | ---------------------------------- |
| address      | public address | GDNODE5JKEW8765DHGJASYD78ADG5YAJSD |

Example Response JSON:<br/>
[{"response":"success","data":{"height":"23423", "timestamp":"2s", "hash":"0x902349....","merkleRoot":"0x093240...","signature":"0x83493.....","validators":"234","txCount":"123","enrolledCount":"322"}}]({"response":"success","data":{"height":"23423", "timestamp":"2s", "hash":"0x902349....","merkleRoot":"0x093240...","signature":"0x83493.....","validators":"234","txCount":"123","enrolledCount":"322"}})
