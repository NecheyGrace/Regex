## Regex
Mastercard Credit Card Number Validator
This JavaScript program allows you to validate Mastercard credit card numbers using a regular expression.

### Installation
There's no specific installation required for this program. You can simply copy the provided JavaScript code and integrate it into your project.

### Usage
To use the Mastercard credit card number validator, follow these steps:

Copy the JavaScript function validateMastercardCreditCard() into your project.
Call the function validateMastercardCreditCard(cardNumber) and pass the credit card number as a parameter.
The function returns true if the provided credit card number is valid according to the Mastercard format, otherwise it returns false.
Example:

```
const cardNumber = "5123456789012345";
if (validateMastercardCreditCard(cardNumber)) {
    console.log("Valid Mastercard credit card number");
} else {
    console.log("Invalid Mastercard credit card number");
}
```
Regular Expression Explanation
The regular expression used for validation is ^(5[1-5][0-9]{14})$.

^: Asserts the start of the string.
5[1-5]: Matches the starting digit of a Mastercard number, which must be 5 followed by a digit from 1 to 5.
[0-9]{14}: Matches 14 digits (0-9) after the starting digit.
$: Asserts the end of the string.
This regular expression ensures that the credit card number starts with 5 followed by a digit from 1 to 5, and is then followed by 14 digits in total, making it a 16-digit Mastercard credit card number.

Author: Amara Metu 



