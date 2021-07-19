# MAMMOBOT_UoB_Public
This is a public copy of the model using in the paper:
Carmen Larrea, Pierre Berthet-Rayne, S.M.Hadi Sadati, Daniel Richard Leff, Christos Bergeles, and Ioannis Georgilas, "Growing Robotic Endoscope for early Breast Cancer Detection: Robot Motion Control"

DESCRIPTION

I order to run the simscape files "lin_c_ts", "kings_ts" and "variables_5" must be open in the workspace

The file "simscape_actuation_22_idealtorque" Has an ideal torque source as a driver. This would be the forward dynamic model in which the pressure desired is inputted.
To process the data from here in MATLAB go to the data processing folder and run "Data_compare_length_3".

The file "simscape_actuation_22_withmotor" is the model with the stepper motor as a driver. The length is inputted in here
To process the data from this model go to the data processing folder and run "Data_compare_pressure_3"

The copyright for the file MAMMOBOT experiment set-up.PNG belongs to King's College London and the Robotics and Vision in Medicine Lab https://rvim.online.
A version of the picture is featured in the paper: https://doi.org/10.1109/LRA.2021.3068676

