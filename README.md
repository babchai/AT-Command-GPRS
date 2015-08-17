# AT-Command-GPRS
AT+CGATT?
+CGATT: 1

OK
AT+CSTT="diginet",","
OK
AT+CIICR
OK
AT+CIFSR
ERROR
AT+CIFSR
100.89.147.239

AT+CIPSTART="TCP","www.google.com","80"
OK

CONNECT OK
AT+CIPSEND
Input: hellop
OK

AT+CIPSEND

Input: #024
SEND OK

CLOSED

#https://vsblogs.wordpress.com/2013/11/28/tcp-connection-over-gprs-using-sim900-and-at-commands/
#http://electronics.stackexchange.com/questions/122839/sim900-at-commands-cipsend-pop3read
