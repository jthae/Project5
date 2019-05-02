# Project5

Project 5

SUMMARY: The description of the lab is to create a frame for the Mesonet Hamming Distance functions to operate, 
and for the user to interact with the components in various ways.

CLASSES:
I only created a single class for the lab, in which both the creation of the frame and the interaction components are
housed. Within this class are methods for the creation of the frame, creation of the panel, calculation of
hamming distance, listing of items with the same hamming distance, and addition of the components to the panels.

METHODS:
HammingDistancePanel - extends from JPanel, creates an interactive panel with which the user may interact with to
calculate hamming distances for particular stations, add a station, or show a list of stations with the same
distance.
HammingDistancePanel - constructor for hamming distance panel, initializing dimensions of panel and adding
mouse listener.
calculateHammingDist - calculates hamming distances for a given station ID, looping through list of station
IDs.
sameHammingDist - creates a list of stations with the same hamming distances, with a given station and a 
given hamming distance.
HammingDistanceFrame - method which buildes and operates the GUI window. Components are added to the panels
here, and change listeners and action listeners are added to the buttons, dropdown menu, and slider.
