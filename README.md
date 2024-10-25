# Automated Login System for OTW Bandit Games

This Bash script automates the login process for various levels of the OverTheWire (OTW) Bandit wargames, simplifying the experience of connecting to each level.

## Overview

The OTW Bandit wargame is designed to teach the basics of Linux command-line usage, SSH, and security concepts. This script streamlines the process of logging into each level by handling password management for you.

## Features

- **Automated SSH login**: Quickly connect to any Bandit level with a single command.
- **Error handling**: Informative error messages for common issues.
- **User-friendly**: Simple command-line interface.

## Prerequisites

Before using this script, ensure you have the following:

- **`sshpass`**: The script relies on `sshpass` to automate SSH logins. Install it via your package manager if it's not already installed.
  
  For example, on Debian-based systems:
  ```bash
  sudo apt-get install sshpass
  ```

- **Password files**: Store the password for each Bandit level in a file named `bandit<level>`. For example, the password for level 5 should be in a file named `bandit5`.

## Usage

To use the script, run the following command in your terminal:

```bash
./otw_bandit <level_you_want_to_connect_to>
```

### Example

To connect to level 10, you would execute:

```bash
./otw_bandit 10
```

## Error Handling

- If no argument is provided, the script will display an error message:
  ```
  Error: No argument passed.
  Usage: ./bandit.sh <level_number>
  ```

- If the password file for the specified level is not found, the script will notify you:
  ```
  Error: Password file 'bandit<level>' not found.
  ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OverTheWire](https://overthewire.org/wargames/bandit/) for providing the Bandit wargame, which serves as an excellent resource for learning command-line skills.

## Contributing

Contributions are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

## Contact

For any questions or feedback, please reach out to me at [mackleodebenboulo@gmail.com].
```

### Key Sections:
- **Overview**: Brief explanation of the Bandit wargame and the script's purpose.
- **Features**: Highlights the benefits of using the script.
- **Prerequisites**: Lists necessary installations and files.
- **Usage**: Instructions on how to use the script, with examples.
- **Error Handling**: Details common error messages and their meanings.
- **License and Acknowledgments**: Credits and legal information.
- **Contributing**: Encourages collaboration and improvement.
- **Contact**: Provides a way for users to reach out with questions or feedback.

Feel free to personalize any part of it, such as the contact information, and add any additional sections relevant to your project! 
