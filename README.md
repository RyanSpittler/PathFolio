# PathFolio #
## The Online Character Sheet Helper ##

This project is currently in development as a personal project. [Visit the deployed project here](http://pathfolio.herokuapp.com).

## Running This Project ##
If you would like to run this project yourself, fork the repository. 
In the application's directory, insert keys into the `copy_of_.env` file and rename the file to be `.env`. 
Then in the application's directory run:

```
    rake db:create db:migrate
    dotenv rails s
```
In your browser, visit localhost:3000.

## Specifications ##

* Ruby Version: 2.1.5
* Tests: RSpec
* Environment Variable Management: dotenv
