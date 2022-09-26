# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 

### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
num_words=0
with open('myfile.txt','r') as f1:
    for i in f1:
        word=i.split()
        num_words += len(word)
print('number of words={}'.format(num_words))

### OUTPUT:
![Screenshot from 2022-09-26 13-33-16](https://user-images.githubusercontent.com/113497680/192228289-d78b6fa1-ee6a-407d-ba47-3bd7ad0a6cbe.png)
![Screenshot from 2022-09-26 13-43-29](https://user-images.githubusercontent.com/113497680/192228344-5837a292-9373-4e0a-8390-4837f7bb1c42.png)

## RESULT:
Thus the program is written to find the word count from a text.
