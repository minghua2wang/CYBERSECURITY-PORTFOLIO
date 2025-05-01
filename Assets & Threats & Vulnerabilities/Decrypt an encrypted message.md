## Decrypt an encrypted message

---

### Scenario <br>
In this scenario, all of the files in your home directory have been encrypted. You’ll need to use Linux commands to break the Caesar cipher and decrypt the files so that you can read the hidden messages they contain.

Here’s how you’ll do this task: First, you’ll explore the contents of the home directory and read the contents of a file. Next, you’ll find a hidden file and decrypt the Caesar cipher it contains. Finally, you’ll decrypt the encrypted data file to recover your data and reveal the hidden message.


---

1. Use the **ls** command to list the files in the current working directory.
![image](https://github.com/user-attachments/assets/e6cd998a-9c7e-4850-934b-43fe098b8c29)

2. Use the **cat** command to list the contents of the README.txt file.
![image](https://github.com/user-attachments/assets/4ed32315-47d2-44e2-b724-7ed8198debcb)

3. Use the **cd** command to change to the caesar subdirectory of your home directory
![image](https://github.com/user-attachments/assets/8025b443-992a-4b3a-8bff-36e8ec9ebe33)

4. Use the ls **-a** command to list all files, including hidden files, in your home directory.
![image](https://github.com/user-attachments/assets/795fc5f9-1696-44e0-b42c-33449c2272e8)

5. Use the **cat** command to list the contents of the .leftShift3 file.
![image](https://github.com/user-attachments/assets/92ac7ccb-3097-4264-88fe-2fad5bdb31b0)

6. Decrypt the Caesar cipher in the .leftshift3 file by using **cat .leftShift3 | tr "d-za-cD-ZA-C" "a-zA-Z"**
![image](https://github.com/user-attachments/assets/fe16fd27-c058-446b-a11d-02748581787a)

Note: The tr command translates text from one set of characters to another, using a mapping. The first parameter to the tr command represents the input set of characters, and the second represents the output set of characters. Hence, if you provide parameters “abcd” and “pqrs”, and the input string to the tr command is “ac”, the output string will be “pr".

7. Use **cd** command to return to your home directory. Use the exact command revealed in the previous task to decrypt the encrypted file. Use the ls command to list the contents of your current working directory again.
![image](https://github.com/user-attachments/assets/9482121e-0baf-4bba-81f0-5b3c42b08949)

8. Use the cat command to list the contents of the Q1.recovered file.
![image](https://github.com/user-attachments/assets/9332a279-0610-4cf0-b219-1239cb8f169e)
