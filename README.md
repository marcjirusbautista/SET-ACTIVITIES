# SET-ACTIVITIES

#Activity 1 Remove Duplicates

numbers = [1,2,2,3,4,4,,5]
unique_numbers = set(numbers)
print(unique_numbers)

#Activity 2 Add and Remove

fruits = {"watermelon", "tomato"}
fruits.add(" grapes")
fruits.remove("tomato")
print(fruits)

#Activity 3 Set operation


A = {1, 2, 3}
B = {3, 4, 5}

print(A | B)
print(A & B)

#Activity 4 Common students

classA = {"Esto", "Aquino", "Marcial"}
classB = {"Bautista", "Esto", "Ferido"}

print(classA & classB)
print(classA | classB)
