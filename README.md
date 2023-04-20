# Sundae Server

This is a server for the Sundaes On Demand app from the [Jest and React Testing Library course on Udemy](https://www.udemy.com/course/react-testing-library/) by [Bonnie Schulkin](https://www.udemy.com/user/bonnie-schulkin/). It is needed for my [next-jest-testing-library](https://github.com/emanuelefavero/next-jest-testing-library) cheat-sheet repo

> Note: This is just a test server used to learn Jest and React Testing Library. It is NOT meant for a fully featured application

## Installation

- clone the repo and `cd` into it
- run `npm install`
- run `npm start` to start the server

## Test the routes

You can test routes using the `test.http` file in the root of the project. You can use [VSCode REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) to run the requests.

## Routes

- `GET /scoops` - get a list of all available scoops
- `GET /toppings` - get a list of all available toppings
- `POST /order` - submit an order

## License

- [MIT](LICENSE.md)
