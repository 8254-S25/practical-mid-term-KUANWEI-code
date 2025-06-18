**Your Name:** Kuanwei

**1.**

```
scp C:\Users\OO7Ag\Desktop\kuanwei.txt pi@10.0.0.27:~
```

**2. What command do you use to see a directory listing that includes the permissions of the files?**

```
ls -l
```

**3.**

```
ls -l > pr1.txt
```

**4. What are the permissions of the file you just created?**

```
-rw-r--r-- 1 pi pi 513 Jun 18 17:53 pr1.txt
```

**5. What command do you use to display the folder you are currently working from?**

```
pwd
```

**6.**

```
chmod 701 kuanwei.txt
```

**7.**

```
mkdir midtermExam-301
```

**8. What are the permissions of this new folder?**

```
drwxr-xr-x 2 pi pi 4096 Jun 18 17:57 midtermExam-301
```

**9. What command do you use to list the ports your raspberry pi is listening to? Try it using the `-at` flag.**

```
netstat -at
```

**10.**

```
netstat -at > pr2.txt
```

**11.**

```
sftp pi@10.0.0.27
```

**12.**

```
put C:\Users\OO7Ag\Desktop\midtermPi.txt
```

**13. What does the command do?**

```
This command writes the current working directory path to mt.txt file, then appends the directory tree structure to pr.txt file
```

**14.**

```
sudo useradd kuanwei
```

**15.**

```
sudo mkdir /home/kuanwei
sudo chown kuanwei:kuanwei /home/kuanwei
```

**16.**

```
sudo apt-get update
sudo apt-get install filezilla
```
