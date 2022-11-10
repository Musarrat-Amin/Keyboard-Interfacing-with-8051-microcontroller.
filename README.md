# Keyboard-Interfacing-with-8051-microcontroller.
Through the code I have saved Username as "BAD" and Password as "111022".In the Proteus, the LCD will show "ACCESS GRANTED" if the provided with same username and password. And if the provided password and username is not matched then it shows "ACCESS DENIED"
You can change the Username and PAssword to anything you want as long as they are 3 digits and 6 digits respectively.
%Change here
USERNAME: DB 'B','A','D'
PASSWORD: DB '1','1','1','0','2','2'
MSG_1: DB "USERNAME:",0
MSG_2: DB "ACCESS DENIED..",0
MSG_3: DB "ACCESS GRANTED!!",0
MSG_4: DB "PASSWORD:",0

ORG 300H
KCODE2: DB '1','2','3','A'
KCODE1: DB '4','5','6','B'
KCODE0: DB '7','8','9','C'
KCODE3: DB '*','0','#','D'
