# The Unreliable TODO

Welcome to the ROI Hunter FE task readme. If you are interested in joining our FE team, read on and show us your best!


## The task

Your task is to create a simple backend-connected TODO app. However it is not a regular TODO app. The backend is unreliable, so you need to prepare for your requests to not to be accepted!

Your app needs to:

* support all CRUD operations on TODO items
* allow TODO items filtering & sorting
* have a session control component

Session control component is a component where you can manage your session by creating a new one, deleting the current one or changing the session's failure rate. The list of requirements above covers only the core functionality. Feel free to add some custom features improving the app behavior.


## How to develop

As a scaffolding tool we recommend [Create React App](https://github.com/facebook/create-react-app) ([tuned](https://facebook.github.io/create-react-app/docs/adding-typescript) for TypeScript). Develop in a GitHub repository, commiting properly as you go. When you are finished, share the repo with us.
Each solution needs to be also properly tested. Don't forget to prove your app quality with unit tests covering the mandatory parts.


## Technologies

To impress us with your skills we would like to see a usage of these technologies:

* React
* TypeScript
* Redux & Redux Toolkit

When implementing React components, please try to prefer functional components and a usage of hooks. You can also use any other technology that will help you make your app bright & shiny.


## The server (backend)

To help you start right away with the FE development, we have prepared a simple server in this repository ready to be used. Just run `npm install` followed by `npm start` and your server will start at `localhost:9000`. You can change the server port binding in `./src/constants.js`. If you wish to make any changes to the server, feel free to fork this repo. Just don't forget to share with us the server repo link when you are done.  
The ready to use server already implements the minimal interface accepting all CRUD operations on TODO items and sessions. We suggest you to start with the Apiary docs (https://roihfetask.docs.apiary.io), describing the operations, their payloads and responses.


## Bonus points

Would you like to impress us with your solution and you wonder how to do it? Consider our suggestions:

* Cypress tests
* BEM methodology


## Good luck and have fun!

If you struggle, you can contact us anytime and we will provide you some hints. Also if you get stuck at one point, just try to implement the rest of the functionality and get in touch with us.

Contact: denisa.mehesova@roihunter.com
