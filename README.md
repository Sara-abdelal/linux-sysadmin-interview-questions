Linux System Administrator/DevOps Interview Questions
====================================================

A collection of linux sysadmin/devops interview questions. Feel free to contribute via pull requests, issues or email messages.


## <a name='toc'>Table of Contents</a>

  1. [Contributors](#contributors)
  1. [General Questions](#general) [Answers](#answers)
  1. [Simple Linux Questions](#simple)
  1. [Medium Linux Questions](#medium)
  1. [Hard Linux Questions](#hard)
  1. [Expert Linux Questions](#expert)
  1. [Networking Questions](#network)
  1. [MySQL Questions](#mysql)
  1. [DevOps Questions](#devop)
  1. [Fun Questions](#fun)
  1. [Demo Time](#demo)
  1. [Other Great References](#references)
  


#### [[⬆]](#toc) <a name='contributors'>Contributors:</a>

* [moregeek](https://github.com/moregeek)
* [typhonius](https://github.com/typhonius)
* [schumar](https://github.com/schumar)
* [negesti](https://github.com/negesti)
* peter
* [andreashappe](https://github.com/andreashappe)
* [quatrix](https://github.com/quatrix)
* [biyanisuraj](https://github.com/biyanisuraj)
* [pedroguima](https://github.com/pedroguima)
* Ben
* [bharatnc](https://github.com/bharatnc)


#### [[⬆]](#toc) <a name='general'>General Questions:</a>

* What did you learn yesterday/this week?
* Talk about your preferred development/administration environment. (OS, Editor, Browsers, Tools etc.)
* Tell me about the last major Linux project you finished.
* Tell me about the biggest mistake you've made in [some recent time period] and how you would do it differently today. What did you learn from this experience?
* Why we must choose you?
* What function does DNS play on a network?
* What is HTTP?
* What is an HTTP proxy and how does it work?
* Describe briefly how HTTPS works.
* What is SMTP? Give the basic scenario of how a mail message is delivered via SMTP.
* What is RAID? What is RAID0, RAID1, RAID5, RAID10?
* What is a level 0 backup? What is an incremental backup?
* Describe the general file system hierarchy of a Linux system.
* Which difference have between public and private SSH key?

#### [[⬆]](#toc) <a name='answers'>General Questions Answers:</a>
* What did you learn yesterday/this week?
>>github new account sign up, forking repositories , know more about github, terraform aws , hands on aws solution architect 

* Talk about your preferred development/administration environment. (OS, Editor, Browsers, Tools etc.)
>> Admin environment Linux or unix , but preferrably Linux (redhat or ubuntu,..) 
Browsers : chrome as it is mostly compatitble with most webpages and apps (simple , secure , platform independant , leading the market , Extensions and Add-ons , gained Google trust)


* Tell me about the last major Linux project you finished.
>> 1-Administrating AWS webservers from command line bu installing apached and make simple webserver 
>> 2-Launching a fault tolerant Word Press Site on aws environment using s3 to server and save source code using crobjob .
>> 3-Using aws cloudformation to serve any atatched media in wordpress articles to improve perfomance of launching images by leveraging aws backbone network to edge locations .
>> 4-building a serverless website using aws lambda and API Gateway

* Tell me about the biggest mistake you've made in [some recent time period and how you would do it differently today. What did you learn from this experience?
>>biggest mistake i've made that i delayed studying AWS and postponed it but i made a good decision in studing it from zero till i get Solution architect certificate and found it more and more exciting .
i Learned that there is more yet to come and looking forward for my sysops admin certificate .

* Why we must choose you?
>> AWS solution architect certified 
>> Was working with Elite customers @ DellEMC and managed to solve customer production issues live on production servers.
>> contacting Elite customer live via phone , email and webex 
>> Linux administrator certificate 
>> Vmware certified 
>> problem solver 
>> good presentation skills 
>> Passionate 
>> Strong communication skills (written, verbal, nonverbal)
>> Friendly
>> Enthusiastic

* What is URL ?
Uniform Resource locator 

* What function does DNS play on a network?
>> Whomeever used the internet ,definitly used DNS , IT is used to convert human friendly domain name as www.google.com into and  internet protocol (IP) as 1.2.3.4

Domain Name system is the internet Yelloe pages .
DNS workes as a Phone book converting Domain name and resolve it to ip address "computers can understand"

ipv4 :32 bit (4 billion add) and ipv6 is 128 bits (340 undecillion add )

ipv6 created to solve depletion issue as IOT and all other devices consumed ipv4 to get connected to internet  as it was invented in pre internet days and wouldn't predict the great things connected to  internet .  

Ip addresses are used by computers to identify each others on the internet  , commonly come in ipv4 and ipv6

ipv4 is the past while ipv6 is the futur.
https://www.youtube.com/watch?v=Rck3BALhI5c&index=203&list=PLQMVnqe4XbictUtFZK1-gBYvyUzTWJnOk&t=0s

* What is HTTP?
>> HTTP : Hyper Text Transfer Protocol
it is about communication between Web clients and servers 
Communication between client computers and web servers is done by sending HTTP Requests and receiving HTTP Responses

The World Wide Web is about communication between web clients and web servers.

Clients are often browsers (Chrome, Edge, Safari), but they can be any type of program or device.

Servers are most often computers in the cloud.
HTTP Request / Response

Communication between clients and servers is done by requests and responses:

1-A client (a browser) sends an HTTP request to the web
2-An web server receives the request
3-The server runs an application to process the request
4-The server returns an HTTP response (output) to the browser
5-The client (the browser) receives the response
https://www.youtube.com/watch?v=MBwdO30YsGs

* What is an HTTP proxy and how does it work?
>>A HTTP proxy speaks the HTTP protocol, it's especially made for HTTP connections but can be abused for other protocols as well (which is kinda standard already)

The browser (CLIENT) sends GET http://SERVER/path HTTP/1.1 to the PROXY
Now the PROXY will forward the actual request to the SERVER.
The SERVER will only see the PROXY as connection and answer to the PROXY just like to a CLIENT.
The PROXY receives the response and forwards it back to the CLIENT.

It is a transparent process and nearly like directly communicating with a server so it's just a tiny overhead for the browser to implement a HTTP proxy.
There are some additional headers that can be sent to identify the client, reveal that he's using a proxy.
Proxies sometimes change/add content within the data stream for various purposes.
Some proxies for example include your real IP in a special HTTP HEADER which can be logged server-side, or intercepted in their scripts.

CLIENT <---> PROXY <---> SERVER

Communication between two computers connected through a third computer acting as a proxy. Bob does not know to whom the information is going, which is why proxies can be used to protect privacy.

* Describe briefly how HTTPS works.
https is used if you want to provide your customers with safe, secure environment environment on your website by getting web security . so to purchase and SSL certificate  that can be purchased from a web services company who is a certificate authority it :
1- check refrences 
2- assures identity
3- encrypt any data flows to or from my website keepting it secure from outsiders security (who want to steal customer's info and credit cards numbers)

for a secure website (after regsitering a domain and have a website designed and hosted ready to start selling online items) , you purchase an SSL certificate , this certificate authenticates a business's online identity and creates a unique scrambled  connection to provide users (online shoppers) with a safe , secure environement .if customers feels safe they'll feel more comfortable doing business with me on the web 

SSL: Secure Socket layer

according to SSL certificate my website purchased , client's browser may display a small icons shape  like a lock , a thumbs up , a green browser bar or some other reassuring symbol when security is in place , once 2 computers agreed on method to use , data will start flow back and forth between them , when data leaves one computer it's scrambled using agreed upon method and descrambled when it arrives at the other computer 

https://www.youtube.com/watch?v=SJJmoDZ3il8

* What is SMTP? Give the basic scenario of how a mail message is delivered via SMTP.
>> Simple Mail Transfer Protocol , while POP and IMAP are protocols that allow you to retrieve email from a  mail server ,SMPT is the protocol that allows you to send email to Mail server

when you send an email using free email providers lile gmail or yahoo or hotmail , you email address uses their domain name "gmail.com , yahoo.com and hotmail.com" and in turn they allow you to use  their email servers

however if you use local mail client like outlook , apple mail and Mozilla thunderbird , you will need to enter you email providres incoming and outgoing mail server settings when you setup your client .
Incoming server setting (POP , IMAP)tells the email client where it can retrieve your mail from 
Outgoing mail server settings (SMTP) tells the email client where it can send your email to .

Send email process and role of SMTP servers play in it ?
ex : Maggie her mail is maggie@yahoo.com she  is using Yahoo as her email sevrice provider, she likes to use outlook as her email client for wrting , reading and sending emails on it .

So , to make sure outlook can communicate wit yahoo mail server she entered yahoo email server settings when she configured her MS Outlook.

Maggie writes an email to her friend rob using MS Outlook;
To: rob@gmail.com
From : Maggie@yahoo.com
Hi rob,
welcome back from you vacation
thanks ,
when she clicks SEND , Ms outlook sends Rob's email add and her email add and the email body to Yahoo SMTP server.

When yahoo mail server recieves this , it breaks Rob's email add into 2 parts the recipient ID (Rob) and the domian name after @ sign (@gmail.com) , then Yahoo SMTP mail server then goes out to the internet and throught a series of server conversations ,it locates the SMTP mail server of gmail .

Then Yahoo SMTP server Passes Maggie's email to Gmail SMTP  server .

Maggies email will remains @ Gmail SMTP server till Rob logs into his gmail account and retrieve the email.

So, SMTP is the protocol that allows you to send emails from an email client  to mail server
  
https://www.youtube.com/watch?v=j7kMZD81hec

* What is RAID? What is RAID0, RAID1, RAID5, RAID10?
>>Redundant Array of Inexpensive (independant)	Disks ; means using multiple disk drives to achieve better performance and/or better reliability

R0 : all about speed nothing for reliability excepts actually make it works , involves  2 drives or more and striping the data across all of the drives this mean u get to keep all ur capcity and in theory with 2 drives u will have double ur read and write performance  but in event of one drive failed , u will lose all of the data stored on both drives ,it is ideal if your are doing very frequent bkups or going for most extreme performance possible as running multiple SSD's.

R1 : All about reliability , the capacity of 1 of ur drives , the performance of 1 of your drives but u get the redundancy of 2 drives means if 1 of 2 drives failed , all of the data will still there on the other one .
you are still get full perfomance of the drives but the more drives u add to Raid 1 , you will always get half the capacity that u would have 
advantage , it is extremely safe so most inportnt documents to be raid 1 array .


R10 : get all good about R0 and what good about R1 into same thing , u take 4 drives u striping  disk 0 and disk 2 and will be mirrored with 1 and 3.So u will get double performance of an individual disk and double capacity of an individual disk but u can lose up to 2 drives in R10 array without losing any data .
Greate where performance is needed , space is needed .

Note : Raid is not a susptitutional to Backups .on Raid you still suspectible to virus or accidental deletion or other human error so need to make sure you make regular backups

R5 & R6 : is used for more professional applications 

R5 : needs atleast 3 drives to operate 

if u have 6 drives , u have the capacity of 5 drives as there is 1 reserved  to rebuild the data on the array incase a drive failure 

it stored data on multiple drives , u can read from it extremely quickly .However writing on R5 will be much slower (without complex hardware RAID controller) and rebuilding the array from 1 drive failure can be time consuming .

R6 : is a more durable version of R5 , it can survive up to 2 drives failures  and still be completely rebuild , u can have at least 4 drives  and much slower to write than R5 and wzout complex h/w RAID controller u can't really run R6
https://www.youtube.com/watch?v=1P8ZecG9iOI
https://www.youtube.com/watch?v=eE7Bfw9lFfs

* What is a level 0 backup? What is an incremental backup?
The only difference between a level 0 incremental backup and a full backup is that a full backup is never included in an incremental strategy.
Full and level zero backups copy all blocks that have data (and more if you're doing image copies), so they are both "full" in that sense.
But if you want to do cumulative or differential backups, the starting point for those must be a level zero incremental backup.

* Describe the general file system hierarchy of a Linux system.
/ >> Root directory
/bin >> Binaries  and executable programs 
/etc >> system files configurations
/home >> user home directories
/opt >> application software package 
/tmp >>temproray files ,  typically cleared on reboot.
/usr >> user utilities and applications
/var >>	Variable data, most notably log files.
/boot  >>static files of boot loader
/dev >> devices files
/lib >> shared libraries
/mnt >> mounted filesystem

https://www.linuxtrainingacademy.com/linux-directory-structure-and-file-system-hierarchy/

https://www.linuxtrainingacademy.com/linux-ip-command-networking-cheat-sheet/

https://www.linuxtrainingacademy.com/linux-commands-cheat-sheet/

Actually our computers are forgrtfull and never remebred where we put staff like imp documents or my os or games ...
So FS is doen to keep track of where all my staff is . All types of systems in common divided up your HD SSD or flash drives into small units that stores data and have some kind of way to remebering what data is in each unit spo to find it later on .
FAT (File Allocation Table) used by Windows till windows xp then Fat32 comes with windows 98 but still have same issue of unused spaces on Hard left "SLACK" then NTFS "nEW technology FS"
used some space mgmt tricks to make use of space more effiently than FAT, SO can support massive partitions of hundreds of TB and can prevent DL , native file compression and security .

Note Fat32 is still used on USB flash drives to maintain compatibility with old versions of Windows and other OS as linux .

there is EXFAT then appeared.


https://www.youtube.com/watch?v=BV0-EPUYuQc&list=PLQMVnqe4XbictUtFZK1-gBYvyUzTWJnOk&index=208


* Which difference have between public and private SSH key?
SSH, or secure shell, is a secure protocol and the most common way of safely administering remote servers. Using a number of encryption technologies, SSH provides a mechanism for establishing a cryptographically secured connection between two parties, authenticating each side to the other, and passing commands and output back and forth.
Think of a public key as being the lock. It’s not actually a key, it’s a padlock you can make lots of copies of and distribute wherever you want. For example, if you want to put your ‘padlock’ on an ssh account on another machine, you would copy it to ‘authorized_keys’ in the ~/.ssh folder. You’ve setup the padlock.
Think of a private key as being the actual key. This is what you use to open the padlock that is stored on the other machine. Just like a regular key you keep it secret, safe, and out of the wrong hands.
http://blakesmith.me/2010/02/08/understanding-public-key-private-key-concepts.html



#### [[⬆]](#toc) <a name='simple'>Simple Linux Questions:</a>

* What is the name and the UID of the administrator user?
* How to list all files, including hidden ones, in a directory?
* What is the Unix/Linux command to remove a directory and its contents?
* Which command will show you free/used memory? Does free memory exist on Linux?
* How to search for the string "my konfu is the best" in files of a directory recursively?
* How to connect to a remote server or what is SSH?
* How to get all environment variables and how can you use them?
* I get "command not found" when I run ```ifconfig -a```. What can be wrong?
* What happens if I type TAB-TAB?
* What command will show the available disk space on the Unix/Linux system?
* What commands do you know that can be used to check DNS records?
* What Unix/Linux commands will alter a files ownership, files permissions?
* What does ```chmod +x FILENAME``` do?
* What does the permission 0750 on a file mean?
* What does the permission 0750 on a directory mean?
* How to add a new system user without login permissions?
* How to add/remove a group from a user?
* What is a bash alias?
* How do you set the mail address of the root/a user?
* What does CTRL-c do?
* What does CTRL-d do?
* What does CTRL-z do?
* What is in /etc/services?
* How to redirect STDOUT and STDERR in bash? (> /dev/null 2>&1)
* What is the difference between UNIX and Linux.
* What is the difference between Telnet and SSH?
* Explain the three load averages and what do they indicate. What command can be used to view the load averages?
* Can you name a lower-case letter that is not a valid option for GNU ```ls```?
* What is a Linux kernel module?
* Walk me through the steps in booting into single user mode to troubleshoot a problem.
* Walk me through the steps you'd take to troubleshoot a 404 error on a web application you administer.
* What is ICMP protocol? Why do you need to use?

#### [[⬆]](#toc) <a name='medium'>Medium Linux Questions:</a>

* What do the following commands do and how would you use them?
 * ```tee```
 * ```awk```
 * ```tr```
 * ```cut```
 * ```tac```
 * ```curl```
 * ```wget```
 * ```watch```
 * ```head```
 * ```tail```
 * ```less```
 * ```cat```
 * ```touch```
 * ```sar```
 * ```netstat```
 * ```tcpdump```
 * ```lsof```
* What does an ```&``` after a command do?
* What does ```& disown``` after a command do?
* What is a packet filter and how does it work?
* What is Virtual Memory?
* What is swap and what is it used for?
* What is an A record, an NS record, a PTR record, a CNAME record, an MX record?
* Are there any other RRs and what are they used for?
* What is a Split-Horizon DNS?
* What is the sticky bit?
* What does the immutable bit do to a file?
* What is the difference between hardlinks and symlinks? What happens when you remove the source to a symlink/hardlink?
* What is an inode and what fields are stored in an inode?
* How to force/trigger a file system check on next reboot?
* What is SNMP and what is it used for?
* What is a runlevel and how to get the current runlevel?
* What is SSH port forwarding?
* What is the difference between local and remote port forwarding?
* What are the steps to add a user to a system without using useradd/adduser?
* What is MAJOR and MINOR numbers of special files?
* Describe the mknod command and when you'd use it.
* Describe a scenario when you get a "filesystem is full" error, but 'df' shows there is free space.
* Describe a scenario when deleting a file, but 'df' not showing the space being freed.
* Describe how 'ps' works.
* What happens to a child process that dies and has no parent process to wait for it and what’s bad about this?
* Explain briefly each one of the process states.
* How to know which process listens on a specific port?
* What is a zombie process and what could be the cause of it?
* You run a bash script and you want to see its output on your terminal and save it to a file at the same time. How could you do it?
* Explain what echo "1" > /proc/sys/net/ipv4/ip_forward does.
* Describe briefly the steps you need to take in order to create and install a valid certificate for the site https://foo.example.com.
* Can you have several HTTPS virtual hosts sharing the same IP?
* What is a wildcard certificate?
* Which Linux file types do you know?
* What is the difference between a process and a thread? And parent and child processes after a fork system call?
* What is the difference between exec and fork?
* What is "nohup" used for?
* What is the difference between these two commands?
 * ```myvar=hello```
 * ```export myvar=hello```
* How many NTP servers would you configure in your local ntp.conf?
* What does the column 'reach' mean in ```ntpq -p``` output?
* You need to upgrade kernel at 100-1000 servers, how you would do this?
* How can you get Host, Channel, ID, LUN of SCSI disk?
* How can you limit process memory usage?
* What is bash quick substitution/caret replace(^x^y)?
* Do you know of any alternative shells? If so, have you used any?
* What is a tarpipe (or, how would you go about copying everything, including hardlinks and special files, from one server to another)?
* How can you tell if the httpd package was already installed?
* How can you list the contents of a package?
* How can you determine which package is better: openssh-server-5.3p1-118.1.el6_8.x86_64 or openssh-server-6.6p1-1.el6.x86_64 ?
* Can you explain to me the difference between block based, and object based storage?

#### [[⬆]](#toc) <a name='hard'>Hard Linux Questions:</a>

* What is a tunnel and how you can bypass a http proxy?
* What is the difference between IDS and IPS?
* What shortcuts do you use on a regular basis?
* What is the Linux Standard Base?
* What is an atomic operation?
* Your freshly configured http server is not running after a restart, what can you do?
* What kind of keys are in ~/.ssh/authorized_keys and what it is this file used for?
* I've added my public ssh key into authorized_keys but I'm still getting a password prompt, what can be wrong?
* Did you ever create RPM's, DEB's or solaris pkg's?
* What does ```:(){ :|:& };:``` do on your system?
* How do you catch a Linux signal on a script?
* Can you catch a SIGKILL?
* What's happening when the Linux kernel is starting the OOM killer and how does it choose which process to kill first?
* Describe the linux boot process with as much detail as possible, starting from when the system is powered on and ending when you get a prompt.
* What's a chroot jail?
* When trying to umount a directory it says it's busy, how to find out which PID holds the directory?
* What's LD_PRELOAD and when it's used?
* You ran a binary and nothing happened. How would you debug this?
* What are cgroups? Can you specify a scenario where you could use them?
* How can you remove/delete a file with file-name consisting of only non-printable/non-type-able characters?
* How can you increase or decrease the priority of a process in Linux?
* What are run-levels in Linux?


#### [[⬆]](#toc) <a name='expert'>Expert Linux Questions:</a>

* A running process gets ```EAGAIN: Resource temporarily unavailable``` on reading a socket. How can you close this bad socket/file descriptor without killing the process?
* What do you control with swapiness?
* How do you change TCP stack buffers? How do you calculate it?
* What is Huge Tables? Why isn't it enabled by default? Why and when use it?
* What is LUKS? How to use it?


#### [[⬆]](#toc) <a name='network'>Networking Questions:</a>

* What is localhost and why would ```ping localhost``` fail?
* What is the similarity between "ping" & "traceroute" ? How is traceroute able to find the hops.
* What is the command used to show all open ports and/or socket connections on a machine?
* Is 300.168.0.123 a valid IPv4 address?
* Which IP ranges/subnets are "private" or "non-routable" (RFC 1918)?
* What is a VLAN?
* What is ARP and what is it used for?
* What is the difference between TCP and UDP?
* What is the purpose of a default gateway?
* What is command used to show the routing table on a Linux box?
* A TCP connection on a network can be uniquely defined by 4 things. What are those things?
* When a client running a web browser connects to a web server, what is the source port and what is the destination port of the connection?
* How do you add an IPv6 address to a specific interface?
* You have added an IPv4 and IPv6 address to interface eth0. A ping to the v4 address is working but a ping to the v6 address gives you the response ```sendmsg: operation not permitted```. What could be wrong?
* What is SNAT and when should it be used?
* Explain how could you ssh login into a Linux system that DROPs all new incoming packets using a SSH tunnel.
* How do you stop a DDoS attack?
* How can you see content of an ip packet?
* What is IPoAC (RFC 1149)?
* What will happen when you bind port 0?



#### [[⬆]](#toc) <a name='mysql'>MySQL questions:</a>

* How do you create a user?
* How do you provide privileges to a user?
* What is the difference between a "left" and a "right" join?
* Explain briefly the differences between InnoDB and MyISAM.
* Describe briefly the steps you need to follow in order to create a simple master/slave cluster.
* Why should you run "mysql_secure_installation" after installing MySQL?
* How do you check which jobs are running?
* How would you take a backup of a MySQL database?

#### [[⬆]](#toc) <a name='devop'>DevOps Questions:</a>

* Can you describe your workflow when you create a script?
* What is GIT?
* What is a dynamically/statically linked file?
* What does "./configure && make && make install" do?
* What is puppet/chef/ansible used for?
* What is Nagios/Zenoss/NewRelic used for?
* What is Jenkins/TeamCity/GoCI used for?
* What is the difference between Containers and VMs?
* How do you create a new postgres user?
* What is a virtual IP address? What is a cluster?
* How do you print all strings of printable characters present in a file?
* How do you find shared library dependencies?
* What is Automake and Autoconf?
* ./configure shows an error that libfoobar is missing on your system, how could you fix this, what could be wrong?
* What are the advantages/disadvantages of script vs compiled program?
* What's the relationship between continuous delivery and DevOps?
* What are the important aspects of a system of continuous integration and deployment?
* How would you enable network file sharing within AWS that would allow EC2 instances in multiple availability zones to share data?

#### [[⬆]](#toc) <a name='fun'>Fun Questions:</a>

* A careless sysadmin executes the following command: ```chmod 444 /bin/chmod ``` - what do you do to fix this?
* I've lost my root password, what can I do?
* I've rebooted a remote server but after 10 minutes I'm still not able to ssh into it, what can be wrong?
* If you were stuck on a desert island with only 5 command-line utilities, which would you choose?
* You come across a random computer and it appears to be a command console for the universe. What is the first thing you type?
* Tell me about a creative way that you've used SSH?
* You have deleted by error a running script, what could you do to restore it?
* What will happen on 19 January 2038?
* How to reboot server when reboot command is not responding?


#### [[⬆]](#toc) <a name='demo'>Demo Time:</a>

* Unpack test.tar.gz without man pages or google.
* Remove all "*.pyc" files from testdir recursively?
* Search for "my konfu is the best" in all *.py files.
* Replace the occurrence of "my konfu is the best" with "I'm a linux jedi master" in all *.txt files.
* Test if port 443 on a machine with IP address X.X.X.X is reachable.
* Get http://myinternal.webserver.local/test.html via telnet.
* How to send an email without a mail client, just on the command line?
* Write a ```get_prim``` method in python/perl/bash/pseudo.
* Find all files which have been accessed within the last 30 days.
* Explain the following command ```(date ; ps -ef | awk '{print $1}' | sort | uniq | wc -l ) >> Activity.log```
* Write a script to list all the differences between two directories.
* In a log file with contents as ```<TIME> : [MESSAGE] : [ERROR_NO] - Human readable text``` display summary/count of specific error numbers that occurred every hour or a specific hour.


#### [[⬆]](#toc) <a name='references'>Other Great References:</a>

Some questions are 'borrowed' from other great references like:

* https://github.com/darcyclarke/Front-end-Developer-Interview-Questions
* https://github.com/kylejohnson/linux-sysadmin-interview-questions/blob/master/test.md
* http://slideshare.net/kavyasri790693/linux-admin-interview-questions
