# Python-Problems

Problem 1 (mad libs)

location = input("Enter in a fun place:")
print("I love going to the " + location)

occupation = input("Enter in your dream occupation:")
print("One day I want to be a " + occupation + "so I can make lots of money")

color = input("Enter in a color:")
print("The color " + color + "is my favorite")

Problem 2 (odd counter)
index = 1
while (index <= 10):
    if index % 2  == 1:
     print(index)
    index +=1

Problem 3 (fibonacci)

n1 = 0
n2 = 1

nth = 0
count = int(input("Enter a range for fibonacci"))
while nth <= count:
    print(n1)
    n3 = n1 + n2
    n1 = n2
    n2 = n3
    
    nth +=1

    Problem 4 (password strength checker)
