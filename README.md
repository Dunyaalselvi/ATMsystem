# ATMsystem
This project is a simulation of an Automated Teller Machine (ATM) system, implemented in C++. It allows users to perform basic banking operations such as changing their PIN, withdrawing cash, and depositing money. The system is designed to handle multiple users, each with a unique user ID, PIN, and account balances in two separate accounts. The ATM offers a language selection feature, supporting English and Turkish, ensuring accessibility for a wider audience.

Key Features:

1-User Authentication: The system verifies the user's identity by comparing the entered UserID and PIN with pre-defined records. If authentication fails, access is denied.

2-Language Support: The ATM system supports multiple languages (currently English and Turkish) to accommodate users from different regions.

3-ATM Menu: After successful authentication, users can interact with the ATM menu to select actions such as changing the PIN, withdrawing money, or depositing funds.

4-Balance Management: Users can withdraw and deposit money. The system ensures that withdrawal amounts do not exceed the available balance.
PIN Management: Users can change their PIN if they wish, with validation to ensure the new PIN meets the expected format.



Benefits:

1-Convenience: Users can access their account details and perform financial transactions at any time, without needing to visit a bank branch.

2-Security: The use of PINs ensures secure access to the ATM system.

3-Multi-language Support: The system allows users to interact in their preferred language, making it accessible to a broader audience.

4-Customization: Users have the option to change their PIN for enhanced security.

Challenges:

1-User Experience: Proper handling of user input and clear instructions are critical to ensure a smooth and intuitive user experience.

2-Error Handling: The system needs to be robust in handling invalid inputs, such as incorrect PINs or withdrawal amounts exceeding the balance.

3-Scalability: Although the system currently supports a small number of users, scalability would need to be considered for real-world applications, such as supporting larger databases and more complex user scenarios.

This ATM system project demonstrates fundamental concepts in C++ programming, such as handling user input, using structures for data storage, managing conditional logic, and working with loops for menu navigation. Additionally, the use of language translation functions adds an internationalization aspect, making the system adaptable for diverse populations.
