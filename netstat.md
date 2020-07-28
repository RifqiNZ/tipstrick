netstat -ntlp

#remotevnc
rasp- autossh -R 39997:localhost:5901 rifqi@182.253.226.92 -p 2201
mac- ssh -L 9021:localhost:39997 rifqi@182.253.226.92 -p 2201

