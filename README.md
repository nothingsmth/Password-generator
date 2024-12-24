# Password Generator

This is a simple Python-based password generator that allows you to create random passwords with customizable options for length, uppercase letters, digits, and symbols.

## Features
- Specify the length of the password.
- Option to include or exclude uppercase letters, digits, and special symbols.
- Ensures a strong and random password.

## Requirements
- Python 3.6 or higher

## Usage
1. Clone this repository or copy the code into a file named `password_generator.py`.
2. Run the script in your terminal:
   ```bash
   python password_generator.py
   ```
3. Follow the prompts to customize your password:
   - Enter the desired password length.
   - Choose whether to include uppercase letters, digits, and symbols.

### Example Output
```
Password Generator
Enter password length (default is 12): 16
Include uppercase letters? (y/n, default is y): y
Include digits? (y/n, default is y): y
Include symbols? (y/n, default is y): n
Your generated password: abCDeFGh123ijkl
```

## How It Works
The script generates a random password based on your input using Python's `random` and `string` modules. You can customize the password to meet your security needs.

## Contributing
Feel free to fork the repository and submit pull requests for improvements or additional features.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy generating secure passwords! 🔒
