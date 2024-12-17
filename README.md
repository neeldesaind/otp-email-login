# Simple OTP Email Verification (HTML, CSS, JS, Node.js)
This project demonstrates an OTP (One-Time Password) email verification system where users can enter their email, receive an OTP to their inbox, and verify it for further actions.

## Features
- **Email Input:** Users can input their email to receive the OTP.
- **OTP Generation:** A 6-digit OTP is sent to the provided email address.
- **OTP Verification:** Users can enter the OTP to verify and proceed with the next steps.
- **Error Handling:** Proper error handling for failed OTP requests or incorrect OTP input.

## Technology Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend (Server):** Node.js (for OTP email sending and verification)
- **Third-party Libraries:** None used in this project, but you can extend it with additional features such as email validation services.

### Demo
https://github.com/user-attachments/assets/c461a215-a6b1-4a70-9082-e78e69308fc3

## How to Run

1. Clone this repository to your local machine:
   git clone https://github.com/neeldesaind/otp-email-verification.git
   cd otp-email-verification
2. Make sure you have Node.js installed on your machine.
3. Install the necessary dependencies for the backend (server-side code):
     npm install
4. Start the Node.js server:
      node server.js

### How It Works

1. The user enters their email address and clicks Send OTP.
2. The application sends the email request to the server, which generates a 6-digit OTP and sends it to the user's email.
3. Once the OTP is sent, the email input form is hidden, and the OTP input boxes are displayed for the user to enter the OTP.
4. The user enters the OTP, and the system verifies it against the one sent to the email.
5. If the OTP is correct, the user is redirected to a success page or another step in the process.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/neeldesaind/otp-email-login/blob/main/LICENSE) file for details.

### Contact
Feel free to reach out if you have any questions or suggestions:
Email: neel.desai1653@gmail.com
GitHub: https://www.github.com/neeldesaind
