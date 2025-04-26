# Robust Aircraft Routing Testing Datasets
This repository contains two flight delay datasets used in the paper [Robust aircraft routing](https://pubsonline.informs.org/doi/abs/10.1287/trsc.2015.0657) by [Chiwei Yan](web.mit.edu/chiwei/www) and Jerry Kung, *Transportation Science*, 52(1), pp.118-133. If you use any of the material here, please include a reference to the paper and this webpage.

## Dimensions

 - Network 1 (N1), 106 flights, 24 aircraft
 - Network 2 (N2), 117 flights, 23 aircraft

## Contents

 - `N1_flights.csv`, `N2_flights.csv` contain flight info including flight_id, origin airport, destination airport, departure and arrival time (both in epoch time in milliseconds).
 - `N1_training.csv`, `N2_training.csv` contain training delay data for each flight over 31 days (July 2007); each row represents one day.
 - `N1_testing.csv`, `N2_testing.csv` contain testing delay data for each flight over 31 days (August 2007); each row represents one day.
 - `N1_original_route.csv`, `N2_original_route.csv` contain the original aircraft route used by the airline.
 
## Minimum Turn Time
 - Network 1 (N1), 30 minutes
 - Network 2 (N2), 20 minutes
