# Docker CheatSheet

* `docker build -t tag_name .`   --- to build docker with given tag name
* `docker exec -it container_tag bash`   --- to bash into the container
* `docker system prune -a`   ---- to delete all dangling images and containers
* `docker rmi $(docker images -a -q)`   --- to delete all images





