# Operating system installation on radiation-lab-robot
 setting up the operating system on the single board computer (SBC) and all the required programms to make it an LAMP system (Linux Apache MySql PHP).
 the SBC is connected to: 
 - power via usb-c, 
 - internet via ethernet cable to router,
 - monitor via hdmi,
 - keybord via usb,
 - mouse via usb

 

## os used (Linux)
debian bullseye, 
installed from file: rk3588-usb-debian-bullseye-minimal-6.1-arm64-20240311.zip

more up to date os can be found on: "[https://download.friendlyelec.com/NanoPiR6C](https://download.friendlyelec.com/NanoPiR6C)"

it is flashed to an micro-SD card (SDHC to be precice) that is inserted to the SBC, and powered up.


## installng apache
This folder contains the original Assignment description (wishes, demands and intent).


## installing mysql
This folder contains the code on the SBC that continuously checks the queue in the database for tasks


## installing php
This folder contains the MySQL database design


# credits
Thanks to the "University of Utrecht" in the Netherlands, whom subsidised the project and provided the assignment.
In particular [Ing. L. van Leeuwen](https://www.uu.nl/medewerkers/LvanLeeuwen) whom aided us in this project.

Thanks to "[Spectrum Techniques](https://www.spectrumtechniques.com/)" whom cooperated whit us to control the ST365 Radiation counter externally over USB.
In particular [Rod Taylor]() whom provided the needed guiding document to do so.

Thanks to my students whom created the website, database and motor control as part of an high school research project.
O. Kaufmann and J. Wansink 


# License and copyright
We invoke GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007


   

