
# Cuatro Elementos

The idea of this project is to combine the musical performance of free improvisation with a digital mobile application that will be operated by the public. In this way, environments, textures, climates and new soundscapes will be generated.
One of the objectives of this project is to represent the four elements of nature: air, earth, water and fire. For example, granular synthesis could be used to represent air or water.
The application is designed and developed for mobile devices that work with the Android operating system and has a simple and intuitive graphical interface.
It is not necessary to have an internet connection to install the application on the device and it is not required to have musical knowledge to use it.

This project could be divided into two parts:

  - Musical performance:  each element will be represented one by one, connecting the clients to the server. For example, the air element will be the first one and the user will be able to listen it’s features by controlling the axis XYZ of the phone’s screen. Once each element is presented, the elements will be able to be combined by playing duets or combining each one of them at the same time. 
  - Digital musical performance: it consists of a server that will act as a provider of digital sound banks to interact with the connected clients through the application. The sounds will be controlled by the mobile sensors: gyroscope and touch screen.


During the musical performance, the audience will have the possibility to interact with the improvisation being carried out, using the application as if it were an instrument that appears in the scene. 
Bellow you can find a graphical representation of the project idea:

[![N|](https://i.ibb.co/BG5zpHt/cuatro-elementosv2.png)]

# cuatro elementos wifi:
## 1) Install server_side requirements::
   * pip install -r requirements.txt
   * On linux use app_linux.py
* You can share wifi with linux with "create_ap" tool: https://github.com/oblique/create_ap , make sure you have wireless AP mode features in your wifi device.
* to share wifi you can go: sudo create_ap -n wlp3s0 Nature Nature123 -g 192.168.0.1


### Todos

 - Write MORE Tests
 - Improve performance

License
----

MIT

**Free Software, Oh Yeah!**

