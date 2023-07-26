# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a text file
### Step 2: 
read the text file
### Step 3: 
Copy the file using write mode
### Step 4:  
End the program.

## PROGRAM:
```
#to copy file
#Developed by : MALLIGESH M
#Register number : 23002936


from google.colab import drive
drive.mount('/content/drive')

with open('/content/drive/My Drive/python/python.txt','r') as f:
  text=f.read()
with open('/content/drive/My Drive/python/p1.txt','w') as g:
  g.write(text)

```


### OUTPUT:

![output](/pr.png)
![output](/out.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.