This is a colection of python programs designed to run on a RasberryPi 3 on the ADAMUS "baby robot"

test_thrusters.py
This script takes no arguments and sequetially pulses the thrusters for 2 seconds each

test_individual_thruster.py
This script takes one argument, a number between 1 and 8 which corisponds with the labels on the trusters
It pulses the selected truster for two seconds

tcp_client.py
This program sets up a tcp client which expects a string of 8 ones and zeros
eg. 11111111 00000000 10101010
It takes this string and sets the corisponding pins on the RasPi which in turn opens the trusters
A 1 corisponds to closed and a 0 corisponds to open.

tcp_server.py
This is a tcp server for sending single thrust vectors to the blink_client.py


