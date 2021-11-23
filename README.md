# Redux_Store

## Task

We learned how to manage global state using React’s Context API. The Context API is quickly gaining traction as a worthy alternative or perhaps even successor to other libraries that manage global state in tandem with React, such as Flux or MobX. Nonetheless, the open source JavaScript library Redux remains the industry standard for managing complex state in a large-scale React application, and we likely encounter it on the job.

Our challenge is to refactor the e-commerce platform from given Activity so that it uses [Redux](https://redux.js.org/). We won’t need to make sweeping changes to the code, but we will need to read through the Redux documentation on our own to find the information we need. Some guidelines have been provided to point us in the right direction.

## User Story

```md
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
```

## Description

 ![License](https://img.shields.io/badge/License-MIT-yellow)

```md
GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API
```

## Mock-Up

This section reviews the web application's general appearance and functionality.

The following animation shows how a user can register using the Signup page and then navigate to the Products page:

![A user registers on the Signup page and then navigates to the Products page, which displays images and descriptions of products.](./Assets/22-state-homework-demo-01.gif)

The following animation shows how the user can select a category, choose a product, view details about it on the product page, and add and remove it from their shopping cart:

![The user selects a category, chooses a product, views details about it on the product page, and adds it to and removes it from their shopping cart.](./Assets/22-state-homework-demo-02.gif)

Finally, the user can check out by going to their shopping cart, as shown in the following animation:

![The user checks out by going to their shopping cart.](./Assets/22-state-homework-demo-03.gif)

## Table Of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Test](#test)
- [License](#license)
- [Contribution](#contribution)
- [Contact](#contact)
- [Questions](#questions)
    
## Installation 

The following necessary dependencies must be installed to run the application.

 concurrently, node, nodemon as dev dependencies, mongoDB Atlas, Express, mongoose, GraphQL, jsonwebtoken, apollo-server-express, bcrypt, @apollo/client, bootstrap, react, react-dom, react-router-dom, react-scripts, react-bootstrap, jwt-decode, redux, react-redux,  stripe, @stripe/stripe-js,  Heroku

## Usage

 Application can be invoked by npm run develop command in terminal or user can use deployed to Heroku link to access application.

## Test
  N/A
## License

This project is licensed under :

 [MIT](https://opensource.org/licenses/MIT)

For more information about the license, check the above link.

## Contribution

Coding Boot camp provided fully functional react website to refactor with redux.

## Contact

* GitHub :[bindi-v](https://github.com/bindi-v)

* Email : bindi.vaghela@gmail.com
    
## Questions

If you have any questions, please reach out to my Github.

### Deployed Link

* [The URL of the functional, deployed application on Heroku.]()

* [The URL of the GitHub repository](https://github.com/bindi-v/Redux_Store)

#### Thank you for visiting my Github!