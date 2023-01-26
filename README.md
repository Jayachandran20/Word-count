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
#Reference no: 22008847
with open('file.txt','r') as f1:
    with open('file2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
            
 ### OUTPUT:
![hi](https://user-images.githubusercontent.com/118447015/214826639-857e13db-86af-42f8-8c67-0929fcce1f15.jpg)


![hello](https://user-images.githubusercontent.com/118447015/214826777-933e522f-e65d-48ae-846b-09da8882402d.jpg)



## RESULT:
Thus the program is written to find the word count from a text.
