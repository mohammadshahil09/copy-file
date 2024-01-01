# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

Step 2:
Read the file and store in a variable

Step 3:
Now create a new file in which we want to paste the content using access mode.

Step 4:
Use write function to copy the read file that has been stored in the variable.

Step 5:
The content in the original file will be copied in the newfile

Step 6:
End the program

## PROGRAM:
```
#program to copy the content of one file to the other
#developed by: guntur shaik mohammad shahil
#register number: 212223240044
with open('pythonfile.txt') as f:
    with open("text1.txt",'w') as f1:
        for line in f:
         f1.write(line)
```
### OUTPUT:

![image](https://github.com/hariharana59/copy-file/assets/144980130/f3d2b74f-a9b2-40a4-90c1-7a7554e94722)

![image](https://github.com/hariharana59/copy-file/assets/144980130/3370d3b6-3b98-4eb0-acee-e3ea9747c6be)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
