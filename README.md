# Ldap-testing

#### Keycloak - Config

```
LDAP - Enabled

Active Directory
Connection URL  - ldap://ldap.forumsys.com:389
Enable StartTLS  - Off
Use Truststore SPI  - Never
Connection pooling - On
Connection timeout - 10000
Bind type - simple
Bind DN - cn=read-only-admin,dc=example,dc=com
Bind credentials - password

LDAP searching and updating
Edit mode - WRITABLE
Users DN - dc=example,dc=com
Username LDAP attribute - cn
RDN LDAP attribute - cn
UUID LDAP attribute - objectClass
User object classes - inetOrgPerson

User LDAP filter 
Search scope  - Subtree
Read timeout - 5000
Pagination - Off

Synchronization settings
Import users - On
Sync Registrations - On
Batch size - 1000
Periodic full sync - On
Full sync period - 120
Periodic changed users sync - Off

Kerberos integration
Allow Kerberos authentication - Off
Use Kerberos for password authentication - Off

Cache settings
Cache policy - NO_CACHE

Advanced settings
Enable the LDAPv3 password modify extended operation - Off
Validate password policy - Off
Trust Email - Off
```

#### Browser (app)
```

Link
https://www.ldapclient.com/downloads78/LdapBrowser-7.8.x-win-x64-Setup.exe

Hostname - ldap.forumsys.com
Port - 389
Protocol - ldapv3
UserDN - cn=read-only-admin,dc=example,dc=com
Password - password

```
