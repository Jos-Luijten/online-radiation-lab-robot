# online-radiation-lab-robot
 An real world robot that receives orders from online users of a website to take measurements of radioactive samples.
 

## global setup
An single board computer(SBC) hosts an website on which users can create a new task for the robot to perform. The user can chose from a few radioactive samples, absorbers, measurement distance and measurement time. When user is finished and sends his task, it will be added to a queue in a MySQL database.

on the SBC runs a program that continuously checks the queue and picks the next task to execute. it will steer and direct all the motors in preparation for the measurement. After which it will start the radiation counter and reads out the result. 

the result is then saved back in to the database, completing the task.
and the website can display the result, or the number of the queued tasks.

an webcam records a live stream witch is connected to the SBC which will be visible on the hosted website.


## assignment from university of Utrecht,
This folder contains the original Assignment description (wishes, demands and intent).


## design and code controlling sensors and actuators
This folder contains the code on the SBC that continuously checks the queue in the database for tasks


## design and code of MySQL database
This folder contains the MySQL database design


## design and models of mechanics
This folder contains the step files of the physical objects and the Autodesk fusion 360 project files


## design and code of website
This folder contains the htdoc's. such as: html, php, css and javascript code 


## operating system robot
This folder contains a copy of the operating system of the SBC. 
And a document containing explanation on the installed software and setup of the system.
Depending on the SBC, probably a type of L.A.M.P system


## parts and datasheets used in robot
This folder contains the lists of materials that were used, and their datasheets


# credits
Thanks to the University of Utrecht in the Netherlands, whom subsidised the project and provided the assignment.
In Particular [Ing. L. van Leeuwen](https://www.uu.nl/medewerkers/LvanLeeuwen) whom aided us in this project.

Thanks to my students whom created the website, database and motor control as part of an high school research project.
O. Kaufmann and J. Wansink 


# License and copyright
We invoke GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007


   

