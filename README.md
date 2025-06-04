# FIVE-BAR-MECHANISM-AND-FOUR-BAR-MECHANISM-KINEMATIC-SYNTHESIS-

# ABSTRACT 
 
 
Kinematic synthesis revolves around crafting mechanisms capable of producing predetermined motion paths or trajectories. In essence, it involves the design and configuration of systems, such as linkages and cams, to achieve desired motion patterns. This process entails determining the appropriate dimensions, shapes, and layouts of components to fulfill specific motion requirements. For instance, in industrial settings, kinematic synthesis might involve devising mechanisms to facilitate tasks like lifting and relocating objects with precision. This facet is integral to fields like robotics, automation, and machinery design. 
 
 
# 1. AIM OF THE PROJECT 
 
 
The aim of the project is to design a five-bar mechanism that follows a given function and then convert the designed five-bar mechanism into a four-bar mechanism to determine the path it follows. Subsequently, an error analysis is conducted, and the results are interpreted. 
 
 
# 2. DESIGN PROCEDURE 
 
 
# 2.1 FIVE BAR MECHANISM 
 
 
The inverse task method was used in the design of a 5-bar mechanism. During the application of the inverse task, link dimensions were initially determined, and necessary calculations were made considering these dimensions. As a result of these calculations, 2 input and 2 output angles were obtained. One of these different solutions was selected, and a 5-bar mechanism was drawn on a graph. By means of a button, it was observed whether the mechanism followed the desired path. As a result of the process, the 5-bar mechanism successfully followed the desired path. 

# 2.1.1 FIVE BAR MECHANISM CALCULATIONS 
 
 ![image](https://github.com/user-attachments/assets/c64b0b60-ef56-44dc-b7c6-95e554c7bbe8)

For the right side of mechanism replace: 
a= a+f b=e c=d 
Qb=Qe 
Qc=Qd  calculations rewrited and Qe Qd degrees found. In this Project 1st solution was used. 

  ![image](https://github.com/user-attachments/assets/3dc51d92-9004-40f7-90dc-c3f0fa54e2c2)

# 2.2 FOUR BAR MECHANISM


During the design stage of the 4-bar mechanism, the relationship between input and output angles was assumed to be the same as that of the 5-bar mechanism.3 precision point was selected ,based on this assumption, the link lengths of the 4-bar mechanism were calculated. 
 
 ![image](https://github.com/user-attachments/assets/4e3bf928-9cea-4d17-9260-a14352c9ab62)

 
Link length of ‘f’ five bar mechanism must be equal to link length of ‘d’ for four bar mechanism. First step d link length was assumed to 1 but five bar mechanism ‘f’ link length is 150 mm so, four bar mechanism link lengths must be scale by multiplying each link to 150. 
 
 ![image](https://github.com/user-attachments/assets/bf14fc1d-64b0-4ace-832a-9a2f75f17490)

 
 
# 2.2.1 FOUR BAR MECHANISM DIRECT TASK

By performing the direct task, the relationship between the input and output angles of the known 4- bar mechanism is obtained. Thus, the design of the 4-bar mechanism is completed. 
 
 ![image](https://github.com/user-attachments/assets/06e76fe4-5805-4683-a20e-a14bbd14f2b5)

 
![image](https://github.com/user-attachments/assets/0a42e866-1a7b-4005-9ce1-f81bb6a2466f)


(Relationship between input and output angle) 

 
 ![image](https://github.com/user-attachments/assets/c92fdc99-c85a-4300-80cb-0871f90cec87)

(Four bar mechanism) 

# 2.3 ERROR CALCULATION 
The polynomial approximation method was chosen for error calculation. 
 

 
 ![image](https://github.com/user-attachments/assets/5c5471e7-55d2-4837-9a0b-7752175e3d13)

 ![image](https://github.com/user-attachments/assets/80fbfca1-7512-481d-bc7f-2a2ff4017896)

 
 ![image](https://github.com/user-attachments/assets/bd8ed97a-3b99-4670-94d3-dcd2fd9b1798)

 
 
 ![image](https://github.com/user-attachments/assets/c3feb603-48c3-4e7d-bfd7-bd0f7f535311)

 
 

 
# 3. 	RESULTS 
 
 
In the project, the path that the mechanism needed to follow was a function in the x and y planes. This means that a 2-degree-of-freedom mechanism can follow this path with zero error. We proved this with the synthesis of the 5-bar mechanism. However, when we converted our 5-bar mechanism to a 4-bar mechanism, the degrees of freedom reduced to 1, causing the mechanism to fail to follow the required path and errors to occur. In the final step of the project, this error was calculated to reach a conclusion. 
