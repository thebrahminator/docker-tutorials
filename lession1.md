# Docker Basics

## Commands
 * Search: `docker search <name>` ->  This command is used to search for existing Docker images. Eg. `docker search redis`. This searches the existing Container registry, and lists the containers for `redis`. Look for contatiners, where the Official Tag is set to OK, this is probably the best container. 

 * Run: Once you search for an image, find it, you need to run it in your system. For running a Docker image, use command `docker run <image-name>`. If you want to run the process in background, specify the same with `-d` flag. 
