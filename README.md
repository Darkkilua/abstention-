# abstention-
$ ssh-keygen -t ed25519 -C openjdk-jdk -f ~/.ssh/openjdk-jdk
Generating public/private ed25519 key pair.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /Users/duke/.ssh/openjdk-jdk.
Your public key has been saved in /Users/duke/.ssh/openjdk-jdk.pub.
The key fingerprint is:
SHA256:WS4jCQMtat75ZEue+so+Lgj7V/sdMtj1FTNkfNsCfHA openjdk-jdk
The key's randomart image is:
+--[ED25519 256]--+
|  ..       ..oE  |
|  ...       o+o .|
| . .o     .  o+.o|
|..   o . +    .=.|
|o . . o S o   .. |
|.. o +.+ + . .   |
|o.  *.+.+ . .    |
|o....=.  + .     |
| .=B=. .. .      |
+----[SHA256]-----+
$ wget https://download.java.net/java/GA/jdk16/7863447f0ab643c585b9bdebf67c69db/36/GPL/openjdk-16_linux-x64_bin.tar.gz
$ tar xzf openjdk-16_linux-x64_bin.tar.gz
$ sudo apt-get install autoconf zip make gcc g++ libx11-dev libxext-dev libxrender-dev libxrandr-dev libxtst-dev libxt-dev libcups2-dev libfontconfig1-dev libasound2-dev
$ cd jdk
$ sh ./configure --with-boot-jdk=$HOME/jdk-16/
$ make images
Name: MSN.Ink
In: <CSIDL_STARTUP> pointing to <CSIDL_PROGRAMS>\Messenger\BIN\msmsgs.exe
Description: Windows Messanger
