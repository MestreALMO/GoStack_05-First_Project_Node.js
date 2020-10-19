# GoStack_05-First_Project_Node.js

This was the challenge of number five of the Bootcamp GoStack, the challenge is 100% completed, [here is the original link of the challenge.](https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-fundamentos-nodejs)

The challenge consisted of creating a DB:
* POST /transactions as follows:
```
{
  "id": "uuid",
  "title": "Salário",
  "value": 3000,
  "type": "income"
}
```
* GET /transactions as follows:
```
{
  "transactions": [
    {
      "id": "uuid",
      "title": "Salário",
      "value": 4000,
      "type": "income"
    },
    {
      "id": "uuid",
      "title": "Freela",
      "value": 2000,
      "type": "income"
    },
    {
      "id": "uuid",
      "title": "Pagamento da fatura",
      "value": 4000,
      "type": "outcome"
    },
    {
      "id": "uuid",
      "title": "Cadeira Gamer",
      "value": 1200,
      "type": "outcome"
    }
  ],
  "balance": {
    "income": 6000,
    "outcome": 5200,
    "total": 800
  }
}
```
* should be able to create a new transaction
* should be able to list the transactions
* should not be able to create outcome transaction without a valid balance
