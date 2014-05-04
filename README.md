LDAP-conf
=========

LDAP Configuration and extensions

Application
-----------
To apply this to an existing LDAP server, simply:

```
ldapmodify -D "cn=directory manager" -w <password> -x -v -f sshChicagoPersonClass.ldif
```

I have no idea why you'd _want_ to apply this to your server if you're not us, but if you want to, uh, more power to you?
