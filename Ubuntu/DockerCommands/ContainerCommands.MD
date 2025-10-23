| Action                                 | Command                                 | Description                        |
| -------------------------------------- | --------------------------------------- | ---------------------------------- |
| **List running containers**            | `docker ps`                             | Shows containers currently running |
| **List all containers (even stopped)** | `docker ps -a`                          | Shows all containers               |
| **Start a stopped container**          | `docker start <container_name>`         | Starts an existing container       |
| **Stop a running container**           | `docker stop <container_name>`          | Stops a container gracefully       |
| **Restart a container**                | `docker restart <container_name>`       | Restarts a container               |
| **Remove container**                   | `docker rm <container_name>`            | Deletes a stopped container        |
| **Remove all containers**              | `docker rm $(docker ps -aq)`            | Deletes all containers             |
| **View container logs**                | `docker logs <container_name>`          | Shows logs of a container          |
| **Attach to container shell**          | `docker exec -it <container_name> bash` | Open an interactive shell          |
| **Stop all containers**                | `docker stop $(docker ps -q)`           | Stops every running container      |
