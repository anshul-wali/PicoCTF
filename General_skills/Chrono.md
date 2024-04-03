- Lauch the instance and open terminal to login on ssh using the credentials given.
- This CTF is related to cron jobs which is used to automate tasks on linux whose hint is given in the title "chron" and description "How to automate 
  tasks to run at intervals on linux servers?". All the cron jobs are handled using corntab. Also, cron jobs need to be added in the /etc directory.
- We will now change our directory to `cd /etc`.
- List the files in this directory using `ls`. We can see files name that start with cron, after trying opening them we got our flag in "crontab" file using 
  `cat corntab`. 
- <details>
  <summary>Flag</summary>
   picoCTF{Sch3DUL7NG_T45K3_L1NUX_1d781160}
  </details>

