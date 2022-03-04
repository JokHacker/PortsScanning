# PortsScanning
Script For Scanning Ports in your Server Or Device ( HTTP , DNS , HTTPS , SMTP , MYSQL , MongoDB ...ALLPorts )
To make file Shell Script Executable use : 
 Chmod command Or Chown Command : 
    Chmod +x File_Name.sh 
To Execute File script use : 
    ./File_Name [Arguments] : 
    ./File_Name (1)IP_Address in Domaine to start (2)Last Device for Example 255 (3) Port like HTTP or Any Port
    EXEMPLE : 
    ./PortsScanning 196.168.1.1 255 8080 
    This Example To Scanning HTTP Port and Know whos Devices use this Port
    The Most Ports Useful : 
    8080 -> HTTP 
    53  -> DNS
    443 -> HTTPS
    465 -> SMTP
    520 -> RIP
    554 -> RTSP
