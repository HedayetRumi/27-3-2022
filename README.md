#sum of a number

n = 10
count = sum(range(1, n + 1))
print("Total sum of ", n, " is ", count)


#sum of a list by using built in sum fucntions

list = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100]
count= 0
count = sum(list)
print("Sum of total number is ", count)


#sum of a list by using loop
list = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100]
count = 0
for i in list:
    count = count + i  #count+=i
print("Sum of this list is", count)
