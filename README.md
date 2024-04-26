# Test-plan-for-E-commerce
1. Positive Login Page Test Cases
   
Valid username and password combination successfully logs the user in.
Testing with the minimum allowed username and password length.
Testing with a username and password containing alphanumeric characters.
Successful login with the "Remember Me" option selected.
Testing login with a username that contains both uppercase and lowercase characters.
Successful login using a valid email address as the username.
Successful login using a valid phone number as the username.
Successful login with multi-factor authentication (MFA) enabled.
Testing login with a username that includes special characters (e.g., @, #, $).
Successful login using social media accounts (if applicable).
Successful login using biometric authentication (e.g., fingerprint, face recognition).
Testing login after a password reset to ensure the new password works.
Successful login after an account recovery process.
Successful login with localization settings (testing with different languages).
Testing login with different browsers (e.g., Chrome, Firefox, Edge).

2.Negative Login Page Test Cases

​​Entering an incorrect password for a valid username.
Entering an incorrect username for a valid password.
Entering an empty username field.
Entering an empty password field.
Entering a username that does not exist in the system.
Entering a password that does not meet password strength requirements.
Testing login with excessive length usernames and passwords.
Testing login with incorrect case (uppercase/lowercase) in the username.
Testing login with expired or deactivated user accounts.
Testing login with suspended user accounts.
Multiple consecutive failed login attempts triggering an account lockout.
Testing login after the session has expired due to inactivity.
Testing login with incorrect multi-factor authentication (MFA) codes.
Entering invalid characters (e.g., scripts) in the username or password fields.
Testing login with CAPTCHA validation failure.

3.Performance Test Cases For Login Page

Measure and document the average load time for the login page.
Conduct load testing to determine the maximum concurrent user logins the system can handle.
Evaluate the login page's response time during peak usage hours.
Monitor server resource utilization (CPU, memory, bandwidth) during login attempts.
Test the login page's performance on various browsers and devices.
Test the login page's performance with slow internet connections.
Measure the time it takes to recover from a failed login attempt.
Evaluate the login page's performance when the system database is under heavy load.
Test the login page's performance during distributed denial of service (DDoS) attacks.
Evaluate the system's ability to handle high volumes of simultaneous login attempts.
Measure the impact of login rate limiting on performance.
Conduct performance testing with different authentication methods (e.g., password, MFA).
Test the login page's performance with a large number of inactive user accounts.
Evaluate the impact of CAPTCHA validation on login page performance.
Measure the time it takes for a user to receive an authentication code (MFA) if applicable.
