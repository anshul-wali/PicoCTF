- Download the file.
- Open the file using 'cat enc_flag'. This looks like a base64 encoded data.
- We can decode the data by pasting using cyberchef or "cat enc_flag | base64 -d". The data seems to be encoded multiple times in base64, so we have to decode it 
  multiple times by running the same command till we get the flag.
- <details> 
  <summary>Flag</summary>
   picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_9b59b35c}
  </details>
