# rabbitmq
My basic RabbitMQ starting point


### Setup

Start up and go to [http://localhost:15672](http://localhost:15672).

1. Login with username `guest` and password `guest`.
2. Create a new admin user with **STRONG** password and tag "Admin", possibly give virtual host access to `/`?
3. Log out of `guest` and log into `admin`. Delete the `guest user`.
4. Create new user(s) for producing to topics that will be used in the nodes