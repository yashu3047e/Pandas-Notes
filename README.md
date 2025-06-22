# Pandas-Notes

C:\Users\Yash\Desktop\python codes\Starting today\Practicalfile.py

# # Q1

import pandas as pd

# Creating a Series with scalar value 5 repeated 5 times
s = pd.Series(5, index=[0, 1, 2, 3, 4])
print(f"Series with scaler value 5 :\n{s}")

# Q2

import pandas as pd

# Creating a dictionary with house names and student counts
data = {
    'Raman': 34,
    'Rishi': 0,
    'Dikshant': 69,
    'Happu': 1,
    'Abhinandan':100
}

# Creating Series using the dictionary
house = pd.Series(data)

# Displaying the Series
print(f"Number of students in each house (Class 12B):\n {house}")

# Question 3

import pandas as pd 
c = pd.Series([30,25,20,2], index=["Keyboard (KB)","Mouse","Computer","Printer"])
print(f"The Quantity Of computer items available in labs are :\n{c}")

#Question 4

import pandas as pd 
data = {
    'Rishi' : 74,
    "Rahul" : 80,
    "Yash" : 99,
    "Disha" : 98,
    'Rohan' : 2,
    "Dikshant" : 59
}

result = pd.Series(data)
print(result[result>75])

#Question 5 

'''Write python program to create series and display
various attribute of the Series .'''

import pandas as pd 
d = pd.Series(['Rishi',43,'Yash',34,565,787,34])
print(f"The List Of the series are :\n {d}")

print(f"Index : {d.index}")
print(f"Shape : {d.shape}")
print(f"Datatype : {d.dtype}")
print(f"Values : {d.values}")
print(f"size : {d.size}")

#Question 6 

import pandas as pd
data = {
    'Admno' : [101,102,103],
    "Name" : ['Rishi','Dikki','Yash'],
    'Percentile': [98,95,96]
}

df = pd.DataFrame(data)
print(f"The Details :\n {df}")

#Question 7 

import pandas as pd 
data = {
    'Name' : ['Nancy Drew','Hardy Boys', 'Diary od a wimpy kid','Harry potter'],
    'Price' : [150,180,225,500]
}

df = pd.DataFrame(data)
print(f"Stock :\n{df}")

#Question 8 

import pandas as pd
data = {
    'city' : ['Delhi',"Bengluru","Chennai","Mumbai"],
    'Max-temp': [35,31,25,36.2],
    "Min-temp" : [26,35,27,40.8],
    "Rainfall" : [24.1,36.2,40.8,35.2]
}
df = pd.DataFrame(data)
print(f"The Following CSV file :\n {df}")

# Question 9

import pandas as pd
data = {
    'PCD' : ['PO1',"P02","P03","P04"],
    'Tittle': ['Notebook','Pencilbox','Waterbottle','schoolbag'],
    "Price" : [85,76,129,730],
    "Qty" : [500,200,50,70]
}
df = pd.DataFrame(data)

df['Grade']=['A','B','C','D']
print(df)

# Question 10




