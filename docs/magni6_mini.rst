Magni 6 Mini
===========

.. image:: /_static/magni-mini/magni6_mini.jpg
   :alt: Magni 6 Mini
   :width: 400px
   :align: center

.. the "|" adds vertical space in the page.
|

The Magni 6 Mini is a compact, versatile robotic platform designed for educational, research and hobby applications. 
With its lightweight frame and modular design, it's perfect for indoor navigation, SLAM experiments, and small-scale automation projects.

Sneak peak
----------

.. raw:: html

    <div style="display: flex; justify-content: center;"> 
        <iframe 
            width="560" height="315" 
            src="https://www.youtube.com/embed/1VUnxondorA" 
            frameborder="0" 
            allowfullscreen 
            referrerpolicy="no-referrer-when-downgrade">
        </iframe>
    </div>

|

Overview
--------

The Magni 6 Mini is the smallest model in the Magni 6 family. It offers balance of portability and functionality. 

Key features include:
    - Compact design for tight spaces.
    - Built-in LIDAR sensor for navigation and maping.
    - Support for ROS2, Open-RMF, and EZ-MAP software.
    - Ideal for beginers and advanced users alike.


**Get Started**: :doc:`./getting_started/getting_started_mini`


Build Specifications
--------------------
==================  =========================
**Feature**         **Specification**
==================  =========================
Dimensions          [add dimensions here]
Weight              [add weight here]
Max Payload         [add max payload here]
Frame               [add chassis info here]
Wheels              [add wheels here]
Battery             [add batteries here]
==================  =========================


Sensors
-------

**Built-in Sensors**:
    - :doc:`Short-range LIDAR <../hardware/lidars>`
    - :doc:`Raspberry Pi Camera <./hardware/raspberry_pi>`

**Supported Add-ons**:
    - sensor 1 
    - sensor 2
.. TODO: Ask ragarding which sensors would be compatible.


Projects
--------

.. note::
    Test all projects in an obstacle-free environment to ensure safe operation.


.. warning::
    Testing on a table top can lead to flying robots. Please when driving and testing the robot, keep it on the floor.




Here are three suggested projects for the Magni 6 Mini. Using the short-range Lidar and the Pi Camera:

- **Room Mapping Starter**: Create a 2D map of your environment using the short-range LIDAR and Ez-Map software. Ideal for learning SLAM basics.

    See: :doc:`./projects/ezmap`


- **Obstacle Avoidance**: Program the Magni 6 Mini to navigate around obstacles using the short-range LIDAR for proximity detection. Perfect for beginners experimenting with autonomous navigation.

    See: :doc:`./projects/obstacle_avoidance`

- **Live Video Patrol**: Use the Raspberry Pi Camera to stream live video, turning the Magni 6 Mini into a mobile surveillance bot. Great for remote monitoring.

    See: :doc:`./projects/telepresence`


