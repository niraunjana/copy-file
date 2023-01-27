# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.
### Step 2: 
 Read the file and store in a variable
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.
### Step 4:  
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
The content in the original file will be copied in the new file.
### Step 6: 
End the program.
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
