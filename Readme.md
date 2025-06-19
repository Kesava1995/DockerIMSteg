**Useful Commands**

docker pull phani1123/stegano-gui:latest

docker run -it --rm -e DISPLAY=host.docker.internal:0.0 -v "C:\Users\ **Your-Username** ":/home/user phani1123/stegano-gui

docker rmi <image-id>


**THIS WORKS ONLY IN WINDOWS based System. X Server should also be installed in the system**

**Below commands should be run in CMD-Administrator mode**
curl -L -o vcxsrv-setup.exe https://sourceforge.net/projects/vcxsrv/files/latest/download

vcxsrv-setup.exe /VERYSILENT /NORESTART /SUPPRESSMSGBOXES

start "" "C:\Program Files\VcXsrv\vcxsrv.exe" :0 -multiwindow -clipboard -wgl -ac
