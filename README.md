# RBV2019
versão 1.1
Distance Sensors
Bumper Sensors
<h3>While navigating by following the right wall, if a collision is detected by one of the bumpers, the robot does a preprogramed maneuver to recover from that collision. The maneuvers can be a simple backward movement as illustrat</h3>

<h4>While navigating by following the right wall, the robot counts and displays in the LCD the white lines detected. In order to avoid multiple detections and counts of the same white line, you should implement some algorithm like the following.</h4>


<h5>. . .<br>
value = read the value of the line sensor;<br>
  if(value < threshold) { //Is a white line. <br>
  move forward during a very brief moment just to pass by the white line;<br>
    totalLines = totalLines + 1;<br>
    display totalLines; <br>
  }<br>
. . .<br>
 </h5>
