## EX NO 04(a)

## Aim:
Print the value of the key 'history' from the given dictionary.
sampleDict = { "class": { "student": { "name": "Mike", "marks": { "physics": 70, "history": 80 } } } }

## Algorithm:
Step 1: Start the progream. <br>
Step 2: Create a dictionary. <br> 
Step 3: To print the 'history' we have give like 'sampleDict["class"]["student"]["marks"]["history"]' }. <br> 
Step 4: End the program. <br>

## Program:
```
sampleDict = { "class": { "student": { "name": "Mike", "marks": { "physics": 70, "history": 80 } } } }
print(sampleDict["class"]["student"]["marks"]["history"])
```

## Output:

<img width="1190" height="215" alt="Screenshot 2025-12-28 124027" src="https://github.com/user-attachments/assets/9bedf039-04e8-4575-a6fb-d1eb5879d0d3" />

## Result:
The program is executed successfully.

## EX NO 04(b)

##Aim:
Write a program to check whether a given key exists in a dictionary or not. <br>
Hint: <br>
Given dict = {‘0’:1, ‘1’:2, ‘2’:3} <br>

## Algorithm:
Step 1: Create a dictionary. <br> 
Step 2: Get the input. <br>
Step 3: Check if the value is present in the dictionary or not. <br> 
Step 4: If present then print true, if not then print false. <br>
Step 5: End the program. <br>

## Program:
```
dict = {'0': 1, '1': 2, '2': 3}
value = int(input())
if value in dict.values():
    print("True")
else:
    print("False")
```

## Output:

<img width="1186" height="304" alt="Screenshot 2025-12-28 124644" src="https://github.com/user-attachments/assets/e97e4c6f-1eef-4564-88af-639cae8a94b9" />

## Result:
The program is executed successfully.

## EX NO 04(c)

## Aim:
Write a python program that asks the user to enter an integer n and return a dictionary whose keys are integers 1, 2, 3, ... n and whose values ​​are 1! , 2! , 3! , … , n!

## Algorithm:
Step 1: Get the input and create a empty dictionary. <br> 
Step 2: For each number i from 1 to n − 1, Set s = 1 <br>
Step 3: For each number j from 1 to i, Multiply s by j. <br>
Step 4: Store s as the value for key i in dictionary d. <br>
Step 5: Display the dictionary. <br> 

## Program:
```
n=int(input())
d=dict()
s=1
for i in range(1,n):
    for j in range(1,i+1):
        s*=j
    d[i]=s
    s=1
print("The obtained dictionary is d = ",d)
```

## Output:

<img width="1279" height="282" alt="Screenshot 2025-12-28 125313" src="https://github.com/user-attachments/assets/034cf5d2-afe0-42f1-97b6-3555ce575b48" /> 

## Result:
The program is executed successfully.

## EX NO 04(d)

## Aim:
Write Python Program to take the radius from the user and find the area of the circle using class name 'saveetha' and function name 'slot'.

## Algorithm:
Step 1: Define a class named saveetha. <br>
Step 2:Define a method fun that accepts radius r. <br>
Step 3:Read the value of r. <br>
Step 4:Create an object of the class saveetha. <br>
Step 5:Call the method fun using the object and pass r. <br>
Step 6:Calculate the area of the circle using the formula π×r×r. <br>
Step 7:Display the area of the circle. <br>

## Program:
```
class saveetha:
    def fun(self, r):
        radius=3.1416*r*r
        print("Area of circle:",radius)
r=int(input())
a=saveetha() 
a.fun(r)  
```

## Output:

<img width="1262" height="278" alt="Screenshot 2025-12-28 125927" src="https://github.com/user-attachments/assets/6679ab37-81ae-4f56-8580-39d82f663510" />

## Result:
The program is executed successfully.

## EX NO 04(e)

## Aim:
Write a python program to find perimeter of a circle using class name 'laptop'  and function name 'dell'.

## Algorithm:
Step 1: Define a class named laptop
Step 2: Define a method dell that takes radius r as input
Step 3: Read the value of r
Step 4: Create an object of the class laptop
Step 5: Call the method dell using the object and pass r
Step 6: Calculate the perimeter of the circle using the formula 2 × π × r
Step 7:Display the perimeter of the circle

## Program:
```
class laptop:
    def dell(self,r):
        perimeter=2*3.1416*r
        print(f"Perimeter of circle: {perimeter:.2f}")
r=int(input())
a=laptop()
a.dell(r) 
```

## Output:

<img width="1283" height="270" alt="Screenshot 2025-12-28 130149" src="https://github.com/user-attachments/assets/8c57c7b2-2fa3-4fdc-b81b-4ee94b90631b" />

## Result:
The program is executed successfully.
