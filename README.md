perl-docker-run
===============

docker run via daemontools

  # install docker-run
  cp bin/docker-run /usr/bin/

  # create /serivce/CONTANINER_NAME/{run,log/run}
  docker-run --setup IMAGE CONTAINER_NAME

  # fix /serivce/CONTANINER_NAME/run
  docker-run --docker-path /path/to/docker --docker-run-arg -d IMAGE CONTAINER_NAME

