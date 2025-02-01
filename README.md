<h2>Description</h2>
This project focuses on optimizing university course scheduling to maximize instructor satisfaction while adhering to constraints such as room availability, time slot conflicts, and workload balance. Using linear programming, we developed a model that assigns courses and time slots to instructors based on their preferences while ensuring efficient resource allocation.
<br />

<h2>Approach</h2>
We formulated the problem as a linear programming model, using:

- Binary decision variables to represent course and time slot assignments.
- Preference weighting to prioritize instructor choices.
- Hard constraints to enforce scheduling rules, including:
  - Each course must be assigned to one instructor.
  - No instructor can teach more than two courses.
  - No instructor can have overlapping time slots.
  - The number of classrooms limits the number of simultaneous courses.

<h2>Data & Implementation</h2>

- Dataset: We used real course and instructor preference data from Fall CO courses.
- Optimization Method: The model uses a weighted sum approach to balance instructor satisfaction and scheduling feasibility.
- Solution Analysis: The model generates an optimal schedule, identifies unused time slots, and highlights possible areas for further optimization.

<h2>Team Member</h2>
Evelyn Geng, Linghan Zhang, Linsi Zhong, Shengdong Zhang & Tony Ye
