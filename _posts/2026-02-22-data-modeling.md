---
layout: post
categories: misc
author:
- Paul Beggs
comments: true
---

## Overview

Your local grocery store would like your help in creating an online grocery shopping web application. The owner of the store will be able to list items for sale, where the items have a name, price, description, quantity available, and a manufacturer. Customers will be able to go to the site and register to create an account, entering in their name, address, and phone number. Once registered, customers will be able to start an order for pickup or delivery. The customer can select from the food items the store has for sale. When an item is selected, the customer will note the quantity desired, any special instructions, and if this item can be substituted if the store is out of stock. Finally, when the customer finalizes their order, they will be able to choose a time and date for their order to be fulfilled. Finalized orders can no longer be changed by the customer.

Breaking down that description, we get the following:

- Owner needs to be able to:
    - list items for sale 
    - items have:
        - price,
        - description,
        - BOH, and
        - manufacturer

- Customers need to:
    - register to create an account, which requires:
        - name,
        - address, and
        - phone number
    - start an order for pickup *or* delivery, which includes:
      - selecting food items the store has for sale, which includes:
        - quantity desired
        - special instructions, and
        - if that item can be substituted if the store is out of stock
    - finalize an order, which includes:
      - choose date *and* time for their order to be fulfilled
        - finalized orders cannot be changed by the customer

## User Stories

Our users include the owner and their customers

1. As an owner, I want to list items with name, price, description, quantity available, and manufacturer so that customers can browse and order them.
    - Time to complete: 8 weeks (whole project length)
    - Connections: Customer ordering, login, and finalizing orders
2. As a customer, I want to create an account by entering my name, address, and phone number so that I can place online orders for pickup or delivery.
    - Time to complete: 2 weeks
    - Connections: Owner's webpage and customer functionality (e.g., ordering, finalizing, setting date and time)
3. As a customer, I want to add items to my order with quantity, special instructions, and substitution preferences so that I receive the items I need even if something is out of stock.
    - Time to complete: 6 weeks
    - Connections: Owner's webpage and customer functionality
4. As a customer, I want to choose a date and time when finalizing my order so that it is fulfilled when I need it.
    - Time to complete: 2 weeks
    - Connections: Owner's webpage and customer functionality
5. As a customer, I want finalized orders to be locked so that I know my order details cannot accidentally change.
    - Time to complete: 1 week
    - Connections: Owner's webpage and customer functionality