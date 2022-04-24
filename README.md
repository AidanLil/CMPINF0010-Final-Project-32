# CS0010 Final Project Group 32: February 30th

Our group submission for the CS0010 Final Project -- using data to determine the "best neighborhood" in Pittsburgh.

## Team members

- Wilson Biggs: wab41@pitt.edu
- Aidan Lillis: aml277@pitt.edu
- Jared Moynahan: jpm172@pitt.edu

## Datasets used
- Wilson Biggs:<br>
    -Neighborhood borders: https://data.wprdc.org/dataset/neighborhoods2<br>
        -Published By: City of Pittsburgh<br>
        -Description: Pittsburgh Neighborhoods<br>
    -Transit stop locations: https://data.wprdc.org/dataset/port-authority-of-allegheny-county-transit-stops<br>
        -Published By: Port Authority of Allegheny County<br>
        -Description: All transit stops within the Port Authority of Allegheny County's service area for the current 1909 schedule period: 9/1/2019 to 11/23/2019.<br>
- Aidan Lillis: <br>
    -Fire Incidents in the city of Pittsburgh: https://data.wprdc.org/dataset/fire-incidents-in-city-of-pittsburgh<br>
        -Published By: City of Pittsburgh<br>
        -Description: Contains data for all incidents of fire responded to by the Pittsburgh Bureau of Fire.<br>
- Jared Moynahan: <br>
    -Playgorund Equipment: https://data.wprdc.org/dataset/playground-equipment<br>
        -Published By: City of Pittsburgh<br>
        -Description: A listing of all playground equipment maintained by the city, including a description, the manufacturer, included safety surface and whether or not it is ADA accessible.
        
## Installation instructions
Our data analysis uses the rtree and seaborn 0.11.2 libraries which are not installed on JupyterLab by default, and can be installed with the following instructions on the terminal.<br>
pip install --user rtree <br>
pip install --user seaborn==0.11.2 <br>
