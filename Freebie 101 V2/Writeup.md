The challenge had a hint published that said "Author: what do you know about me?".  
This clearly hinted to search me, in this case my socials to get to the challenge. If you get to my linkedin you can get to my github and there in the Teknofest CTF writeups repository you can find a challenge "Freebie 101".  
The flag of this challenge was the password for the zip file. In the zip there is a word file with some wierd symbols and a text file with another hint. The hint actually points towards a form of subtitution cipher called nyctography.  
Then you just copy the symbols and paste them in dcode.fr/en and get a hex. Then you just have to decode it from hex to get the flag.
### Flag
```diff
STC{t00_easy}
```
