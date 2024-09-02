AUTHOR-SWASTIK ROY CHOUDHURY,

This tool takes user-provided passwords and checks them against certain security benchmarks like length, use of upper and lowercase letters, numbers, and special characters. Based on these factors, it assigns a strength level, which helps users improve their password security.

1)Install the pynput library using pip:pip install pynput
2)Run the program:python keylogger.py
3)The program will record keystrokes and save them to a file called key_log.txt.

Note:
The program will stop logging when the Esc key is pressed.

EXAMPLE OF CODE INPUT & OUTPUT


Enter a password: swa
Password strength: Weak
Would you like to check another password? (y/n): y
Enter a password: swastik12
Password strength: Medium
Would you like to check another password? (y/n): y
Enter a password: Swastik
Password strength: Weak
Would you like to check another password? (y/n): y
Enter a password: Swastik@
Password strength: Strong
Would you like to check another password? (y/n): n
