## Create and compare hash values

---

Tasks: 
* Compare the plain text of the two files presented for hashing
* Compute the sha256sum hash of the two separate files
* Compare the hashes provided to identify the differences

---

1. Use **pwd** command to determine the current directory.<br>
![image](https://github.com/user-attachments/assets/b11d7b0e-02a2-4ccd-991f-84b9dd36c554)


2. Use **ls** command to list the contents of the directory.<br>
![image](https://github.com/user-attachments/assets/2e28e4e0-0829-48f9-bef6-adb8dde10c53)


3. Use **cat** command to display the contents of file1.txt and file2.txt.<br>
![image](https://github.com/user-attachments/assets/e6fbdfbf-83b2-4585-9b54-58a9a5ce97d6)


4. Use **sha256sum** command to generate the hash value for file1.txt and file2.txt.<br>
![image](https://github.com/user-attachments/assets/ab0a5782-dbdb-436e-9d19-dc21af8d2486)


5. Use **sha256sum** command and **>>** command to generate the hash value for file1.txt and file2.txt and send the value to new files called file1hash and file2hash. Use **ls** command to confirm the changes.<br>
![image](https://github.com/user-attachments/assets/e9495a0e-4885-401c-b981-bc4a0364dd9b)


6. Use **cat** command to display the hash values inside of file1hash and file2hash.<br>
![image](https://github.com/user-attachments/assets/5113f966-f954-4849-be84-88485e2ba19d)


7. Use **cmp** command to highlight the difference between file1hash and file2hash.<br>
![image](https://github.com/user-attachments/assets/e3d2c961-ea3a-46e3-8b1f-9486e6a90ae8)

The output of the cmp command indicates that the hashes differ at the first character in the first line.
