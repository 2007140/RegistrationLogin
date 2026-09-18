# Registration Login
JAVA PROGRAMMING POE PART1
PROG5121 Programming 1A Portfolio of Evidence Part 1
Vutlhari Shingange st10518431


## About
This project is a **Java console application** that simulates a basic registration and login system.  
It demonstrates input validation, credential storage, and user authentication using simple rules.  
The program is designed for educational purposes, showcasing how to handle user input and apply validation logic in Java.

## Validation Rules
- **[Username](ca://s?q=Username_validation_rules)**: Must contain an underscore (`_`) and be no more than 5 characters long.  
- **[Password](ca://s?q=Password_validation_rules)**: Must be at least 8 characters, include one uppercase letter, one number, and one special character.  
- **[Cell Phone Number](ca://s?q=Cell_phone_validation_rules)**: Must start with `+` followed by 10–11 digits (international format).  

## Project Structure
registrationlogin/
│
├── Login.java
│   ├── checkUserName()              # Validates username format
│   ├── checkPasswordComplexity()    # Validates password rules
│   ├── checkCellPhoneNumber()       # Validates phone number format
│   ├── registerUser()               # Stores user details if valid
│   ├── loginUser()                  # Authenticates user credentials
│   └── returnLoginStatus()          # Displays login status message
│
└── RegistrationLogin.java
└── main()                       # Handles user input, registration, and login flow

## How It Works
1. **Registration Phase**  
   - Prompts the user for first name, last name, username, password, and cell phone number.  
   - Each input is validated using the rules above.  
   - If all inputs are valid, the user is registered successfully.  

2. **Login Phase**  
   - Prompts the user to enter their username and password.  
   - Compares input with stored credentials.  
   - Displays a personalized welcome message if successful, or an error message if not.  

## References
Farrell, J., 2023. Java Programming. 10th ed. Boston: Cengage Learning.

JUnit Team, 2026. JUnit 4 Documentation. [Online]  
Available at: https://junit.org/junit4/  
[Accessed 18 September 2026].

Oracle, 2023. Class Pattern. [Online]  
Available at: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/regex/Pattern.html  
[Accessed 18 September 2026].

Oracle, 2023. Class Scanner. [Online]  
Available at: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/Scanner.html  
[Accessed 18 September 2026]. 

## License
This project is licensed under the **MIT License**. You are free to use, modify, and distribute it with attribution.

## Code's functionality
The login class has methods that handles all validation user details. The registration login class contains the main method which manages user interaction.
