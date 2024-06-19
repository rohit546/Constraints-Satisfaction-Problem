# Constraints-Satisfaction-Problem

Task 1:
Given a map of Australia, color it using three colors such that no neighboring
territories have the same color.
Variables: WA, NT, Q, NSW, V, SA, T 
Domains: Di = red; green; blue 
Constraints: adjacent regions must have different colors
e.g., WA ≠ NT
(WA; NT) ∈ [(red ; green );
(red ; blue);
(green ; red) ;
(green ; blue ) ... ]

![image](https://github.com/rohit546/Constraints-Satisfaction-Problem/assets/100420859/bddf9b36-56ba-4532-b532-9a4b92e5508d)

Solutions are complete and consistent assignments, e.g WA = red, NT = green, Q = red, NSW =
green, V = red, SA = blue, T = green

![image](https://github.com/rohit546/Constraints-Satisfaction-Problem/assets/100420859/64b3def1-d168-446a-a073-e195cccfa101)

![image](https://github.com/rohit546/Constraints-Satisfaction-Problem/assets/100420859/dc6d481f-a35b-4250-aec1-6768de9829cf)



Task 2:
A variable in a CSP is arc-consistent if every value in its domain satisfies the variable’s binary
constraints. Arc consistency eliminates values from domain of variable that can never be part of a
consistent solution. Arc Consistency algorithm is AC-3.
Pseudocode for Arc consistency:


![image](https://github.com/rohit546/Constraints-Satisfaction-Problem/assets/100420859/4821737a-20ff-48c0-9001-8a74682baf1f)

Your task is to implement the AC-3 and find the following:
• Calculate time complexity.
• Display that Problem is a CSP Arc Consistent or not.
• Also display the solution, if exists.

Task 3:
Forward checking checks constraints between the current variable and all future ones.
Implement Forward Checking on this Color mapping problem.


