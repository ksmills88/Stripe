# Stripe
## This is a practice repository for setting up a Payment Gateway with Stripe/React/Express.


### [Follow this Tutorial to get up and running from scratch](https://www.robinwieruch.de/react-express-stripe-payment/) or clone this repo to see it working


To get running on your machine follow steps 1-9:

1. Clone Repo
2. cd frontend
3. npm i
4. cd ../backend
5. npm i

> Run backend: 

6. node index.js

> Run frontend:

7. Open second terminal
8. navigate to Stripe/frontend
9. npm start

> This will open development on localhost:3000

### When you click the Payment button, the modal will open with a payment form. Enter dummy information:

- Any Email
- Card Number: 4242 4242 4242 4242
- CVV: 3 digit (any)
- expiration: any date in the future

### Then click the pay button and if successful, you will get an alert that the payment was successful.

The "Pay" button does not trigger any email or any 'actual' movement of funds. In Stripe's test mode, I can view fake transactions on Stripe with payment timestamp and $ amount on my account dashboard. 