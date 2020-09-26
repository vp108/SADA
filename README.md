# SADA
This project pings all ip addresses in a network and lists the ip addresses that ping successfully.
# Tutorial on how to run the srcipt successfully on MacOSX/Linux machines
To find the range of ip address needed run the command "ifconfig" 
Find the ethernet that is connected to the network modem. In my case this is "en0"
The "inet" will show the ip address that your device is connected to the network.
The "broadcast" shows the end of the ip range.
Edit the script on Line 9 if needed to make sure that it scans the correct the range of ip addresses. 

# ifconfig
![Image 1](/Documentation/ifconfig.png)

# Where to edit the script
![Image 2](/Documentation/t1.png)
