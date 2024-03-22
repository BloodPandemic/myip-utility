# myip-utility
Gets your external IP - written in bash
--
Just put this into  /usr/bin/ and then chmod +x /usr/bin/myip   -> if you need to,

then, when you need to see your external IP address, just run "myip" in your terminal 👍


<br>
<-=-==-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-><br>
very good way but there is another way xD <br>
```
vim ~/.bash_profile
```<br>
```
alias pubip='ip=$(dig +short myip.opendns.com @resolver1.opendns.com); echo $ip'
```<br>
```
source ~/.bash_profile```<br>
<br>
then u can write pubip and get your public ip at your fingertips :)))
