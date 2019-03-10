# Weather-Py

* Retrieves and analyzes the weather data of 500+ random cities in order to visualize the weather at varying distances from the equator.


## Table of Contents

[:computer:  Technologies Used](#technologies-used)

[:dvd:  Installation and Usage](#installation)

[:boom:  Features](#features)

[:bust_in_silhouette:  Developer](#developer)

[:email:  Questions or Comments](#questions-or-comments)


## <a name="technologies-used"></a> :computer: Technologies Used

* Python
* Modules
    * os
    * json
    * pandas
    * numpy
    * matplotlib
    * requests
    * time
* Jupyter Notebook
* citipy
* OpenWeatherMap

## <a name="installation"></a> :dvd: Installation and Usage

* Clone the Weather-Py repository to your local computer.
* View the files in Jupyter Notebook or an editor with a Jupyter Notebook extension.


## <a name="features"></a> :boom: Features

* randomly selects at least 500 unique (non-repeat) latitude and longitude combinations
* requests the nearest city to each latitute and longitude combination using citipy
* requests weather data on each city from OpenWeatherMap
* displays the weather data in a dataframe
* saves the weather data in a csv file
* builds scatter plots to demonstrate the relationship between latitude and each of the following: temperature, humidity, cloudiness and wind speed
* reports findings


## <a name="developer"></a> :bust_in_silhouette: Developer

* Maria Wong


## <a name="questions-or-comments"></a> :email: Questions or Comments

If you have any questions or comments, feel free to message me on [LinkedIn](https://www.linkedin.com/in/maria-wong/).

 ### Thanks for checking out Weather-Py!