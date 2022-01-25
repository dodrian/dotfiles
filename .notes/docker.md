# Docker Commands

`docker build .`
`docker images` show local images
`docker run <image-name> <command>` pull image and run command
	`-ti` hook to local stdio
	`-v /path/to/local/folder:path/to/container/folder` mount volume
	`--name <name>` name container
	`--rm` remove container after excecution
`docker exec <container-name> <command>` execute command in running container
	`-ti` hook to local stdio
	`--user <user>` as user
`docker attach <container-name>` attach to running container
`docker ps` show running contaniers
    `-a` all/include stopped
 	`-l` just last container
`docker rm <container>` delete container
`docker commit <container> <tag-name>` turn container into new image
`docker tag <image-id> <name>` tag image

`ctl-p` `ctl-q` - detach running container

