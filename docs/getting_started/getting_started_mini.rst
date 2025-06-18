Getting Started with Magni 6 Mini
=================================

This guide cover unboxing and setting up your :doc:`../magni6_models/magni6_mini` robot. 
For general requirements and connectivity, see :doc:`./requirements` and :doc:`./connecting`. 

Unboxing
--------

The Magni 6 Mini package includes the following:
    - 1x Magni 6 Mini Robot (pre-assembled)
    - 1x Battery Charger (see: :doc:`../hardware/batteries` on how to charge.)
    .. TODO: Image of the battery Charger.

.. image:: /_static/magni-mini/unboxing_mini.jpg
   :alt: Unboxing Magni 6 Mini
   :width: 400px

|

**Initial Inspection Checklist**:
    - Verify all components are included and undamaged. [TODO: We will add here images of all the components so users can check.] 
    - Check for loose connectors or wheels.
    - Ensure the Lidar on top of the cover is undamaged.
[ TODO: We will add video to show the checking process. ]

.. TODO: Create a video for the check above, also add pictures there.
.. TODO: Video of proper wiring. When we fix the wiring.

|
.. TODO: Add images here.
[images here of the componenets]

Setup
-----

Battery Installation and Safety
###############################

Ensure the Magni 6 Mini's two Lead-Acid batteries are safely installed and charged before powering on.

1. **Inspect the Batteries**:
    - Check for visible damage (e.g., swelling, leaks, or cracks).

2. **Secure the Battery**:
    - Connect the batteries to the Motor Controller Board (MCB), the switch, and to each other using the provided connectors.
    - Ensure the connection is firm to avoid power issues.

.. image:: /_static/magni-mini/batteries_and_cables.jpg
   :alt: Secured batteries
   :width: 400px
   :align: center

|

3. **Charge the Battery**:
    - Use a multimeter to check the batteires voltage. Keep the batteries always charged.
    - Once the batteries are inside the robot use the provided charger to charge them.

.. warning:: 
    - Do not use a damaged battery, as it may pose a safety hazard.
    - Charge in a well-ventilated area away from flammable materials.
    - See :doc:`../hardware/batteries`


Powering up the Robot
#####################

1. Locate the white power switch on the back of the Magni 6 Mini and turn it on.

.. image:: /_static/magni-mini/mini_whiteSwitch.jpg
   :alt: Power Switch 
   :width: 400px
   :align: center

.. TODO: Add a better image for the switch.

2. Confirm the Raspberry Pi's green LED is illuminated. This indicates the robot is powered on.

.. image:: /_static/images/magni6_mini/raspberry_pi_light.jpg
      :alt: Raspberry Pi Light
      :width: 400px
      :align: center
      :caption: Raspberry Pi Light

The robot is now powered on and ready for connection.

Connecting to the robot
#######################

See :doc:`./connecting` for general connectivity guides. The Magni 6 Mini emits its own Wi-Fi for SSH access, or you can connect via home network.

**Option 1: Connect via Robot's Wi-Fi**

1. Open a terminal.
2. SSH into the robot:

.. code-block:: bash

    ssh ubuntu@10.42.0.1

3. You will be prompted a password, the password is: **ubuntu**

.. TODO: Add an image here.
[Image here]

|
|

**Option 2: Connect via Home Network** 


1. Connect to the robot to your local network:

.. code-block:: bash

    sudo nmcli device wifi connect <AP name> password <password>


Example:

.. code-block:: bash

    sudo nmcli device wifi connect myhotspot password mypass1234


2. Open a new terminal (the first will be frozen).
3. Identify the robot's IP address on the network (hostname: **ubuntu**).
4. SSH into the robot:

.. code-block:: bash

    ssh ubuntu@[robots IP]


You are now connected to the robot with Internet access.

Test Driving the robot
######################

To drive the robot you must fulfill the following requirements: 

1. Ensure the robot is powered on.
2. Open three terminal sessions connected to the robot (via SSH)
3. Activate the MCB by pressing the button closest to the wires.

.. image:: /_static/magni-mini/mini-MCB_buttons.jpg
   :alt: MCB buttons
   :width: 400px
   :align: center

|

.. warning:: 
    Place the robot on the ground before driving to prevent it from falling off a table.


4. In each terminal, run the following commands (one per terminal):


.. code-block:: bash

    zenoh



.. code-block:: bash
    
    zenoh bridge


.. code-block:: bash

    teleop


5. Focus on the third terminal and follow the teleop instructions to drive the robot.
