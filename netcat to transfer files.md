transmitter
└─$ nc "ip-address" "port-number" -vv -q 0 < "file-name"

└─$ nc -v -w 2 "ip-address" "port-number" < "file-name"

to send folder
tar -cf - . | nc -v "ip-address" "port-number" = goto folder & use this command

tar -cf - "folder-name" | nc -v "ip-address" "port-number"


receiver
└─$ nc -lvnp "port-number" -vv > "file-name"

└─$ nc -v -w 30 -p "port-number" -l > "file-name"

to receive folder
└─$ nc -lvnp 1234 | tar xfv -
