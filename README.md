# Threads and Semaphores:vertical_traffic_light: : Producer–consumer problem
Project made in Java using threads and semaphores for the subject of Operating Systems. <br><br>
![Screenshot of the game](/screenshot.png?raw=true "Screenshot") <br><br>
UI implemented in JavaFx. <br><br>
It solves a case producer-consumer problem which is a Synchronization classic problem. In this problem we have a playground where children play. We can create a child with or without ball. If it has ball then it spends a time playing and then puts the ball in a basket and chills. If it doesn't have a ball it chills for a determined time and then tries to get a ball from the basket. If there's no ball in the basket it gets blocked until it can get a ball. The basket has a max capacity and if the child tries to put the ball and the basket is full it gets blocked as well. We've used semaphores to control the basket and to make sure there are no synchronization problems. <br><br>
The problem statement can be read in Portuguese [here](/Problema%20-%20Brincadeira%20de%20criança.pdf)
