SET awnser TO '3'
SEND 'Guess the number' TO DISPLAY
RECIEVE number FROM KEYBOARD 
IF number > 10:
 SEND 'it should be less than 10 stupid'
ELIF:number = awnser:
 SEND 'congrats you are correct'
ELSE:
 SEND 'Dumb af' TO DISPLAY
END IF
