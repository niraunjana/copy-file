# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
 Initially make count = 0
### Step 3: 
Open the content file using command line arguments.
### Step 4:  
By using for loop name the function as "line"
### Step 5: 
Split the line using .split
### Step 6: 
Split the line using .split
## PROGRAM:
```
## Developed by: NIRAUNJANA GAYATHRI G R
## RegisterNumber: 22008369

with open ("text.txt") as fp:
  with open("file.txt","w") as fp1:
    line= fp.read()
    fp1.write(line)
    
 ```
   

### OUTPUT:

![WhatsApp Image 2023-01-26 at 16 19 56](https://user-images.githubusercontent.com/119395610/214818319-32962c3d-a088-4a20-9591-1ad740755813.jpg)
![WhatsApp Image 2023-01-26 at 16 20 17](https://user-images.githubusercontent.com/119395610/214818381-f26f9425-463d-423c-94f2-f2d39ee9fa8e.jpg)
![WhatsApp Image 2023-01-26 at 16 20 36](https://user-images.githubusercontent.com/119395610/214818435-9e2231b5-2183-4b3a-92cb-355fe1b2dce2.jpg)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
