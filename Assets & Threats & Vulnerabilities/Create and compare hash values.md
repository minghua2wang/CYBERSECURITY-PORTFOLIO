## Create and compare hash values

---

Tasks: 
* Compare the plain text of the two files presented for hashing
* Compute the sha256sum hash of the two separate files
* Compare the hashes provided to identify the differences

---

1. Use **pwd** command to determine the current directory.


2. Use **ls** command to list the contents of the directory.


3. Use **cat** command to display the contents of file1.txt and file2.txt.


4. Use **sha256sum** command to generate the hash value for file1.txt and file2.txt.


5. Use **sha256sum** command and **>>** command to generate the hash value for file1.txt and file2.txt and send the value to new files called file1hash and file2hash. Use **ls** command to confirm the changes.


6. Use **cat** command to display the hash values inside of file1hash and file2hash.


7. Use **cmp** command to highlight the difference between file1hash and file2hash.

The output of the cmp command indicates that the hashes differ at the first character in the first line.
