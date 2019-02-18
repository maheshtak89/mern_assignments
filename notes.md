// #1 build the image
// syntax:  docker build -t <images-name> 
docker build -t nodeharbinger -t

// #2 run  the image
docker run --p 8081:8081 <imahes-name>
docker run --p 8081:8081 nodeharbinger

        *************************************
        *                                   *
        *    // to remove images (none)     *
        *    docker rmi --p                 *
        *                                   *
        *    //to stop container            *
        *                                   *
        *************************************
// #3 to run application from inside containerized image
docker exec -it <CONTAINER_ID> /bin/bash

