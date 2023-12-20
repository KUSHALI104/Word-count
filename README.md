# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
instalize the value for count as zero 
### Step 2: 
 using open command open the txt file to read
### Step 3: 
use the split() command
### Step 4:  
print the counted words
### Step 5: 
end the program


## PROGRAM:
'''
```
Developed by:vellachi tilak
Registered number: 2122232340172
'''
num_words=0
with open('text.txt','r') as f1:
    for i in f1:
        word=i.split()
        num_words += len(word)
print("Number of words in the file = {}".format(num_words))
```


### OUTPUT:
![Screenshot 2023-12-20 192905](https://github.com/KUSHALI104/Word-count/assets/150231135/a1119e68-4720-498e-8d43-8369903a2b22)
![Screenshot 2023-12-20 193013](https://github.com/KUSHALI104/Word-count/assets/150231135/4964ff4a-de37-4e51-93ce-4cec929084e9)





## RESULT:
Thus the program is written to find the word count from a text.
