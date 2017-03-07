-----------------------------------------------------------------------------------
# RPieces-TableTopXYZ
-----------------------------------------------------------------------------------
A Simple and Printable TableTop XYZ Motion Frame using 28BYJ-48 Unipolar Stepper
Motors.

<img src="./images/SmallCropped_SAM_2709.png" height="400" width="400">

The RPieces TableTopXYZ Frame is a project that will attempt to create a simple one
day build of an all in one 3D Printer, Mill, and Plotter.  The project will minimize
the use of linear bearings in place of 3D Printed Rails and minimize the use of 
timing belts in place of 3D-Printed Pinions ( Thus the R.=Rack & P.=Pinion 
abbreviation in RPieces naming convention )

-----------------------------------------------------------------------------------
#Project Status
-----------------------------------------------------------------------------------
RPieces-TableTopXYZ is still in a development phase and has no official releases.  

-----------------------------------------------------------------------------------
#Cost and Materials
-----------------------------------------------------------------------------------
Building this project requires

    - (1) 3D Printer with a build surface of at least 190mm x 190mm   ... $N/A
    - (1) Arduino UNO microcontroller                                 ... $ 3.34
    - (4) 28BYJ-48 Stepper Motors with ULN2003 Drivers                ... $10.34
    - (~20) Male to Female Dupont jumpers                             ... $ 2.20
    - (1) 5Vdc Wall-module Power Supply adapter at ~2A                ... $ 3.10
    - (4) #6-32 x 2" Long Machine Screws or equivalent                ... $ 0.24
    - (8) #6-32 x 1-1/4" Long Machine Screws or equivalent            ... $ 0.40
    - (4) #6-32 x 3/4" Long Machine Screws or equivalent              ... $ 0.20
    - (26) Corresponding hex nuts (#6) for machine screws             ... $ 1.30
    - Modified GRBL Firmware @ https://github.com/tgit23/GRBL-28byj-48-Servo
    - Grbl Controller Software @ http://zapmaker.org/projects/grbl-controller-3-0/

TOTAL ESTIMATED COST (not including filament): $21.22

-----------------------------------------------------------------------------------
#Getting Started
-----------------------------------------------------------------------------------
Assembly document can be found @ https://github.com/tgit23/RPieces-TableTopXYZ/blob/master/docs/RPieces-TableTopXYZ-User-Assembly.pdf

I.e. /docs/RPieces-TableTopXYZ-User-Assembly.pdf

Before trying to control the model;  Setup the parameters of 'grbl' firmware through
the 'grbl controller' command interface by entering the following commands.

    - $0=30
    - $100=100
    - $101=100
    - $102=100
    - $110=120
    - $111=120
    - $112=120
    
You can now load a file from the \nc-examples folder into grbl controller for unit
testing.

Example Video @ https://youtu.be/4aUQkjFIM5M

-----------------------------------------------------------------------------------
CONTRIBUTING
-----------------------------------------------------------------------------------
Anyone interested in joining this project can email
tgit28@gmail.com with a return email address.  Details of what can
be done and what needs done can be negotiated from there.

We'd really appreciate any extra man-power we can gather..
