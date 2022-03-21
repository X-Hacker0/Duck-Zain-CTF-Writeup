## Zain_CTF
### Duck-Digital-Forensic-Writeup

Hello guys, I have completed this challenge. In my personal opinion, this challenge was of medium difficulty... Let me tell you how it was done.

At first I used "file , strings and exiftool" Commands ,  but I didn't get a result, so I thought about the name of the attached file in the challenge and searched for it, and I knew that this file is a USB Rubbery Ducky

After searching, I found this useful <a href="https://www.ducktoolkit.com/decode">site</a> to decrypt the file :
After decrypting this file, we got this file with the name : "duckeycode.txt" , And it contains this command :

![image](https://user-images.githubusercontent.com/95540609/159368522-2be901da-4e23-4b64-be2e-2704f38944a9.png)

After This I changed this symbol ~ this |  ,in The Command .

After I run the command in termenal i got a python file named : environ-74399.py
i was open this file and i saw the python code , I noticed that the code contains this URL : 

![image](https://user-images.githubusercontent.com/95540609/159370516-357765ea-4195-4c7c-a642-7c6c3f1dde59.png)

I got this page :
![image](https://user-images.githubusercontent.com/95540609/159372015-4c0c1d0f-ed8e-4955-a99b-f537940afb11.png)

#### here ! I tried very hard to know this type of cipher, so it occurred to me to convert every "X" letter to 1 and every "x" letter to 0
Here I needed to write a basic Python code to convert from x, X to numbers 0, 1 ..... this is the python code i used :
![image](https://user-images.githubusercontent.com/95540609/159373766-3e4af279-8083-40bf-9555-7f8414d81254.png)
Now, we must decode these output  until we Capture The Flag 💪🏼⛳️
haha this is very nice idea ;) 


