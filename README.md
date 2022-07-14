# Coffee Shop World
This repo contains a modified version of the cafe.world model from gazebo where you can find 4 tables with their chairs to make it more realistic. The collision of the walls has been edited as well to make it more accurate in the mapping process. 

You can use this world to test an indoor delivery robot that can deliver food and drinks to tables, you will find 4 tables and the kitchen where the robot can navigate through them.

![image](https://user-images.githubusercontent.com/89264196/179001802-a56d171b-50ab-48e2-862d-3e967c4583b7.png "Plan View of the World")

The map has been done using the Gmapping package which provides laser-based SLAM (Simultaneous Localization and Mapping).

![image](https://user-images.githubusercontent.com/89264196/178996647-69bdc31e-af5b-4053-b22e-242018d0b4cc.png "Plan View of the Created Map")

## How to Load a World File into Gazebo
Navigate to the world folder and open the terminal inside this folder then write the following command:

`gazebo cafe.world`

## How to Use the Map in Your Project
Copy the .yaml file into the maps folder in your robot package and start to navigate through it.
