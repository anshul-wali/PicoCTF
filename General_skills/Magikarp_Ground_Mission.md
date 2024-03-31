- Start the instance and connect to it using ssh.
- After loging in,run "pwd" to know the directory we are currently in, we get "/home/ctf-player/drop-in".
- List the content of directory using "ls". We see two files named "1of3.flag.txt" and "instructions-to-2of3.txt".
- Open the first file using "cat 1of3.flag.txt", there we find of our first part of flag.
- Open the second file using "cat instructions-to-2of3.txt", in there is string which tells us to go to root directory.
- Run "cd ..", to go one step down.
- Run "ls" to list the files. There we find named "3of3.flag.txt".
- Open this file using "cat 3of3.flag.txt" and there we get our third part of flag.
- Move one more step down to get to the root directory, once there run "ls" to list all files and there is file named "2of3_flag.txt'
- Open the file and there is our second part of our flag.
- <details> 
  <summary>Flag</summary>
   picoCTF{xxsh_0ut_0f_\/\/4t3r_1118a9a4}
  </details>
