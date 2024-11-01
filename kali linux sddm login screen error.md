# kali linux sddm login screen error

# "make sure when you get this error your linux was alredy connected to internet" 

if you got this error do the following steps to resolve it.

1. press ctrl + alt + f1 and then ctrl + alt + f6 to switch to terminal

2. now termial is showing with the message

"Kali GNU/Linux Rolling Kali ttyl

kali login: "

now type your linux username hit enter and then it will ask for password type your username's password and then in blue color text appears

┌──(virus47㉿kali)-[~]
└─$ 
(your username appears in virus47 place)

3. type this commands:

"sudo apt install sddm-theme-breeze -y"

now it will tell you restart services, only select the services that you want to restart but mostly select all services that are related to "sddm or kde".

4. if your original linux login screen appears input your password get logged in then opened the terminal type this commands:

"sudo apt install --reinstall plasma-desktop"

and again restart services but mostly related to sddm and then you are done.

5. For a sure case perform a "sudo apt update -y"

