# Tumbler Dynamics Simulation
#### Jingyan Ling

![demogif](https://github.com/monkalynn813/dynamics_model_tumbler/blob/master/img/314demo.gif)
<p>The project is a dynamics simulation of block in a tumbler by applying Euler Lagrange Equation through Mathematica. The motion has been divided to 7  parts. This project shows techniques expansion from theory and ability of building physical model.   </p>
                  <p> <b>•  Trajectory 1 : </b>The block starts from blade 2 (right side blade) and sliding down form the blade. The blade was treated as varying constraint on two corner points of triangular block. The block will fall after sliding from the blade. 
                    The constraint was off when the mid bottom point of triangle pass beyond the blade inner tip by using “Whenevet” and setting left hand side of E-L to zeros.<br><b>• Trajectory 2 :</b> The block fall from the blade and hit the tumbler inner edge with a plastic impact. From animation A2, it is more obvious to see the plastic impact make the block move along the tumbler edge for a few seconds.<br>
                  <b>• Trajectory 2.5 : </b>Another corner of block impact with the tumbler. It is hard to tell from the animation that two corners of the block hit the tumbler separately. The time of those two impacts are very close (2.19386s and 2.19459s)
                  <br><b>• Trajectory 3 : </b>Take the velocity update computed from Trajectory 2.5 and set the inner edge of tumbler as a constraint on two corners of the block. The animation shows the block sliding at the bottom of the tumbler with initial velocity given from Trajectory 2.5<br>
                  <b>• Trajectory 4: </b>The block is sliding on the bottom of tumbler until it hit by the coming blade ( blade 3 in this case) as another plastic impact. The impact law was used to compute updated velocity.<br>
                  <b>• Trajectory 6: </b>Simulate the animation until the block reach the same position as the beginning of animation.</p>
