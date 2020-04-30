# Expense/Income Tacker 


### Features
1. The server folder contains an Restful API using mongoDB as a backend.
2. The webapp folder contains an angualr js project as a Front-end.
3. Using JWT and brycpt to authenticate user and hash the password.
4. Using mat-dialog in angular material to add/edit item, using item index ad injector data: if index != null or undefined, edit; else add. The list of items is able to export.
5. The user data is protected by route authguard.
6. Using ChartJs to create viewable barcharts and piecharts.
7. Convert the current value to multiple countries' currency.
8. Display user information in profile, using progress bar to compare logged expense/income values, display customized current balance.

### Technologies used
    JavaScript, mongoDB, typescript, angular material, SCSS, bootstrap

### Requirements
    No  basic requirements to run this project. However, you may need Git to launch this js file.

### Steps to run
You need install Git firstly, then easily clone this repository link. Open project folder and launch the html with Chrome (on latest version) to see the output or with Visual Studio Code to check and edit the code.
1. Clone the repository.
2. Run `npm install` in both folders to install the dependencies.
3. Navigate to repo directory/server.
4. Under you mongoDB bin folder run `mongo.exe` to start the mongoDB service.
5. Run `node server.js/nodemon` to start the server on port `3000`.
6. Run `ng serve` on another terminal and navigate to directory/webapp to start the angular project.
7. Launch the http://localhost:4200/ to start the app.  

            
