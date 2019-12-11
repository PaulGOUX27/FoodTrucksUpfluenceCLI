# FoodTrucksUpfluenceCLI
CLI related to the [FoodTrucksUpfluence](https://github.com/PaulGOUX27/FoodTrucksUpfluence) project.  
The purpose of this project is to provide a CLI using the **FoodTrucksUpfluence API**.  
This CLI is developped under **python3**.


## Installation
You might probably have to install `requests` : 

    pip install requests

## Usage
CLI is located in `src` directory.
Upon in this directory, to see entire help, type :

    python3 foodTruckUpfluenceCLI.py --help

## More Informations
This CLI retreive parameters using `getopt`, verify them and send an HTTP request using `requests` to the API server (at `localhost:8080`).
After, it will display some relevant informations to the standart output depending on the response status code.
For more information, please see https://github.com/PaulGOUX27/FoodTrucksUpfluence/blob/master/README.md.

## Go Further
* Dynamically set up the URL (with `localhost:8080` as default URL)
