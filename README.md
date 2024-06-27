# IITISoC-24-IVR-10-MICROMOUSE

## GOAL
To develop a maze solving micromouse with hardware integration using stimulation

People Involved : 

Mentors:
- [Ampady B R](https://github.com/ampady06)
- [Bhawna Chaudhary](https://github.com/WebWizard104)

Members:
- [Gulshan Choudhary](https://github.com/xingetwjojrtoj)
- [Aarushi Singh](https://github.com/Amberss-Log)
<br>

# MICROMOUSE
 Micromouse is a small autonomous robot capable of navigating a maze to find the shortest path from the starting position to the goal. 
 - Firstly, we had to investigate and assess various maze scanning algorithms. These algorithms help navigate and find way out of the maze.These algorithms can be used to **analyze** the structure of a maze and answer questions about it.There are different algorithms suited for different scenarios.

   ## MAZE SCANNING ALGORITHMS
   ### Wall Following
   The wall following algorithm is based on simple logic of movement through the maze by either following the left hand side or the right hand side of the enclosure wall. In simple words, If the maze is simply connected(a perfect maze), then by keeping one hand in contact with one wall of the maze the solver is guaranteed not to get lost and will reach the goal.
   <br>
   **ADVANTAGES**
   - This algorithm has simple logic and is easy to understand and implement.
   - Requires minimal coding and simple sensor data.
   - Garunteed to solve and find the goal in *Perfect Mazes*.
  <br>
  **DISADVANTAGES**

   - IF the maze is *not simply connected*, like it has loops, dead ends or multiple solutions, the the mouse is likely to get stuck or move endlessly on loops.
   - Does not guarantee *shortest path* from start to finish.
   - It does not create *map* of the maze while it navigates. It simply reacts to immidiate responses from the sensors and navigates.

   This is the video depicting the problem faced while using a wall following algorithm:[right_wall_follower](https://drive.google.com/file/d/1flYjwpWsy6WhyAmOay1xKx8tjAGSHOHe/view?usp=drive_link)
   
   
