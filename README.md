# Cyber-Security-Base-2021-Project-I

## LINK: link to the repository
installation instructions if needed

## FLAW N:
exact source link pinpointing flaw 5...
description of flaw 5...
how to fix it...

## FLAW 1 – A1:2017-Injection: 
```Injection flaws, such as SQL, NoSQL, OS, and LDAP injection, occur when untrusted data is sent to an interpreter as part of a command or query. The attacker’s hostile data can trick the interpreter into executing unintended commands or accessing data without proper authorization.```
user can inject sql code

## FLAW 2 – A2:2017-Broken Authentication: 
```Application functions related to authentication and session management are often implemented incorrectly, allowing attackers to compromise passwords, keys, or session tokens, or to exploit other implementation flaws to assume other users’ identities temporarily or permanently.```
weak admin password, and no password restrictions/poliicy

## FLAW 3 – A5:2017-Broken Access Control: 
```Restrictions on what authenticated users are allowed to do are often not properly enforced. Attackers can exploit these flaws to access unauthorized functionality and/or data, such as access other users’ accounts, view sensitive files, modify other users’ data, change access rights, etc.```
user can access other users uploads

## FLAW 4 – A6:2017-Security Misconfiguration: 
```Security misconfiguration is the most commonly seen issue. This is commonly a result of insecure default configurations, incomplete or ad hoc configurations, open cloud storage, misconfigured HTTP headers, and verbose error messages containing sensitive information. Not only must all operating systems, frameworks, libraries, and applications be securely configured, but they must be patched/upgraded in a timely fashion.```
debug on
token leaked in github repo

## FLAW 5 – A7:2017-Cross-Site Scripting XSS: 
```XSS flaws occur whenever an application includes untrusted data in a new web page without proper validation or escaping, or updates an existing web page with user-supplied data using a browser API that can create HTML or JavaScript. XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.```
user can run own code in comment field
