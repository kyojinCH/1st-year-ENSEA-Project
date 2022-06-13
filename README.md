# 1st-year-ENSEA-Project
The first year's project : Structures 3D modelling using a Lidar Robot
The first year project is a simple 5 weeks work in which each group is affilitiated to a professor. The latter proposes projects to students and guides them throught the while making process. In our case, the teacher had chosen a 3D modelling robot using LIDAR and ROS(Robot Operating System). As such, we worked in a corporate structure in which the teacher was the chief superviser and us, the engineers. The whole project management was done with Microsoft Planner.

I have mainly worked on two aspects: the POWER PCB and the driver code for the motors.

## POWER-PCB
The power pcb has seen many developpement throught the 5 weeks, mainly because of some drivers unavailability. This has forced us to adapt the boards each time to the new potential chips. 
I have mostly spent time on reading datasheets and trying to figure out a way to optimally route all components. Personnaly, I have found the task challenging, but I think that it was mainly due to my lack of experience and overusing the autorouting tool, which, to be honest is not as good as it was thaught to be. However, I have learned many tips and tricks that were in no way disclosed during the 3 hours course. Mr BARES's help was priceless during this.
The Software I used was Eagle. Other alternatives are also worthwhile(Fusion360, ProfiCad...) as I've witnessed the teacher and others use them. I will commit the whole project so you can observe how it has evolved(last version is named MK2). Further and more precise technical descriptions will be also be attached.

# DRIVER-CODE
The driver code was the second thing I was tasked with and in which i have worked along with Louis FAY. We struggled at the beggining to generate a pulse width moderated(PWM) signal, since there were no function that allowed us to change it while the robot was working. After a bit of web research, we found a function that could do so. However, we deleted some ligns to optimize its use. Further, we had to make an acquisition, reading then order making bit of code. This part was made in collaboreation with the ROS team, since they were sourcing us with a definite signal. The rest was a question of figuring out the mistakes.

# DISCALMER
I, in no way, pretend being absolutely goood. The sole purpose of this repository is to share what I have done, so as to document it for further use, either by me or others.
