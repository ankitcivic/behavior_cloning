# behavior_cloning
The Scaled Autonomous Vehicles deals with the concepts involving building, running the scaled version of a race car autonomously in a certain desired track under the guidance of Dr. Venkat Krovi, Michelin Endowed Chair Professor of Vehicle Automation. The course is offered during the spring 2020 at Clemson University, CUICAR. We are a team of 3 automotive enthusiasts Ankit Verma, Naga Venkata Sai Teja Allam and Siddhesh Naresh Bhagkar eyed on achieving the level 3 autonomy with the scaled vehicle. The primary goal of the project is to achieve the level 3 autonomy by using CNN and end to end learning algorithms. The vehicle should autonomously perform the obstacle avoidance, lane keeping tasks tested in different tracks.

This project is build on two software packages
1) Donkeycar - to implement Behavior Cloning
2) WilShelby's - to validate the model

Details of both are given below


DONKEY CAR
Donkeycar is minimalist and modular self driving library for Python. It is developed for hobbyists and students with a focus on allowing fast experimentation and easy community contributions.\
Quick Links\
Donkeycar Updates & Examples: https://www.donkeycar.com/ \
Build instructions and Software documentation: http://docs.donkeycar.com/ \
Discord / Chat: https://discord.com/invite/PN6kFeA \


WilShelby's
WilShelby's RC Car ML Development with Goggle Colab package offers and easy to use end to end learning model that also validates the model on the following parameters
1) Mean Model Squared error loss
2) Histogram of Predicted Error
3) Scatter Plot of Error
Quick Link: https://www.wilselby.com/2020/01/rc-car-ml-model-development-with-google-colab/

Our Implementation
We found Donkeycar package more reliable and easy to implement on a scaled vehicle. We modified the Hardware and used an F1/Tenth vehicle instead.
We deployed the car or the following test tracks
1) Indoor Lab setting, Floroscent light
2) Pedestrian Side walk, Daytime
3) On road, Night time
4) Scaled Race Track, Daytime
5) Simulation, Gazebo

Our Validation
We used the three validation matrices as offered by the WilShelby's package, which are MMSE, HPE and SPE. Apart from these, we used Mistakes per Meter as the fourth parameter to test the model.

