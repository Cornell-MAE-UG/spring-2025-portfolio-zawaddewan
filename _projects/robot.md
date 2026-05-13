---
layout: project
title: ASML Robot Competition
description: MAE 3780 Final Project
technologies: [Arduino]
image: /assets/images/robot.png
---

For MAE 3780, all students must participate in the robot competition as part of our class, hosted by ASML. The robot competition involves driving across a field and gathering cubes, attempting to gather more cubes than the other opposing robot before time is called. The robots were made to fit in an 8"x8" box at the start, with a budget of $40.

Our robot performed decently, going 5-2 in our round robin group. It used two motors to drive motion, a color sensor to detect changes in position (i.e. the border, entering different regions of the competition field), and an ultrasonic sensor for detecting other robots. These components are controlled by a single Arduino Uno, mounted in the center of the robot. If we detect another robot during competition, our robot "punches" the opposition by turning and hitting them with its acrylic arm.

During the competition, our robot follows this flowchart for operation:

![Flowchart]({{ "/assets/images/flwochart.png" | relative_url }}){: .inline-image-r style="width: 200px"}



