# handbrake
docker run -t -i -p 6080:6080 -v /directory_on_host:/mountpoint_on_guest smalltree/handbrake:latest

docker run -t -i -p 6080:6080 -v /directory_on_host:/mountpoint_on_guest -v /etc/localtime:/etc/localtime:ro smalltree/handbrake:latest

ghb
