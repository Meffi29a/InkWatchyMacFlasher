Sometimes things are just difficult. Here, I am trying to fix a problem when flashing a watch with the InkWatchy firmware on a Mac.
You cannot establish a connection from a Docker container to a USB serial programmer by restrictions from Apple. The script solves this problem.

After compiling the InkWatchy firmware in your container, the necessary components are copied from the container using “docker cp” and copied to the watch via USB. 
A rudimentary control via dialog boxes is also built in. In theory, all supported watches should be flashed with this tool. 
So far, it has only been tested on an InkWatchy 2.

The InkWatchy project is very complex and the demands on the implementation of this great firmware are high. I still need to work on my skills before I attempt to commit directly to a third-party repository again.
