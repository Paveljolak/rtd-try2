Ez-Map Introduction
===================

Welome to **EZ-Map** - a toolkit for mapping environments using LiDAR, setting up autonomous routes, or manaully driving a robot with video streaming and remote control.

.. TODO: Add image or video here. Or both. 

Setup
#####

Before you begin, make sure you have all the required hardware and components ready.

Magni Robot
-----------

To run EZ-Map, you need a Magni robot. 
If you're new to the platform, start with the :doc:`Start Here <../../getting_started/requirements>` guide.

Choose your robot model and follow the relevant :doc:`Getting Started guides <../../getting_started/models/main_getting_started_models>` and the :doc:`Full Assembly guides<../../magni6_models/full_assembly/main_assembly_models>`.

LiDAR Sensor
------------

A mounted LiDAR is required for mapping. EZ-Map currently supports the following models out of the box:

- :ref:`n10_lidar`
- :ref:`ms1l_lidar`


.. TODO: Add the links and the right lidars here.


Other LiDARs may work if the appropriate ROS driver is installed. 
For unsupported models, contact Ubiquity Robotics support.

.. TODO: add the link to ubiquity support here.


.. note:: 
    This documentation assumes you're using a clean Ez-Map image. 
    Disregard any manual configuration steps mentioned in other setup guides.


Pi Camera
---------

The Pi Camera provides video streaming and fiducial marker detection.
It should come pre-mounted on Magni 6 Robots.

If your camera is not installed, refer to the :doc:`assembly guides<../../magni6_models/full_assembly/main_assembly_models>` for your specific robot model.

EZ-Map Software Image
---------------------

You will receive the Ez-Map `img.xz` software image by email.
After downloading, follow the guide to flsh it to a microSD card.

.. TODO: Confirm if a flashing guide will be added. If yes, link it here. Include it in the software section.

To verify the version you are using, refer to the Changelog.

.. TODO: Ask whether we have a new Changelog page or it is the same one. Add a Changelog page to this documentation and link it here.

How to use EZ-MAP
-----------------

Once setup is complete and the robot has booted, you're ready to start using Ez-Map.

[TODO: Getting Started Content Coming up.]





