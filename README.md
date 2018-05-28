# Equilibria Centralised Flow Management System

Coming soon...

## Dependencies and Deployment

- Ruby Version: 2.5.1

To install, 
1. `$ bundle install --without production`
2. Setup the Postgres server and create a user named `equilibria`
3. Create a file `db/password` and put the password of the user in it.
4. `$ rails db:migrate`
5. If testing passes at this stage, deployment is ready.

## Testing

```
rails test
```
