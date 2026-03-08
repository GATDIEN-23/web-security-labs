# SQL Injection Lab

Platform: PortSwigger Web Security Academy

## Vulnerability
SQL Injection in login form.

## Tools Used
Burp Suite

## Steps

1. Intercept login request using Burp Suite.
2. Modify username with payload:

' OR '1'='1

3. Send the request to the server.
4. Login bypass occurs.

## Impact
Authentication bypass.

## Mitigation
Use parameterized queries and input validation.
