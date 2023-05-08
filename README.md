Download Link: https://assignmentchef.com/product/solved-solved-cs21120-competition-management-system
<br>
<h4>Assignment 1 Competition Management System</h4>

Objectives

The aim of this assignment is to give you experience in writing and using some basic data structures. The objective is to write a system for managing competition matches with a variety of possible rules.

Overview

Many competitions involve matches between pairs of players e.g. Wimbledon tennis championships, the football world cup, world chess championships, etc. Competitions such as Wimbledon use a single elimination style of competition, where pairs of players play each other and the loser leaves the competition and the winner goes on to the next round until a winner is decided.

Assuming each player always plays to their ability, such a competition is guaranteed to find the correct winner. The single elimination style of competition doesn’t provide much information about relative ability of other players. For example the second best person in the competition could go out to the eventual winner in the first round, or the other finalist could be half way down the ranking if they had a particularly lucky draw.

Other systems have been developed to overcome these problems, such as a league or round robin, where every team plays every other team, or various forms of repechage, where losers are allowed to carry on in some way with a second chance to win places. In this assignment you are asked to develop a system for managing such competitions, with the precise style of competition implemented by a class that manages matches between competitors. The system should read a list of players (e.g. individuals or teams) from a text file (one per line). It should then print out the players for each match and request user input to indicate the winner.

The system should then print out the winner and any runner up places the system has determined. The result for a match is in the form of an integer numerical score and there should always be a winner (no draws). The system should warn the user if some incorrect input (e.g. not a pair of numbers or a draw) is entered and request input again. You have been provided with a basic command line program for this. For simplicity the competition manager doesn’t need to worry about matches happening at the same time, or publishing the full draw before the start of the competition. Requirements You need to implement 3 versions of the provided IManager interface. Each must be defined in the package uk.ac.aber.dcs.