SET mystNumb TO 3
SENT "please enter guess number" TO DISPLAY
RECEIVE guess FROM KEYBOARD
IF guess > 10 THEN 
SEND "Too high! Your guess must be between 1 and 10" TO DISPLAY
ELSEIF guess = mystNumb THEN
SEND "Well done! You guessed it correctly!" TO DISPLAY
ELSE SEND "Bad Luck! the correct number is" + mystNumb 
ENDIF


