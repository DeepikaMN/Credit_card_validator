# Credit_card_validator
 
The Credit Card Validator programme was written in C++. The Luhn method is used to validate the credit card number and determine the credit card is valid or not. A Credit Card Validator application that confirms the authenticity of a user's credit card number was created using the C++ programming language.

It employs the Luhn algorithm to assess whether or not a credit card number is valid. Luhn's technique is a simple checksum formula that may be used to validate a wide range of identifications, including credit card numbers, IMEI numbers, and more, however it is most typically used to validate credit card numbers.

The Luhn check, often known as the Mod 10 check, is discussed below (for reference). (for reference, use the card number 4388576018402626):

Step 1: From right to left, double every other digit. To produce a single-digit number while doubling a digit, put the two digits together (for example, 12:1+2, 18:1+8).

Step 2: Add all of the single-digit numbers from Step 1 in Step 2 now.

4 + 4 + 8 + 2 + 3 + 1 + 7 + 8 = 37

Step 3: Add all of the card number's digits in the odd spots, going from right to left.

6 + 6 + 0 + 8 + 0 + 7 + 8 + 3 = 38

Step 4: Add the outcomes of Steps 2 and 3. 37 + 38 = 75

Step 5: The card number is legitimate if the answer to Step 4 is divisible by 10; else, it is invalid.
