# Aircraft Boarding Simulation Analysis

## Project Description
This project simulates the airplane boarding process in order to evaluate the efficiency of different boarding strategies.  
The simulation models passenger behavior, seating arrangements, and delays during boarding.

## Objectives
- Simulate different boarding methods  
- Compare boarding times across strategies  
- Analyze performance using statistical methods  
- Identify which boarding strategy is most efficient  

## Simulation Model
The model is based on the following assumptions:
- The airplane contains 50 rows with 6 seats per row  
- Each passenger has an assigned seat  
- Boarding occurs from a single entrance  
- Luggage storage time follows an exponential distribution  
- Delays may occur when passengers block each other in the row  
- Multiple passengers may organize in parallel depending on seating order  

## Boarding Strategies
The following methods were simulated:
1. Random boarding  
2. Boarding by increasing row order  
3. Boarding by decreasing row order  
4. Steffen Method - boarding passengers based on seat order so they do not interfere with each other while seating  

## Methodology
- Each strategy was simulated 100 times  
- Boarding time was recorded for each run  
- Statistical analysis was performed, including:
  - Mean boarding time  
  - Confidence intervals  
  - Comparison between strategies (e.g., ANOVA / Kruskal-Wallis)  

## Key Insights
- Boarding strategies significantly affect total boarding time  
- Structured boarding methods tend to outperform random boarding  
- Passenger interference (blocking) plays a major role in delays  

## Tools and Technologies
- Python  
- NumPy  
- Pandas  
- Matplotlib  

## Project Structure
- `aircraft_boarding_simulation.ipynb` - Simulation and analysis code  
- PDF report - Results, graphs, and conclusions  

## Conclusion
This project demonstrates how simulation and statistical analysis can be used to evaluate real world processes and optimize decision making.
