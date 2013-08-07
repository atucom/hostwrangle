HostWrangle
===========

Ruby script to convert nmap xml into one-line-per-port csv output

Output:
#{host.ip},#{port.number},#{port.protocol},#{port.state},#{port.service},#{port.service.product},#{port.service.version}

Example:
./atu-hostwrangle.rb nmap.xml
192.168.1.1,23,tcp,open,telnet,NASLite-SMB/Sveasoft Alchemy firmware telnetd,
192.168.1.1,80,tcp,open,http,Linksys wireless-G WAP http config,
192.168.1.103,80,tcp,open,http,,
192.168.1.103,135,tcp,open,msrpc,Microsoft Windows RPC,
192.168.1.103,139,tcp,open,netbios-ssn,,
192.168.1.103,443,tcp,open,skype2,Skype,
192.168.1.103,445,tcp,open,netbios-ssn,,
192.168.1.103,554,tcp,open,rtsp,,
192.168.1.103,2869,tcp,open,http,Microsoft HTTPAPI httpd,2.0
192.168.1.103,5357,tcp,open,http,Microsoft HTTPAPI httpd,2.0
192.168.1.103,10243,tcp,open,http,Microsoft HTTPAPI httpd,2.0
192.168.1.104,6510,tcp,filtered,mcer-port,,
192.168.1.104,9968,tcp,open,http,doubleTwist httpd,
192.168.1.105,3007,tcp,filtered,lotusmtap,,
192.168.1.106,22,tcp,open,ssh,OpenSSH,5.2
192.168.1.106,3689,tcp,open,daap,Apple iTunes DAAP,10.6d22
192.168.1.106,5900,tcp,open,vnc,VNC,
192.168.1.106,7000,tcp,open,http,Apple AirPlay httpd,
192.168.1.106,7100,tcp,open,http,Apple AirPlay httpd,