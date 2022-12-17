# linux-wargames
Dockerfiles for finding flags in containers\
This is official repository for building docker images from dockerfiles and use them for conducting quizzes by dropping volunteers into containers \
The password for the next level container can only be found in previous level container\
Currently, each directory contains dockerfile for building image that can provide password for the next level which can be used to log in into the next level container
Example,\
if you are in level n, once you find the password, you can use it to log in to the next level container \
Suppose, for the first level, there will be password already provided, and for 2nd level, you have to find it from that logged in container

Lastly there is a dockerfile at root which will combine all these levels into one dockerfile which can be used for all levels i.e the levels will be nothing but \
non-previlleged user accounts in that container 

Contributions are welcome!
