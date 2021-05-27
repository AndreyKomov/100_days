**1 day (21.05.2021)** - encrypted disk C with eror (file not found). 
1. Press Windows key + E, to open File Explorer.
2. Navigate to C:\Windows\System32\Recovery.
3. Look for REAgent.xml file, right click on it and click on Rename.
4. Rename the file to REAgent.old.
5. If you receive any prompt click on Yes.
6. Start the Bit Locker encryption process.

**1 day (27.05.2021)** - add new SSG-key to GitHub (for my new device)/
Администратор@DESKTOP-6B1Q3NI MINGW64 /d/work
$ ssh-keygen -t ed25519 -C "komov.te@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/Администратор/.ssh/id_ed25519): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /c/Users/Администратор/.ssh/id_ed25519
Your public key has been saved in /c/Users/Администратор/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:+3w/JeQ2n266qoy5+AJbhCS370NXjDNs8ZVkdETnWeg komov.te@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|          o+++ o.|
| . o   .  .o. + o|
|  + o . = .  . o |
|   o . * +    E  |
|    o . S    o   |
|   . + . .    = .|
|    * . .    . =.|
|   . +. +o  . .o.|
|     .+=.o+o.+*o |
+----[SHA256]-----+

Администратор@DESKTOP-6B1Q3NI MINGW64 /d/work
$ ssh-keygen -t ed25519 -C "komov.te@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/Администратор/.ssh/id_ed25519): 
/c/Users/Администратор/.ssh/id_ed25519 already exists.
Overwrite (y/n)? y
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Passphrases do not match.  Try again.
Enter passphrase (empty for no passphrase):
Enter same passphrase again: 
Your identification has been saved in /c/Users/Администратор/.ssh/id_ed25519
Your public key has been saved in /c/Users/Администратор/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:VIQMNwvPQDO6ZIG77IkBdjtBDxCFLwLtpetufISaIkE komov.te@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
| +=o..Boooo      |
|..oo.o Oo+       |
|..o+*   =        |
|oE+* o .         |
|=.o++   S        |
|o =o.            |
| X o.            |
|* * .            |
|oo..             |
+----[SHA256]-----+

Администратор@DESKTOP-6B1Q3NI MINGW64 /d/work
$ eval "$(ssh-agent -s)"
Agent pid 467

Администратор@DESKTOP-6B1Q3NI MINGW64 /d/work
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/Администратор/.ssh/id_rsa (Администратор@DESKTOP-6B1Q3NI)

Администратор@DESKTOP-6B1Q3NI MINGW64 /d/work
$ clip < ~/.ssh/id_rsa.pub

Администратор@DESKTOP-6B1Q3NI MINGW64 /d/work
$ git clone git@github.com:AndreyKomov/historical-quiz.git
Cloning into 'historical-quiz'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

Администратор@DESKTOP-6B1Q3NI MINGW64 /d/work
$
