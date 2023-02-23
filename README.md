#3
a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]
for x in a:
    if x < 5:
        print(x)

print([x for x in a if x < 5])

numbers = [6678, 57, 1396, 654, 869, 54, 107, 246, 497, 15, 986, 104, 123, 14876, 11]
lessFnums = []
lessNnums =[]

for num in numbers:
    if num < 5:
        lessFnums.append(num)
        lessFnums.sort()
print(lessFnums)
num = int(input("Enter a number: "))

for n in numbers:
    if n < num:
        lessNnums.append(n)
        lessNnums.sort()
print(lessNnums)
#5
a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]
b = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13]
print(set(a[x] for x in range(len(a))if a[x] in b))
#6
a = []
b = []

usrstr = input('Choose a word : ')

for i in usrstr:
 a.append(i)
 b.append(i)

b = b[::-1]

if a == b:
 print('It\'s a palindrome!')

else:
 print('Not a palindrome!')
#7
a = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
even_list = [num for num in a if num%2==0]
print(even_list)
#10
import random
a = random.sample(range(1, 10), 7)
b = random.sample(range(1, 15), 10)

one_list = list(dict.fromkeys(a + b))
one_list.sort()
print(one_list)
#12
l = int(input("length : "))
b = []
i = 1
while i <= l:
 a = int(input(" "))
b.append(a)
i = i+1
print(b)
c = []
c.append(b[0])
c.append(b[-1])
print(c)
#14
First_list = [1, 1, 2, 3, 4, 5, 6, 6, 7, 8, 9]
New_list = []
for i in First_list:
 if i not in New_list:
  New_list.append(i)
print(First_list)
print(New_list)
