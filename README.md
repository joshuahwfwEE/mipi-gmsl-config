# mipi-gmsl-config
record for adjusting max96717f and max96724f  
tunneling mode:  
architecture:  

Video Pipe Selection Block Diagram:  
0x00b: gmsl2 mode lock in link c  
mapping video pipe 2 amd pipe 3
![alt text](https://github.com/joshuahwfwEE/mipi-gmsl-config/blob/main/gmsl_link2video_pipe_select.png?raw=true)  
phy selection for mapping:  
we are using pipe2 map to controller2, pipe3 map to controller3  
![alt text](https://github.com/joshuahwfwEE/mipi-gmsl-config/blob/main/4x2_mode_phy_sel.png?raw=true)  

video pipe to mipi phy selection:  
