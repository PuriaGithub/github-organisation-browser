<p align="center">
    <img src="https://raw.githubusercontent.com/PuriaGithub/github-organisation-browser/master/public/logo192.png" width="129" alt="logo">
</p>


# Github Organisation Respository Browser - [Live Version](https://flamboyant-panini-a781ab.netlify.app/)

This project is a single page application (SPA) using ReactJS and Github Restful API.

This application retrieves the details of the requested organisation available on GitHub including:

* Avatar
* Description
* Location
* Website URL
* Github URL
* Total number of repositories  

It also presents a list of all the repositories available on Github and their details such as:
* Name
* Description
* GitHub URL
* Whether it is a fork
* Star Count
* Watchers Count
* License (if there is one)
* Language
* Top 5 Contributors

In addition, it allows you to filter and sort the repository list with a few options like whether it is a forked repository or not and etc.

## Change the default organisation

You can easily change the default organisation by changing the following part in the `.env` file in the root directory.

`REACT_APP_ORG_NAME=organisation-name`

For example, to get Microsoft repositories details, you need to have something like:

`REACT_APP_ORG_NAME=microsoft`


## How to run?

### Step 1 - Downloading all the required node modules

`yarn`

or

`npm install`


### Step 2 - Serving the application

`yarn start`

or

`npm run start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Tested successfully on the following web browsers:
* Safari - v13.0.2
* Google Chrome - v86.0.4240.198 
* Microsoft Edge - v86.0.622.69 
* Firefox - v82.0.3

### Resources
[React](https://reactjs.org/) - A JavaScript library for building user interfaces

[Redux](https://redux.js.org/) - A Predictable State Container for JS Apps

[Material Designs Icons](https://materialdesignicons.com/) -  Material Design icons and more from the community



