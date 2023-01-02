# Traveling-saleperson-problem
TSP problem using brute force algorithm 


This is a program to solve the traveling salesman problem (TSP). It reads in a file with city data and calculates the shortest tour of all the cities. The TSP class has two functions: TSP_solution, which reads in the city data from the file and calls minimumDistancecoverandTour, and minimumDistancecoverandTour, which calculates the minimum distance and tour of all the cities.

The TSP_solution function initializes the start city and calls minimumDistancecoverandTour with the city data, start city, and an empty tour vector. The minimumDistancecoverandTour function calculates the minimum distance and tour by keeping track of the visited cities and adding up the distances between the current city and the nearest unvisited city. When all cities have been visited, the function returns to the starting city and adds the distance to the total distance before returning the total distance.

The main function reads in the file and stores the city data in two vectors, city and dist, before calling the TSP_solution function.
