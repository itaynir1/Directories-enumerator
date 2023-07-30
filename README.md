# Directories Enumerator Project
## Directory Enumerator :
The Directory Enumerator is a Python script that helps you discover directories or paths on a given target website. It utilizes the power of Python's `requests` library to send HTTP requests and determine if the directories exist on the target server.

## Features
- Efficiently enumerates directories on a target URL.
- Lightweight and easy to use.
- Makes use of Python's `requests` library for HTTP requests.

## How to Use
1. **Prerequisites:** Make sure you have Python 3.x installed on your system.
2. **Installation:** No installation is required. Simply download the directory_enumerator.py script and you're good to go!

3. **Usage:**

- Open your terminal or command prompt.
- Navigate to the directory where you saved `directory_enumerator.py`.
- Execute the script using the following command:
```python
python directory_enumerator.py
```

4. **Input:**
- Upon running the script, you will be prompted to provide the target URL you want to enumerate directories on.
- Next, you'll be asked to enter the name of the file containing the directories you wish to check.

5. **Output:**

- The script will start sending requests to the target URL combined with each directory from the specified file.
- If a directory exists on the target server, it will be printed as output, indicating a successful discovery.

6. **Example:**

```Python
[*] Enter Target URL: https://example.com
[*] Enter Name Of The File Containing Directories: directories.txt
[*] Discovered Directory At This Path: https://example.com/admin
[*] Discovered Directory At This Path: https://example.com/images
[*] Discovered Directory At This Path: https://example.com/js
```
# Disclaimer
This script is intended for educational and ethical testing purposes only. Unauthorized access to systems or websites is illegal and unethical. Use this tool responsibly and with proper authorization from the target website's owner.
