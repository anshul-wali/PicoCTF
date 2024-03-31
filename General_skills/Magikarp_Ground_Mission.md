- Start the instance and connect to it using ssh.
- After loging in,run "pwd" to know the directory we are currently in, we get "/home/ctf-player/drop-in".
- List the content of directory using "ls". We see two files named "1of3.flag.txt" and "instructions-to-2of3.txt".
- Open the first file using "cat 1of3.flag.txt", there we find of our first half of flag.
- Open the second file using "cat instructions-to-2of3.txt", in there is string which tells us to go to root directory.
- Run "cd ..", to go one step down so we can get to the root directory.
- Once in root directory, run "ls" to list the files. There we find named "3of3.flag.txt".
- Open this file using "cat 3of3.flag.txt" and there we get our second half of flag. 
- <details> 
  <summary>Flag</summary>
   picoCTF{xxsh_1118a9a4}
  </details>
