Asembly of Magni 6 Mini
=======================

This guide provides step-by-step instructions to build the Magni 6 Mini.

.. note::
    If any parts listed are missing, check the Magni BOM for ordering details.
    If unavailable online, contact: `Ubiquity Robotics support <support@ubiquityrobotics.com>`_ for replacements.

[TODO: We will add the link to the Magni 6 BOM order details here.]

.. TODO: Add details regarding the ordering of the items, and from where they can be ordered.


Buiild Requirements
###################

The following tables list the Magni 6 Mini BOM. Verify all required materials are present before starting, and order if missing. 
Similar componenets may substitute, but using the specified BOM items is recommended to prevent build issues.


.. list-table::
   :header-rows: 1

   * - **Screws BOM**
     - 
   * - BOLT M2,5x14 ((8.8) Zn) ISO 7380
     - 5
   * - BOLT M2,5x10 ((8.8) Zn) ISO 7380
     - 2
   * - BOLT M2,5x8 ((8.8) Zn) ISO 7380
     - 17
   * - BOLT M2x14 ((8.8) Zn) ISO 7380
     - 2
   * - BOLT M2x5 ((8.8) Zn) ISO 7380
     - 8
   * - BOLT M2,5x5 ((8.8) Zn) ISO 7380
     - 2
   * - BOLT M4x8 ISO 7380
     - 10
   * - WASHER 2,7 (Zn) DIN 125
     - 22
   * - WASHER 4,3 (Zn) DIN 125
     - 6
   * - SPACER L=12 F_M2,5
     - 4
   * - PCB PUSH PIN WITH SPRING
     - 2

|

.. list-table::
   :header-rows: 1

   * - Other BOM
     - 
   * - BASIC
     - 1
   * - TOP COVER
     - 1
   * - FRONT COVER
     - 1
   * - FIREWALL
     - 1
   * - BATTERY HOLDER
     - 1
   * - HEAT SINK
     - 1
   * - MOTOR WHEEL
     - 2
   * - CAMERA MODULE 3 V8
     - 2
   * - 5.5 x 2.1 mm DC POWER CHARGER
     - 1
   * - SINGLE BALL ROLLER BEARING
     - 1
   * - RUBBER TYRE
     - 2
   * - ON/OFF ROCKER SWITCH
     - 1
   * - LIDAR
     - 1
   * - RASPBERRY 5
     - 1
   * - MOTOR BOARD
     - 1
   * - BATTERY
     - 2
   * - SONAR
     - 15
   * - COVER CAP
     - 16
   * - LIDAR
     - 1
   * - RUBBER PAD
     - 1
   * - MOTOR WHEEL
     - 2
   * - RUBBER SOCKET
     - 1



Assembly Guide
##############


Final Look
----------

.. image:: /_static/magni-mini/assembly/preview.png
    :alt: Magni 6 Mini Preview
    :width: 400px
    :align: center

|

Step-by-Step Guide
------------------

1. Take BASIC sheet metal part, SINGLE BALL ROLLER BEARING, RUBBER PAD and 2x BOLT M2, 5x5 ((8.8) Zn) ISO 7380 and bolt together - Tighten the hex key using just two fingers - do not overtighten. 

.. image:: /_static/magni-mini/assembly/chasis.png
    :alt:  Chasis Image
    :width: 400px
    :align: center
|

.. raw:: html
   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/bearing_adding.jpeg" alt="Bearing adding with rubber." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/bearing_screwing.jpeg" alt="Bearing added and screwing." style="width: 50%; height: auto;">
   </div>

|


2. Take MOTOR WHEEL and BASE. 

.. image:: /_static/magni-mini/assembly/motor_wheel_and_base.png
    :alt: Motor Wheel and Base
    :width: 400px
    :align: center

|

3. Grab motor wheel small connector and push it through the oppening (slide it diagonally)

.. raw:: html
   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/motor_wheel_connector.png" alt="Sliding motor wheel connector through opening pic 1" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/motor_wheel_connector_added.png" alt="Sliding motor wheel connector through opening pic 2" style="width: 50%; height: 50%">
   </div>

|


4. Grab the second connector and push it through (mind the orientation).

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/second_motor_wheel_connector.png" alt="Sliding motor wheel second connector through opening pic 1" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/second_motor_wheel_connector_added.png" alt="Sliding motor wheel second connector through opening pic 2" style="width: 50%; height: 50%">
   </div>

|


5. Take screws M4x8 ISO 7380 and with your fingers thread the bolt in just slightly, until it catches. Then turn the BASE on the side (so the wheel is looking up on the table; that way is more easy to thread in the second bolt). Take the second bolt and thread it slightly. Finally thread in the last bolt. 



.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/motor_wheel_screwing.png" alt="Installing motor wheel on the chasis pic 1" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/motor_wheel_cable.png" alt="Installing motor wheel on the chasis pic 2" style="width: 50%; height: 50%">
   </div>

|


.. image:: /_static/magni-mini/assembly/motor_wheel_screwing_lower.png
    :alt: Screwing motor wheel to the chasis.
    :width: 400px
    :align: center
|



6. Once all three bolts are partially threaded, use allen key and tighten them firmly.

.. image:: /_static/magni-mini/assembly/motor_wheel_tightening.png
    :alt: Tightening motor wheel on the chasis
    :width: 400px
    :align: center
|



7. Repeat the same steps for the other side to get the setup on the page below. 

.. image:: /_static/magni-mini/assembly/base_with_motor_wheels.png
    :alt: Chasis with Motor Wheels Installed
    :width: 400px
    :align: center
|

8. Take the double-sided thermally conductive tape and cut two strips measuring 70x20 mm. Apply the strips to the FIREWALL as shown in the picture. Then, remove the protective film from the top side of the tape. The surface is now prepared for mounting the motor control board.


.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/firewall.png" alt="Firewall " style="width: 30%; height: auto;">
     <img src="/_static/magni-mini/assembly/firewall_with_tape.png" alt="Firewall with tape." style="width: 30%; height: auto">
     <img src="/_static/magni-mini/assembly/firewall_with_tape_pilled.png" alt="Firewall with tape pilled." style="width: 30%; height: auto">
   </div>

|

9. Take the Motor Controller Board and carefully press it onto the double sided thermally conductive tape,l as shown in the picture. Ensure that the mounting holes on the Motor Controller Board are aligned concentrically with the slots on the FIREWALL, as ilustrated.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/MCB.png" alt="MCB preview." style="width: 60%; height: auto;">
     <img src="/_static/magni-mini/assembly/MCB_with_firewall.png" alt="MCB with FIREWALL." style="width: 45%; height: auto;">
   </div>

|


10. Take SPACER L=12 F_M2.5, washer 2.7 and BOLT M2, 5x8 ((8.8) Zn) ISO 7380 and tigthen together FIREWALL and PCB.

.. Warning::
  Do not tighten fully!

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/show_standoffs_and_screws_for_firewall.png" alt="FIREWALL to PCB installation pic 1." style="width: 60%; height: auto">
     <img src="/_static/magni-mini/assembly/standoffs_added_to_firewall.png" alt="FIREWALL to PCB installation pic 2." style="width: 40%; height: auto">
   </div>

|


11. Take rubber pad 15x10x3mm and place it between FIREWALL and Motor Controller Board like shown in the picture at the edge of the PCB. The rubber pad acts as a spacer to make sure Motor Control Board is in parallel to FIREWALL surface. Then tighten the bolt gently using only two fingers on the hex key. Place the same rubber pad on the other side near the bottom bolt sloth opening. 

.. note::
  The PCB and FIREWALL should be PARALLEL! 

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/show_rubber.png" alt="Rubber between MCB and FIREWALL pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/add_rubber.png" alt="Rubber between MCB and FIREWALL pic 2." style="width: 50%; height: 50%">
   </div>

|


12. SPACER L=12 F_M2.5, washer 2.7 and BOLT M2.5x8 ((8.8) Zn) ISO 7380 and tighten gently together FIREWALL and PCB on the top side as shown in the picture. Verify again that the PCB is mounted parallel to the surface of the FIREWALL.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/MCB_with_firewall.png" alt="Adding HEATSINK to MCB." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/MCB_with_standoffs.png" alt="MCB with standoffs." style="width: 50%; height: 50%">
   </div>

|


13. Now slide FIREWALL assembly in the BASE. 

.. image:: /_static/magni-mini/assembly/base_with_mcb_and_firewall.png
    :alt: FIREWALL in the base
    :width: 400px
    :align: center
|


14. Take BOLT 2.5x8 ((8.8) Zn) ISO 7380, washer 2.7 and firmly tighten together bottom of FIREWALL and BASE as shown in picture.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/securing_firewall_from_back.png" alt="Bolting FIREWALL to BASE pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/securing_firewall_from_back2.png" alt="Bolting FIREWALL to BASE pic 2." style="width: 50%; height: 50%">
   </div>

|


15. Take BOLT M2.5x8 ((8.8)  Zn) ISO 7380, washer 2.7 and insert the screw and thread it in lightly by allen key.

.. note:: 
  Final tightening will be done after full assembly.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/securing_firewall_from_side1.png" alt="Bolting side of FIREWALL to the BASE pic 1" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/securing_firewall_from_side2.png" alt="Bolting side of FIREWALL to the BASE pic 2" style="width: 50%; height: 50%">
   </div>

|


16. Take left WHEEL MOTOR connector(small) and connect it to the left side of MOTOR BOARD as shown in the picture. Be sure to turn it correctly. 

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/motor_controller_lower_connector.png" alt="Connect Motor Wheel Connector to the MCB middle pic 1" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/motor_controller_lower_connector_connected.png" alt="Connect Motor Wheel Connector to the MCB middle pic 2" style="width: 50%; height: 50%">
   </div>

|


17. Take left WHEEL MOTOR connector(big) and connect it to the MOTOR BOARD as shown in the picture. Be sure to turn it correctly and path the wire as in the picture.

.. image:: /_static/magni-mini/assembly/motor_controller_upper_connector_connected.png
    :alt: Connecting Motor Wheel Connector to the MCB top 
    :width: 400px
    :align: center
|


.. note::
  The left wheel motor connectors attach to the left side of MCB. And the right wheel motor connectors attach to the right side of the MCB. 



18. Ensure that the wiring is routed as shown in the bottom pictures for the right side.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/motor_wheel_to_MCB_routing1.png" alt="Correct Wiring Motor Wheels to MCB upper pic 1" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/motor_wheel_to_MCB_routing2.png" alt="Correct Wiring Motor Wheels to MCB upper pic 2" style="width: 50%; height: 50%">
   </div>

|

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/motor_wheel_to_MCB_routing3.png" alt="Correct Wiring Motor Wheels to MCB lower pic 1" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/motor_wheel_to_MCB_routing4.png" alt="Correct Wiring Motor Wheels to MCB lower pic 2" style="width: 50%; height: 50%">
   </div>

|


19. Take CONNECTION BOARD and gently push both connectors on the picture (red circle) together, until fully engaged.

.. image:: /_static/magni-mini/assembly/PCB_to_MCB.png
    :alt: Connection board to MCB connection.
    :width: 400px
    :align: center
|


20. Use four M2.5x8 (8.8) Zn bolts (ISO 7380) to fasten the CONNECTION BOARD and MOTOR CONTROL BOARD together through the standoffs. 

.. note:: 
  Tighten them carefully.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/PCB_to_MCB_adding_bolts.png" alt="Bolting PCB controller to MCB pic 1" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/PCB_to_MCB_screwing_bolts.png" alt="Bolting PCB controller to MCB pic 2" style="width: 50%; height: 50%">
   </div>

|


21. Take wire harness and connect ground female spade crimp terminal to the ground pin on the MOTOR CONTROL BOARD.



.. FIXME: update the image of the wiring harness to have an arrow pointing at the black connector that we connect to the MCB.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/wire_harness_connector_for_MCB.png" alt="Wires together." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/wire_harness_connected_to_MCB.png" alt="Black connector connected to the spade of the MCB" style="width: 50%; height: 50%">
   </div>

|



22. Take Raspberry Pi 5 and cover the PCU with double-sided thermally conductive tape. Next, remove the protective film from the double sided thermal tape.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/rpi5_with_tape.png" alt="Covering PCU with double sided conductive tape pic 1" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/rpi5_with_tape_pilled1.png" alt="Covering PCU with double sided conductive tape pic 2" style="width: 50%; height: auto;">
   </div>

|


23. Take HEATSINK, 2x PCB PUSH PIN WITH SPRING and RPI5.

.. image:: /_static/magni-mini/assembly/rpi5_and_heatsink.png
    :alt: HEATSINK and RPI5
    :width: 600px
    :align: center
|


24. Position HEATSINK on the RPI5 as shown in the picture and push through two PCB PUSH PINS WITH SPRING as shown in the picture.

.. image:: /_static/magni-mini/assembly/rpi5_with_added_heatsink1.png
    :alt: HEATSINK on RPI5.
    :width: 400px
    :align: center
|


25. Take RPI assembly and connect RPI HAT & GRIPO INTERFACE connector together with CONNECTION BOARD connector as shown in the picture.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/rpi5_connected_to_pcb_top_view.png" alt="Connecting RPI to PCB connector pic 1" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/connecting_rpi5_to_pcb_right.png" alt="Connecting RPI to PCB connector pic 2" style="width: 50%; height: 50%">
   </div>

|


26. Check that the surface of the heatsink is making proper contact with the base sheet metal. Ensure that all parts are correctly aligned, leaving the USB and Ethernet ports fully accessible. Then take M2.5x8 (8.8) Zn bolt (ISO 7380), washer 2.7 and gently tighten one screw.

.. warning:: 
  Do not tighten the screw fully. 

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/rpi5_connected_to_pcb_top_view.png" alt="Screwing the RPI+HEATSINK on the chasis top view." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/rpi5_connected_to_pcb_side_view.png" alt="Screwing the RPI+HEATSINK on the chasis outside view." style="width: 50%; height: 50%">
   </div>

|


27. Inster other bolt M2.5x8 (8.8) Zn (ISO 7380), with washer and gently press on RPI5 so that USB and ETHERNET ports stay centered in sloth like on picture.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/securing_the_rpi5_to_base_left.png" alt="Properly screwing the RPI to the chasis pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/securing_rpi5_to_base_right.png" alt="Properly screwing the RPI to the chasis pic 2." style="width: 50%; height: 50%">
   </div>

|


28. Take two M2.5x8 (8.8) Zn bolt (ISO 7380) with washers 2.7 and carefully fasten together FIREWALL with BASE on the bottom of the robot.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/securing_firewall_bottom_left.png" alt="Screwing the FIREWALL with BASE bottom view pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/securing_firewall_bottom_right.png" alt="Screwing the FIREWALL with BASE bottom view pic 2." style="width: 50%; height: 50%">
   </div>

|


29. Position the ON/OFF rocker switch according to the picture and firmly press it onto the slot. 

.. important:: 
  Pay attention to the position of the dot on the switch. The dot needs to be on the bottom.


.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/switch_adding_to_base.png" alt="Adding the ON/OFF rocker to the BASE pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/switch_added_to_base.png" alt="Adding the ON/OFF rocker to the BASE pic 2." style="width: 50%; height: 50%">
   </div>

|

30. Take 5.5 x 2.1 mm DC POWER CHARGER and push it through opening like on the picture.

.. image:: /_static/magni-mini/assembly/dc_charger_adding_to_base.png
    :alt: Adding DC POWER CHARGER to the BASE 
    :width: 400px
    :align: center
|


31. Align flaat part of the charger with the part of the slot and push it through sheet metal like on picture shown.

.. image:: /_static/magni-mini/assembly/dc_charger_adding_to_base_flat.png
    :alt: Position charger correctly.
    :width: 400px
    :align: center
|


32. Take POWER CHARGER's nut and put it on the connector side.

.. image:: /_static/magni-mini/assembly/dc_charger_adding_nut_to_charger.png
    :alt: Adding the NUT to the power charger.
    :width: 400px
    :align: center
|

33. Ensure that the connector is properly aligned, with the flat side matching the flat surface of the cutout. Then hand-tighten the nut to secure it.

.. image:: /_static/magni-mini/assembly/dc_charger_added.png
    :alt: Aligning the nut to the charger and hand-tighten it
    :width: 400px
    :align: center
|


34. Take FRONT hatch of the Robot and CAMERA 3 WIDE.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/front_hatch_preview.png" alt="Front hatch of the robot" style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/piCamera_wide_preview.png" alt="Camera WIDE." style="width: 50%; height: 50%">
   </div>

|


35. Use 4 BOLTS M2.5x5 ((8.8) Zn) ISO 7380 to tighten CAMERA to FRONT. Tigthen with an allen key using two finger pressure.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/piCamera_adding_to_front_hatch.png" alt="Tightening the CAMERA to the FRONT HATCH pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/piCamera_added_to_front_hatch.png" alt="Tightening the CAMERA to the FRONT HATCH pic 2." style="width: 50%; height: 50%">
   </div>

|

36. Take 3 BOLTS M2x5 ((8.8) Zn) ISO 7380 to tighten the second CAMERA to FRONT. Tighten with an allen key using two finger pressure.

[ TODO: Are we shipping with one or with two cameras. ]

.. TODO: Get the information for this part. 
.. if yes then add images with one more camera.
.. if not leave this part out.

37. Firmly insert the cover caps into the FRONT by applying hand pressure.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/front_hatch_adding_caps.png" alt="Inserting the cover caps into the FRONT HATCH pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/front_hatch_added_caps_preview.png" alt="Inserting the cover caps into the FRONT HATCH pic 2." style="width: 50%; height: 50%">
   </div>

|

38. Just like on the FRONT sheet metal, insert the cover caps into the TOP COVER. Next, place the LIDAR onto the top surface of the TOP COVER and secure it with M2x14 bolts using Allen key. Tighten gently using two-finger pressure.

.. image:: /_static/magni-mini/assembly/top_hatch_with_lidar.png
    :alt: Aligning the nut to the charger and hand-tighten it
    :width: 400px
    :align: center
|

39. Take the BATTERY and position it in the BASE according to the picture. Pay close attention to its orientation.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/batteries_adding_first_one1.png" alt="Adding first battery to the robot upper pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/batteries_adding_first_one2.png" alt="Adding first battery to the robot upper pic 2." style="width: 50%; height: 50%">
   </div>

|

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/batteries_adding_first_one3.png" alt="Adding first battery to the robot lower pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/batteries_adding_first_one4.png" alt="Adding first battery to the robot lower pic 2." style="width: 50%; height: 50%">
   </div>

|


40. Use BATTERY HOLDER to put the second BATTERY in the BASE as shown in the picture.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/batteries_adding_second_one1.png" alt="Adding second battery to the robot with battery holder pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/batteries_adding_second_one2.png" alt="Adding second battery to the robot with battery holder pic 2." style="width: 50%; height: 50%">
   </div>

|


41. Be careful with the wires.

.. image:: /_static/magni-mini/assembly/batteries_minding_the_wires.png
    :alt: Adding second battery, being carefull with the wires.
    :width: 400px
    :align: center
|


42. Take the yellow-green wire and attach it like shown in the picture.

.. note:: 
  Red connector from the wire goes to the RED spade of the first battery. Black connector of the wire goes to the black spade of the second battery.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/batteries_connecting_in_series.png" alt="Connecting the batteries in series pic 1." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/batteries_connected_in_series.png" alt="Connecting the batteries in series pic 2." style="width: 50%; height: 50%">
   </div>

|


43. Grab the wire harness and connect the black female spade terminal to the - battery pin as shown in the picture. Press it in firmly.


.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/wire_harness_connector_for_battery1.png" alt="Wire harness with shown black connector." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/batteries_wires_connected_to_first_battery.png" alt="Connecting the wires to the batteries." style="width: 50%; height: 50%">
   </div>

|

44. Grab the only free black female connector and connect it to the GND CONNECTOR BOARD pin like shown in the picture.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/wire_harness_connector_for_MCB.png" alt="Wire black connector with green circle." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/MCB_wire_harness_connected_to_MCB.png" alt="Wire black connector added to the MCB with green circle." style="width: 50%; height: 50%">
   </div>

|

.. image:: /_static/magni-mini/assembly/MCB_wire_harness_connected_to_MCB_preview.png
    :alt: Close up image of the wire to the MCB with green circle.
    :width: 400px
    :align: center
|


45. Take the short RED wire with spade connector and connect it firmly to the + pin on the battery like shown in the picture (green circle). Also take the charger connector that is on the harness and connect it with the 5.5 x 2.1 mm DC POWER CHARGER connector (yellow circle).

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/wire_harness_connector_for_battery2.png" alt="Wires with green and yellow circle." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/batteries_wires_connected_to_second_battery.png" alt="Wires connected to the battery with yellow and green circle. " style="width: 50%; height: 50%">
   </div>

|

46. Connect the remaining red spade connector to the upper pin of ON/OFF SWITCH.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/wire_harness_connector_for_switch.png" alt="Rest of the wires with green circle." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/switch_spade_connector_for_wire.png" alt="ON/OFF SWITCH with green circle for upper spade connector." style="width: 50%; height: 50%">
   </div>

|


47. Take the other wire harness (with 3 red spade connectors) shown in the picture below. Take the connector from the circuit, which splits into two separate connectors (green circle) and connect it to the bottom pin of the ON/OFF SWITCH.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/wire_harness_connector_for_lower_spade_on_switch.png" alt="Second wire harness with green circle.." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/switch_lower_spade.png" alt="ON/OFF SWITCH with green circle for lower spade connector." style="width: 50%; height: 50%">
   </div>

|


48. Connect the remaining spade connectors and firmly connect one to the 12V PIN ON THE CONNECTOR BOARD and other on 12V pin of the MOTOR CONTROLER BOARD.

.. raw:: html

   <div style="display: flex; gap: 10px;">
     <img src="/_static/magni-mini/assembly/wire_harness_connectors_for_MCB_and_PCB.png" alt="Second wire harness with green and yellow circle." style="width: 50%; height: auto;">
     <img src="/_static/magni-mini/assembly/MCB_wire_harness_connected_to_MCB_preview.png" alt="MCB with green and yellow circle." style="width: 50%; height: 50%">
   </div>

|

49. All the spade connector need to be firmly connected to the pins. Check all pins again! Route the wire harness as shown in the image bellow. 

.. Important:: 
  Check that all pins are firmly connected.

.. note:: 
  UPDATE of the WIRE ROUTING is coming soon.

[TODO: Add image here without the wires being taped/secured to the second battery.]

.. image:: /_static/magni-mini/assembly/final_wiring.png
    :alt: Final wiring. 
    :width: 400px
    :align: center
|


50. Now take TOP COVER assebmly and FRONT assembly and position them like shown in the picture. Take the scre BOLT M2.5x10 ((8.8) Zn) ISO 7380 with washer and two finger force-tighten it while aligning both plates to the BASE. Repeat the same on the opposite side. Once both screws are in place, tighten them fully using an allen key.

.. image:: /_static/magni-mini/assembly/top_hatch_securing_from_outside.png
    :alt: Adding and screwing front cover to the robot.
    :width: 400px
    :align: center
|


51. Take BOLT M2.5x8 ((8.8) Zn) ISO 7380 with 2.7 washer and with allen key and two finger force tighten the bottom part of the FRONT HATCH.

.. image:: /_static/magni-mini/assembly/front_hatch_securing_bottom.png
    :alt: Screwing lower part of front cover to the robot.
    :width: 400px
    :align: center
|


52. Using an M2.5x8 (8.8) Zn Bolt with a 2.7 mm washer, tigthen TOP COVER HATCH with an allen key. Apply only light pressure - approximately  the force of two fingers.

[ FIXME:  This should be secured from the other side. I think.]

.. FIXME: Find this out when in the workshop.

.. TODO: Also, add that this should be optional. As the hatch is heavy enough to keep itself closed. And if you are making a lot of changes
.. it will be hard to screw and unscrew the screws every time.

.. image:: /_static/magni-mini/assembly/top_hatch_securing_top.png
    :alt: Screwing the top cover to the robot.
    :width: 400px
    :align: center
|



[FIX OF THE IMAGE SIZES COMING SOON]

.. TODO: Finish this page.

.. TODO: Fix the sizes of the images so they are visible and not stretched..