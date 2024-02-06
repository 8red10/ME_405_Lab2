## ME 405 Lab 2

### Authors
By: Jack Krammer, Jason Chang

California Polytechnic State University

February 13, 2024


### Description
This project was aimed to increase our familiarity with encoders. In this lab, 
we created an Encoder class that can read from the encoder builtin to the motors 
in the ME 405 lab kit. The Encoder objects uses a timer's count to reflect the 
change in motor position. A position variable is used to store the overall 
position so that underflows and overflows in the timer's count can be appropraitely 
accounted for. 

