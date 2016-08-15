# sbt-docker-image
Example:

`docker run -p 9005:9005 -v /home/you/your-sbt-app:/app:rw jakubdziworski/sbt-docker-image`

- `-p` - expose port  
- `-v` - mount project directory (must containt build.sbt)
