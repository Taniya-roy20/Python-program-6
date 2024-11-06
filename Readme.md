# Program 6: WAP to swap the first n characters of two strings.
code= str1 = input("enter first string: ")
<br>
str2 = input("enter second string: ")
<br>
n1 = int(input("enter no of character which is to be swap:"))
<br>
n = str1[ :n1]
<br>
m = str2[ :n1]
<br>
if n1 <= min(len(str1),len(str2)):
<br>
    print(str1.replace(n,m))
    <br>
else:
<br>
    print(str2.replace(m,n))
![6](https://github.com/user-attachments/assets/8adf5088-e075-4dcf-807d-5fee2166ae7c)
![image](https://github.com/user-attachments/assets/029aebf5-227b-4357-8982-c0c658e567ad)

