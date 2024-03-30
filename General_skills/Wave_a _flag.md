- wget https://mercury.picoctf.net/static/b28b6021d6040b086c2226ebeb913bc2/warm     
- "ls -la" to see the downloaded files permissions, the Executable file has only read and write perms. We need to run the exe file, we can do that by adding the 
  execute perm.
- Run "chmod +x warm", now the file is executable.
- Run "./warm" to execute the file. It gives the following output "Hello user! Pass me a -h to learn what I can do!"
- After running "./warm -h" the command we get the following output "Oh, help? I actually don't do much, but I do have this flag here: " and we have out flag.
- <details> 
  <summary>Flag</summary>
   picoCTF{b1scu1ts_4nd_gr4vy_d6969390}
  </details>
