# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Open terminal and activate conda, then open jupyter notebook.

## Step 2:
Create a text file in jupyter notebook or upload a text file in the jupyter notebook.

## Step 3:
Open a new cell in jupyter notebook.

## Step 4:
Type the program in the cell.

## Step 5:
Now in the output box,type the file name.

## Step 6:
End the program.

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
