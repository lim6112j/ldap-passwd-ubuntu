# check the guide [here](http://ldapjs.org/guide.html)
* should run on Linux, mac won't work for command useradd.
``` sh
ldapsearch -H ldap://localhost:1389 -x -D cn=root -w secret -LLL -b "o=myhost" "objectclass=*" cn gid
```
