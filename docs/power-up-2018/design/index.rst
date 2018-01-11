Design Documentation
********************

This documentation covers the design aspect of the 2018 FIRST game, Power Up.
The documentation will show the thought processes that the team had over time 
to develop the final robot design, and any necessary documents.

Early Designs
-------------

Early on, following rules overview, the team sat down to begin preliminary 
design discussions. This included asking a few major questions.

1) What actions do we want the robot to be able to perform?
2) How do these actions play into the game to cause events?
3) How do these events give us points?
4) What events will maximize our points?

For Question 1, the team decided on a few major actions they want the robot to excel at performing.

* Moving in 2 Dimensions: This means that the left and right side of the robot will be driven by 3 wheels connected on a track, allowing ample movement.
* Climbing: The Robot should be able to lift itself (and potentially other robots) via a climbing mechanism.
* Claw: The Robot will have an arm that allows it to pick up, move, and release objects.
* Arm/Elevator: The Robot will have some mechanism to move the arm from floor position to any height accurately.

For Question 2, the team decided how these actions would influence and cause events in the game.

* Being able to move is critical to the game. Tele-operated driving is a given, but a strong autonomous is a must for the high-strategy game.
* Climbing awards the most points and gives the potential of a Rank Point in seeding rounds, so it is essential that the Robot's climbing mechanism can accurately and precisely climb the scale, either via the bar or another method. We also considered allowing other robots to climb via our robot in some way.
* Moving Power Cubes around the field, placing them on the switch/scale, and inserting them into the vault is critical. The robot's Arm/Elevator and Claw must be able to perform all of these actions quickly and accurately, no matter the orientation of the drop-zone or cube when being picked up.

For Question 3 & 4, the game relies heavily on strategy. What we do during the match will depend on the teammates that are in our alliance for each match, but it was decided that the strongest strategy was to control the scale in autonomous and place as many Power Cubes on the Switch and Scale as possible throughout the match, and then being able to climb. 

Refined Designs
---------------

The refined design came down to a few major subsystems.

Claw
++++

The **Claw** is a two-pronged wrist assembly that can open and close, allowing it to pick up and move the Power Cubes around the arena. There is potential to add some type of driven wheel or belt-drive to the claw's grips to allow for sucking in and pushing out, aside from just dropping. The Claw's prongs will be covered in some friction-y material, such as rubber, to ensure to good grip with the box. It will also contain *bumps* that will allow it to better hold on to the Power Cube. 

The claw will also be able to rotate around the Z axis (if looking at it from the side) meaning that the robot can lift and place a Power Cube within it's confides to ensure safety and security.

Arm / Elevator
++++++++++++++

To get the Power Cubes up to the height of the Scale at its worst position, we had to design a lift mechanism for the Claw. 

Initially, we designed an arm with a joint that would sit at the back of the robot that would rotate open using cylindars. The initital CAD drawing of this design is below. This design could have the wrist and the Claw at the end of the Arm, but to fit within the 16" dimensions outside of the frame parameter when being rotated/raised up, the Arm would have to sit inside of the Robot.

.. image:: /_static/arm-v1.png

The second design that was put forth and is currently being developed was the use of an elevator-like system that could raise and lower the Claw, as well as contain the mechanism(s) required to climb.
