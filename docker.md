First write Dockerfile (Build the application, and Run the application).

After build the image using this Dockerfile -  docker build -t atul-springboot-app .

lastly we can run this image on our docker container - docker run -p 8080:8080 atul-springboot-app

You can view the runnning container by - docker ps 

if you want to access running container shell - docker exec -it <container_id> /bin/sh


to stop container -  docker stop <container_id>  and to remove - docker rm <container_id>


-p 8080(our port):8080(docker port)

docker exec -it 739d1e6d74a9 /bin/sh

cd 

Inside  - app  bin  dev  etc  home  lib  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var

inside bin - 

arch      busybox  chmod  dd             dumpkmap  fatattr  getopt  hostname  kbd_mode  linux64  lsattr    mknod   mountpoint  nice   pipe_progress  reformime  run-parts  sh     su     true    watch
ash       cat      chown  df             echo      fdflush  grep    ionice    kill      ln       lzop      mktemp  mpstat      pidof  printenv       rev        sed        sleep  sync   umount  zcat
base64    chattr   cp     dmesg          egrep     fgrep    gunzip  iostat    link      login    makemime  more    mv          ping   ps             rm         setpriv    stat   tar    uname
bbconfig  chgrp    date   dnsdomainname  false     fsync    gzip    ipcalc    linux32   ls       mkdir     mount   netstat     ping6  pwd            rmdir      setserial  stty   touch  usleep

cd to go back to shell