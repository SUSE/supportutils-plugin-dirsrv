## Supportutils Plugin Dirsrv

This is a support utils plugin to gather information on 389-ds instances to assist with
issue diagnosis. This tools attempts to redact some private information to prevent
data leaks.

To test:

    LOG=/tmp python3 ./dirsrv

This will output logs to /tmp of the collected data. For example:

    dirsrv.txt
    dirsrv-slapd-localhost.txt
    dirsrv-slapd-localhost-access-log.txt
    dirsrv-slapd-localhost-error-log.txt


