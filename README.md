# Circle_Path
This is a matlab function that essentially traces a path using what amounts to a double pendulum (just without gravity). This was created under instruction from JobertoLee.com. The idea is that one arm travels around the origin while another arm spins on the end of the first arm. The length and angular velocity are inputs to the function, which returns a live figure that renders according to the sample rate. 


## Theory
In the words of Joberto Lee, "This is your introduction to dynamics". While this problem seems complex at the surface, it's really just a time-discrete version of vector addition. Imagine the path of each arm as the edge of a circle, where the arms themselves are just vectors pointing to where the edge is at that specific point in time. This is simplified further by the fact that each one arm to stuck to the end of the other, so the end position of the "double pendulum" is simply the two position vectors added together. 

## Documentation 
The line to call the function is as follows: 
> c2PATH(r1,r2,w1,w2)

Which is input directly into the matlab command line. *r1* and *r2* respectively are the lengths of the 
