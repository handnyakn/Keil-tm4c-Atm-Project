# Keil-tm4c-Atm-Project

The details of the design are as below. 
-	Input 4-digit card pin password associated with your 7-digit bank account, using a control device (for ex.: keypad)
-	Check entered password, if it is wrong display an error message, give up to 3 tries.
-	If correct open ATM menu on computer PUTTY screen.
-	User has 3 accounts with different 7-digit account ID and password. 
-	ATM menu operations:
1)	User can withdraw/deposit money from their account.
-	ATM should have a finite amount of paper bill with varying value (i.e., x amounts of 100 TL, 20TL, 10TL, 5TL)
-	The withdrawn mount will be subtracted from user’s account. 
-	If user wants a withdrawal that is not possible with the current currency, the maximum possible amount should be given. 
-	Deposits also done with paper bills, specifying bill value and amount (i.e., depositing 10 of 100 TL bills)
2)	Change pin password.
-	Using keypad user will be able to set new password. 
-	If the new password has 2 or more of the same digits, display an error message. Allow user to retry.

3)	Money Transfer.
-	User will be able to transfer x amount money to another one of his accounts.
-	Transfer will take 30 Seconds to complete. User can cancel the transaction within this time. 
-	If a transfer is received in this account, display a message with transfer information.

4)	Exit.
-	User exits the ATM menu. 
-	Finishes the account operations and waits for new access.
