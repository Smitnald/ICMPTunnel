# ICMPTunnel
Create a reverse icmp tunnel to forward tcp traffic,this maybe useful in some lan env
Usage:

Server :
echo 1> /proc/sys/net/ipv4/icmp_echo_ignore_all
python IcmpTunnel_S.py



Client :
python IcmpTunnel_C.py {serverIP} {needConnectIP} {needConnectPort}
