# Introductions to Cyber-Security

## Become a hacker

### Task1: What is Offensive Security

Answer: Offensive Security

### Task2: Let's Hack Part 1/2

*- 1st Method:* 
After the / , add : sitemap, mail, login, register, admin
On this list, only "login" redirect us to a new page, so, the answer is : **login**

*- 2nd Method: *
On the terminal, type: "gobuster dir --url http://www.onlineshop.thm/ -w /usr/share/wordlists/dirbuster/directory-list.txt"
The gobuster command show you all the page of the website, you can see "/login" is on the list, here is the answer: **login**


### Task3 : Let's Hack Part  2/2

*- 1st Method:*
You can type all the password that the website shows you: "abc123", "123456", "qwerty", "password", "654321"
On this list, the password who log us on the account is **qwerty**

*- 2nd Method:*
You can bruteforce the password with the tool "Hydra" by using this command : "hydra -l admin -P passlist.txt www.onlineshop.thm http-post-form "/login:username=^USER^&password=^PASS^:F=incorrect" -V"
 Hydra, gonna test all the password on the "passlist.txt" file with the username: "admin" and at the end, he will show us the good password : "80][http-post-form] host: www.onlineshop.thm login: admin password: qwerty"
So the password is **qwerty**

Now when you know the password, just log in using the username admin and the password "qwerty", a pop up show a flag : **"born_to_be_a_hacker"**


### Task4 - Careers in Cyber Security

No answer needed, just read 
