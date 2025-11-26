# pay-ui
Flutter 3 UI

with login, signup, and main balance screen. 


---

Screens to Implement

1. Login Screen

Username/email + password fields

“Login” button

Navigation to Signup screen

Use OTP Bank green for buttons/primary UI elements:

HEX: #0F9D58



2. Signup Screen

Username, email, password, name fields

“Signup” button

On success, navigate to main balance screen

Use OTP Bank green for buttons/primary UI elements



3. Main Balance Screen

Show user balance in a card (like Revolut)

List of recent transactions (title, amount, date, icon)

Pull-to-refresh animation

Smooth scrolling / animations encouraged

Optional: dark mode





---

API Endpoints

POST /auth/login
POST /auth/signup
GET  /user/balance
GET  /user/transactions


Example Login Request:

{
  "username": "testuser",
  "password": "testpass123"
}

Example Login Response:

{
  "token": "dummy_jwt_token_for_testuser",
  "user": {
    "id": 1,
    "username": "testuser",
    "email": "testuser@example.com",
    "name": "Test User"
  }
}


---

Technical Requirements

Flutter 3+

Use state management (Provider / Riverpod / Bloc / etc.)

Separate models/services from UI

Handle loading and error states

Store token locally for authenticated calls

Use OTP Bank green (#0F9D58) for buttons, highlights, or cards
---

If you want, I can also write a ready-to-paste snippet for README with a color swatch and dummy API JSON so you can drop it directly into your GitHub repo for him.

Do you want me to do that?
