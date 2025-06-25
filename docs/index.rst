.. RTD Try2 documentation master file, created by
   sphinx-quickstart on Fri Jun  6 13:19:06 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Ubiquity Robotics Gen 6 Documentation
=========================================

Welcome to the documentation for the Ubiquity Robotics Magni Gen 6. 
This guide provides information for interacting with our robots, from beginner tutorials to advanced projects.
Learn how to assemble, connect, drive, and create custom projects with our robots. 
Each robot model has a dedicated page with a getting started guide. 
Explore hardware details, custom software, and usage instructions.

Sections
########

- **Getting Started:** This section shows what you need to set up your robot and PC. Then follow step-by-step guides from unboxing to driving your Magni Robots.
- **Magni 6 Models:** This section introduces the Magni Gen 6 robot models. It includes overview, common use cases, build specifications, custom software images, included sensors, and optional add-ons.
- **Software:** This section details the robot's software, including custom images, their specifications, and tutorials for using our custom software.
- **Hardware:** This section describes the robot's hardware components, including sensors, batteries and modification guidelines, so people can modify the harware without interrupting with the base systems of the robot.. 
- **Beginner Projects Magni Mini:** This section offers beginner-friendly projects to help useers become familiar with the robots. Completing these projects helps users confidently interact with and use the robots.

.. toctree::
   :maxdepth: 2
   :caption: Getting Started

   getting_started/requirements
   getting_started/workstation
   getting_started/models/main_getting_started_models
   
.. toctree::
   :maxdepth: 2
   :caption: Magni 6 Models
   
   magni6_models/models/main_magni_models
   magni6_models/full_assembly/main_assembly_models

.. toctree:: 
   :maxdepth: 2
   :caption: Software

   software/images
   software/openrmf
   software/ezmap

.. toctree::
   :maxdepth: 2
   :caption: Hardware

   hardware/beginner/main_beginner_hardware
   hardware/advanced/main_advanced_hardware

.. TODO: FIX THE ISSUE WHERE THE BATTERIES DOCS DISSAPEAR WHEN YOU ENTER HARDWARE PART 

.. toctree::
   :maxdepth: 2
   :caption: Projects for Magni Robots
   
   projects/mini/main_projects_mini
   projects/medi/main_projects_medi
  
.. toctree::
   :maxdepth: 1
   :caption: Examples of .MDs

   example


