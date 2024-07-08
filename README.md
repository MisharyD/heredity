# Herdity
This is a project part of the CS50AI course. I have only written the 3 main functions: joint_probability, update, and normalize.<br> 
This program calculates the probabilities of each person in a family having a specific genetic trait (in the course, it is the GJB2 gene) by considering all possible gene and trait configurations. <br> 
then accumulating and normalizing these probabilities based on given genetic and trait data, the program takes a csv file for the family like the one in the data folder. A Bayesian network was used to model the idea that a child gene is dependant on parents gene.

## Usage:
python3 heredity.py data.csv <br>

examples of the .csv file is given in the data directory

