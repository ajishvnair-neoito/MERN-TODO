
# MERN Stack TODO Application

<!-- INSTALL PROJECT PACKAGES -->

## API Documentation

```sh
|---------------------------------------------------------------------------------|
| METHOD:  URL:                                        // DESCRIPTION             |
|---------------------------------------------------------------------------------|
| GET:     http:localhost:5000/                        // defaults welcome routes |
| GET:     http:localhost:5000/api/v1/todos-all        // get all todos           |
| GET:     http:localhost:5000/api/v1/todo/:id         // get a single todo       |
| POST:    http:localhost:5000/api/v1/todo/new         // create a new todo       |
| POST:    http:localhost:5000/api/v1/todos-many       // create many todos       |
| PUT:     http:localhost:5000/api/v1/todo/:id         // update a todo           |
| DELETE:  http:localhost:5000/api/v1/todo/:id         // delete a todo           |
|---------------------------------------------------------------------------------|
```

<!-- INSTALL PROJECT PACKAGES -->

## Installing Packages

```sh
npm install express         // node framework
npm install serve-favicon   // api router favicon sets
npm install mongoose        // mongoDB database schema-based solution to model your application data
npm install dotenv          // environment variables
npm install corss           // corss-origin-allow-all
```

<!-- EXTENSIONS & LINTING SETUP -->

## VS-Code Extensions

Install the below extensions:

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## Linting Setup

In order to lint and format your code automatically according to popular airbnb style guide, I recommend you to follow the instructions as described in video. References are as below.

### Install Dev Dependencies

```sh
npm install -D eslint prettier
npx install-peerdeps --dev eslint-config-airbnb-base
npm install -D eslint-config-prettier eslint-plugin-prettier
```

