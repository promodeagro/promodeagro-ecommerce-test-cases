Use Case: Login with Email/Phone and OTP Verification
Primary Actor: User
Goal: To successfully log in to the application using their email or phone number and verify their identity through OTP verification.
Preconditions:
- The user has a valid email address or phone number.
- The user has already registered with the application.
- The user has access to their email or phone to receive the OTP.
Triggers:
- The user clicks on the Login button in the top right corner of the application.
Description:
1. The user clicks on the Login button, and a pop-up window appears with two options: Login or Sign Up.
2. The user selects Login.
3. The user is prompted to enter their email address or phone number.
4. The user enters their email address or phone number and clicks on the Continue button.
5. An OTP (One-Time Password) is sent to the user's entered mobile number.
6. The user receives the OTP and enters it in the application.
7. The application verifies the OTP and logs the user in successfully.
Postconditions:
- The user is logged in to the application.
- The user's identity is verified through OTP verification.
Assumptions and Dependencies:
- The user has a stable internet connection.
- The user's email address or phone number is valid and correctly entered.
- The OTP is delivered to the user's mobile number within a reasonable time frame.
Extensions:
- If the user enters an incorrect email address or phone number, an error message is displayed, and the user is prompted to retry.
- If the user fails to receive the OTP, an option to resend the OTP is provided.
- If the user enters an incorrect OTP, an error message is displayed, and the user is prompted to retry.
