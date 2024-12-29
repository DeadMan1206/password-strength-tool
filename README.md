# password-strength-too
# Password Strength Assessment Tool

This Python tool evaluates the strength of a password based on multiple factors such as length, complexity, uniqueness, and entropy analysis. It provides feedback and a strength score to help users create stronger passwords.

## Features
- Checks for minimum password length.
- Validates complexity (uppercase, lowercase, numbers, special characters).
- Detects repeated characters and keyboard patterns.
- Identifies common weak passwords.
- Supports advanced entropy analysis using `zxcvbn` (if installed).
- Provides actionable feedback for password improvement.

## Requirements
- Python 3.6 or higher
- Optional: `zxcvbn` library for advanced entropy analysis. Install using:
  ```bash
  pip install zxcvbn
  ```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/DeadMan1206/password-strength-tool.git
   cd password-strength-tool
   ```
2. Run the script:
   ```bash
   python password_strength_tool.py
   ```
   By default, the script evaluates a predefined password. Update the `predefined_password` variable in the script to test custom passwords.

## Example Output
```
Testing with predefined password: ExamplePassword123!
Password Strength Score: 85/100
Feedback:
- Password length is strong.
- Your password is strong.
```

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the tool.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
