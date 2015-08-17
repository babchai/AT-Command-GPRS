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

https://vsblogs.wordpress.com/2013/11/28/tcp-connection-over-gprs-using-sim900-and-at-commands/
http://electronics.stackexchange.com/questions/122839/sim900-at-commands-cipsend-pop3read


OK
AT+CGATT=1
OK

AT+CGATT=1
OK

AT+CSTT="diginet"
OK

AT+CIICR
OK

AT+CIFSR
100.76.135.167
AT+CIPSTART="TCP","74.124.194.252","80"
OK

CONNECT OK
AT+CIPSEND
GET http://www.m2msupport.net/m2msupport/http_get_test.php HTTP/1.0
SEND OK

http://m2msupport.net/m2msupport/atcipserver-configure-module-as-server/
