# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.
### Step 2: 
 Using keyword "with" to open the requied file.
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The four function is used to take each line from the main file.
### Step 6: 
The four function is used to take each line from the main file.

## PROGRAM:
```
#Developed by: M.Jayachandran
#Reference No: 22008847
fname=input("Enter file name: ")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words)
```
            
 ### OUTPUT:
![hi](https://user-images.githubusercontent.com/118447015/214826639-857e13db-86af-42f8-8c67-0929fcce1f15.jpg)


![wc](https://user-images.githubusercontent.com/118447015/214829644-98de8ff5-aa3d-478d-a635-ab2a02dc0c9f.jpg)



## RESULT:
Thus the program is written to find the word count from a text.
