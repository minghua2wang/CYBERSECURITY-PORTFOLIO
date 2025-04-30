## Create and compare hash values

---

Tasks: 
* Compare the plain text of the two files presented for hashing
* Compute the sha256sum hash of the two separate files
* Compare the hashes provided to identify the differences

---

1. Use **pwd** command to determine the current directory.
[1](image_url)

2. Use **ls** command to list the contents of the directory.
[2](image_url)

3. Use **cat** command to display the contents of file1.txt and file2.txt.
[3](image_url)

4. Use **sha256sum** command to generate the hash value for file1.txt and file2.txt.
[4](image_url)

5. Use **sha256sum** command and **>>** command to generate the hash value for file1.txt and file2.txt and send the value to new files called file1hash and file2hash. Use **ls** command to confirm the changes.
[5](image_url)

6. Use **cat** command to display the hash values inside of file1hash and file2hash.
[6](image_url)

7. Use **cmp** command to highlight the difference between file1hash and file2hash.
[7](image_url)
The output of the cmp command indicates that the hashes differ at the first character in the first line.
