# Subway-Planning

Write a function, subway, that takes lines as input (read more about the \**lines notation in the instructor comments box below) and returns a dictionary of the form {station:{neighbor:line, ...}, ... } 

For example, when calling subway(boston), one of the entries in the resulting dictionary should be 'foresthills': {'backbay': 'orange'}. This means that foresthills only has one neighbor ('backbay') and that neighbor is on the orange line. 

Other stations have more neighbors: 'state', for example, has 4 neighbors. Once you've defined your subway function, you can define a ride and longest_ride function. 

ride(here, there, system) takes as input a starting station (here), a destination station (there), and a subway system and returns the shortest path. 

longest_ride(system) returns the longest possible ride in a given subway system. 
