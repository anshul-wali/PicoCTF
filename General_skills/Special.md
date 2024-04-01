- Login using ssh into the instance.
- It took a lot of time to try different syntax. I found that ''cat'' works but this did not work when I passed the file as a argument like ''cat file_name''. 
  After trying some more different syntaxes, I again came back to this syntax and I found that `''cat'' ''file_name''` works.
- I listed the content using `''ls''` and found a directory named 'blargh'.
- I tried to `cd` into the blargh but it did not work, so I tried a different way to list the contents of this directory. 
- To list it's content I ran `''ls'' ''blargh''`. I found a file named `flag.txt`.
- To print the content of this file I ran `''cat'' ''blargh/flag.txt''`.
- <details> 
  <summary>Flag</summary>
   picoCTF{5p311ch3ck_15_7h3_w0r57_3befb794}
  </details>
