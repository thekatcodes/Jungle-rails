# Jungle

A mini e-commerce application built with Rails 6.1 for purposes of teaching Rails by example.

## Final Product

### Home Page Demo

https://user-images.githubusercontent.com/83685887/225451623-2770d950-c7c4-466a-a673-f23234528c6f.mov

### Cart/Checkout Demo

https://user-images.githubusercontent.com/83685887/225451627-75da2b4d-4b98-4be4-ac3a-bb68f315c674.mov


## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rails db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Database

If Rails is complaining about authentication to the database, uncomment the user and password fields from `config/database.yml` in the development and test sections, and replace if necessary the user and password `development` to an existing database user.

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

- Rails 6.1 [Rails Guide](http://guides.rubyonrails.org/v6.1/)
- Bootstrap 5
- PostgreSQL 9.x
- Stripe
- Turbolinks ^5.2.0
- Webpack ^4.46.0
- Webpack Client ^3.3.12

## Dev Dependencies
- Cypress ^9.7.0
- Webpack Development Server ^3.11.2

## Thank You
Thank you for taking the time to look at one of my projects!
