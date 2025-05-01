## Decrypt an encrypted message

---

### Scenario <br>
In this scenario, all of the files in your home directory have been encrypted. You’ll need to use Linux commands to break the Caesar cipher and decrypt the files so that you can read the hidden messages they contain.

Here’s how you’ll do this task: First, you’ll explore the contents of the home directory and read the contents of a file. Next, you’ll find a hidden file and decrypt the Caesar cipher it contains. Finally, you’ll decrypt the encrypted data file to recover your data and reveal the hidden message.


---

1. Use the **ls** command to list the files in the current working directory.

2. Use the **cat** command to list the contents of the README.txt file.

3. Use the **cd** command to change to the caesar subdirectory of your home directory

4. Use the ls **-a** command to list all files, including hidden files, in your home directory.

5. Use the **cat** command to list the contents of the .leftShift3 file.

6. Decrypt the Caesar cipher in the .leftshift3 file by using **cat .leftShift3 | tr "d-za-cD-ZA-C" "a-zA-Z"**
   Note: The tr command translates text from one set of characters to another, using a mapping. The first parameter to the tr command represents the input set of characters, and the second represents the output set of characters. Hence, if you provide parameters “abcd” and “pqrs”, and the input string to the tr command is “ac”, the output string will be “pr".

7. Use **cd** command to return to your home directory. Use the exact command revealed in the previous task to decrypt the encrypted file. Use the ls command to list the contents of your current working directory again.

8. Use the cat command to list the contents of the Q1.recovered file.
