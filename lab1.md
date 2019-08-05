## Description

You are required to implement a `python` application that emulates an Airline Reservation System.
The system should implement the following:

* Import a fleet of aircraft from a CSV file (format of the CSV is as follows):
    
| ID | Registration | Brand  | Model       | Max_Pax | Max_Crew | Max_Bags_Kg |
|----|--------------|--------|-------------|---------|----------|-------------|
| A1 | G-ABCD       | Boeing | 777-200     | 315     | 12       | 2000        |
| A2 | G-XYXW       | Airbus | A320-200    | 150     | 5        | 700         |

* Import routes from a CSV file (format of the CSV is as follows):
   
| Route_ID | From_IATA | To_IATA | Aircraft | Model    |
|----------|-----------|---------|----------|----------|
| R1       | LHR       | EWR     | Boeing   | 777-200  |
| R2       | EWR       | LHR     | Boeing   | 777-200  |
| R3       | FCO       | LHR     | Airbus   | A320-200 |


The reservation system should have the following functionality (via a menu of some sort):
* For the airline:
   * Import the aircraft fleet CSV
   * Import the route CSV
   * List routes
   * List fleet
   * List route/fleet relations
   * Show statistics for route booking

* For the passengers:
   * Allow to list available routes with their seating availability
   * Allow to book a seat (& baggage) for a specific route
      * Show the necessary warnings when max pax or max bags kg is reached 
   * Print an itinenary of the booked seat


  
