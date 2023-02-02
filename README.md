# Assignment-1

## Create RESTFUL API with expressJS.

Database - PostgreSQL.

ORM - Sequelize.

The application performs basic banking operations. Implement authentication and authorization in Express API using JWT. Every endpoints should be secured. 
User should have access of his account only. Application should handle all the possible validations. Every endpoints should be functional in local environment.

- Build a endpoint for register a user.
- Build a endpoint for login a user.
- Build a endpoint for create an account for a logged in user.
- Build a endpoint for deposit money into User account.
- Build a endpoint for withdraw money from User account.
- Build a endpoint for check the balance of the User account.
- Build a endpoint for show latest 5 transactions of user account.
- Build a endpoint for transfer funds between accounts.

### Associations 
- User has one account.
- Account has many transactions.

## Reference docs.

- https://developer.mozilla.org/en-US/

- https://expressjs.com/en/starter/installing.html

- https://sequelize.org/docs/v6/getting-started/

- https://standards.rest/

- https://www.rfc-editor.org/rfc/rfc7231
