# Masterthesis on Developing a Software Defined GNSS Receiver for the Dragsail Cubesat.
This is the Masterthesis document of my final project of my Master in Electrical Engineering. 

In a team with other students of my university and a partner university a small satellite was developed, which _should_ launch some time in 2016 or 2017 (More info here: http://www.compass-project.de). 
Because we had some experiments planned which could alter the orbit of the satellite we wanted to 
have some means to find out the position of the cubesat.
"Normal" GPS chips do not work in space (and those that do are expensive), thats why we had to develop our own receiver.
For that purpose we have a a small GPS frontend chip onboard that would digitize the L1 GPS signal and provide the raw baseband signal.

My job was to develop the signal processing that would turn the raw signal into something useful.
