# Personal Expense Tracker API

This is a simple RESTful API for managing personal financial transactions using Node.js and Express.

## Endpoints

- **POST /transactions**: Add a new transaction (income or expense).
- **GET /transactions**: Retrieve all transactions.
- **GET /transactions/:id**: Retrieve a specific transaction by ID.
- **PUT /transactions/:id**: Update a transaction by ID.
- **DELETE /transactions/:id**: Delete a transaction by ID.
- **GET /summary**: Retrieve a summary of total income, total expenses, and balance.

## Instructions

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Start the server with `npm start`.
4. Use Postman or any HTTP client to interact with the API.

## Example

### POST /transactions

```json
{
  "type": "income",
  "category": "Salary",
  "amount": 5000,
  "date": "2024-10-01",
  "description": "Monthly salary"
}
```

### GET /summary

## Contact
Created by [[@Vamshi-1999](https://github.com/Vamshi-1999)] - feel free to contact me!


```json
{
  "totalIncome": 5000,
  "totalExpenses": 0,
  "balance": 5000
}
```
