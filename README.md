# ada-debit-orders
Protocol to facilitate debit order contracts on the Cardano blockchain

#### Approach:
 - Client secures the entire amount owed over the agreed term inside a contract
 - contract manages the distribution from that fund each month(or custom frequency) to the recipient
 - client is able to withdraw the amount(minus latest payment) at any point
   - contractor is notified if the client withdraws
