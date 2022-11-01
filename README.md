# PHP Source Code Analysis

Vulnerabilities can be detected by searching the following keywords in vulnerable web applications written in PHP:

## File Upload:
move_uploaded_file

## XML Injection:
xml_parse

## XPATH Injection:
->xpath(

## Command Injection:
exec
shell_exec

## XSS
innerHTML

echo

var_dump


## File Inclusion
include

## Code Injection
eval

## Open Redirect
header

## Path Manipulation
readfile

## SQL Injection(Because parametric query is not used)
mysql_query

->exec

->query

## Deserilization
unserialize

## LDAP Injection
ldap_connect

## SSII
!--#echo var

## IDOR
$_REQUEST

## Frame Injection
iframe

## SSTI
Twig_Autoloader

Twig_Loader_String

Twig_Environment

## Clickjacking
iframe

Not using X-Frame-Options or Content-Security-Policy
