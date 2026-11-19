# PASSWORD CRACKING REPORT

### Password cracking with John the Ripper and Networkwalks tools

**W2-PM-FINAL | CYBERSECURITY & ETHICAL HACKING INTERNSHIP | NETWORKWALKS**

| Field | Detail |
| --- | --- |
| **Name** | Erica Gyamfuaa Fordjour |
| **Program/Batch** | Networkwalks Cybersecurity & Ethical Hacking Internship, B084 |
| **Date** | 19 November 2026 |
| **Modules completed** | W3-PM1 (Password cracking with John the Ripper)<br>W3-PM2 (Password cracking with NetworkWalks tools) |


## Password Cracking with JTR (Johnny)

[Task](https://networkwalks.com/password-cracking-with-jtr-john-the-ripper-project-task-lab/)

This lab shows how to recover the password of a locked PDF using the Johnny tool. It is made for beginners and also works on Kali Linux where the tool is already installed.

Task: recover the password of the locked PDF using Johnny.

If you use Kali Linux you do not need to download anything. John the Ripper is already there.

Safe use
Only test files you own or have written permission to test. Use this lab for learning only.


## Requirements

- John the Ripper ([official site](https://www.openwall.com/john/))
- Johnny GUI ([official site](https://openwall.info/wiki/john/johnny))



# Steps

John the Ripper (JTR) is a popular password cracking tool used by security professionals to test how strong passwords are.Johnny is the graphical version of John the Ripper. I used JTR John and JTR Johnny to recover the password of a protected PDF file.

What I did:
- I used an online hashcrack to find the hash of an encrypted pdf file and saved the hash in a text document.

![alt text]()
 

- Opened Jonny and uploaded John.exe

![alt text]()


- Uploaded the text file to get the password of the encrypted pdf file

![alt text]()


- Successfully opned hash pdf file

![alt text]()




# NW Tools

- I used the Hash Calculator to take the hash out of a locked PDF file. 
- Then I used the Password Cracker to find the real password from that hash.
You can check the tasks from here https://networkwalks.com/password-cracking-with-jtr-john-the-ripper-project-task-lab/


# What I learned:
- Strong passwords are important for protection.
- Encryption is a two-way function; what is encrypted can be decrypted with the proper key. 
- Hashing, however, is a one-way function that scrambles plain text to produce a unique message digest

---