# Bank Tech Test

## Specification

### Requirements

- You should be able to interact with your code via a REPL like IRB or the JavaScript console. (You don't need to implement a command line interface that takes input from STDIN.)
- Deposits, withdrawal.
- Account statement (date, amount, balance) printing.
- Data can be kept in memory (it doesn't need to be stored to a database or anything).

### Acceptance criteria

**Given** a client makes a deposit of 1000 on 10-01-2012  
**And** a deposit of 2000 on 13-01-2012  
**And** a withdrawal of 500 on 14-01-2012  
**When** she prints her bank statement  
**Then** she would see

```
date || credit || debit || balance
14/01/2012 || || 500.00 || 2500.00
13/01/2012 || 2000.00 || || 3000.00
10/01/2012 || 1000.00 || || 1000.00
```
### Code Structure 

I've written some comments explaining struggles in the code and not being able to get the class extraction quite right!

### Tests

All of my tests are failing in this branch or they are passing because I've fudged them I think- because I cannot mock in Jest and struggling to figure it out from online resources! (Though I would also struggle in RSpec)

![image](https://user-images.githubusercontent.com/30720508/117331360-95fe6b80-ae8e-11eb-94be-7556b6461a37.png)
