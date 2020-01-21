# My First Monolith

* **Objective** - To create a full-stack monolithic application
* **Purpose** - To gain familiarity with connecting a web service to a front end application
* **Description**
   * Run this application by running the main method in `DemoApplication`.
   * Navigate to the server port specified in the [application.properties file](./src/main/resources/application.properties). By default, the port number is `8080`
   * If your application cannot run because something is occupying a port, execute this command from `Git Bash` with the respective port number specified:
       * ``kill -kill `lsof -t -i tcp:8080` ``
   * Navigate to `localhost/8080` from a browser (`Chrome`, or `Firefox`)
   * Take note of the functionality for each button that is available on the webpage.
   * Modify the functionality of the `create` button which fetches data from the [DOM](https://www.w3schools.com/js/js_htmldom.asp), and persists it in our database.

## Part 0 - Clone the project
* Begin by _forking_ this project into a personal repository.
   * To do this, click the `Fork` button located at the top right of this page.
* Navigate to **your github profile** to find the _newly forked repository_.
* Clone the repository from **your account** into your `~/dev` directory.
* Open the newly cloned project in a code editor (IntelliJ, for example).


## Part 1 - Configure Local Environment Environment
* This setup guide uses the `npm` client command line interface, which is installed with `Node.js` by default. 
* Verify that your machine has [NodeJs](https://nodejs.org/en/) installed by
    1. open `node` by executing the following command from a command line
        * `node`
    2. update `node` by executing the following command from a command line
        * `npm install npm@latest -g`
* If there are still issues with configuration, click [here](https://angular.io/guide/setup-local) to see the full documentation on setting up local environment.
* Install [Angular.js]() by executing the following command from a command line
    * `npm install -g @angular/cli`    


## Part 2 - Create a new workspace and initialize the project
* From the root directory of the project, execute the following command from a command line to create a new workspace and initial starter app
    *  `ng new my-app`
* `add`, `commit`, and `push`, your changes to your remote repository as an initial _checkpoint_ for the project.
* Continue and complete the Tour of Heroes tutorial by clicking [here](https://angular.io/guide/setup-local#step-2-create-a-workspace-and-initial-application)
