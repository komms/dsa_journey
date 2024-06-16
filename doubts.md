# Doubts
1. Questions have 2 to 3 methods to solve it i am doing the answers in the easy way then what about the remaining methods to solve the same question.

2. Does python has long data type like in c language.

3. a = int(input("Enter a number")) for the code what if the number is very much higher.

4. num = input("enter a number")
print(type(num)) 2
<class 'str'>
The output of the above small code is string because i have not specified the int keyword but when i specify the int keyword it is taking the input as integer why can not it auto assign the input as integer like it assigned the input as string.

5. num = int(input("Enter how many numbers")) 
sum = ((num)*(num+1))/2
print(sum)
I have got an error saying sum is not an callable object but now i am not getting the error.

6. num = 5
sum = 0
for i in range(num+1):
  sum+=i
print(sum) this is giving correct answer for sum of first n natural number 
But 
num = int(input("Enter how many numbers"))
sum = 0
for i in range(num+1):
    given = (int(input("Enter the numbers")))
    sum+= given
print(sum)
Enter how many numbers5
Enter the numbers1
Enter the numbers2
Enter the numbers3
Enter the numbers4
Enter the numbers5
Enter the numbers5
20
But why is this asking one time more if i gave the same range of num+1

7. why can not we use & as a and operator

8. Got confused at prime number questions and seen the anwer step after step and solved it.

9. doing mistakes like taking i instead of num in prime number code

10. low,high = 2,10
primes = []
for i in range(low,high+1):
    flag = 0
    if i<2:
        continue
    if i ==2:
        primes.append(2)
        continue
    for x in range(2,i):
        if i%x==0:
            flag=1
            break
    if flag==0:
        primes.append(i)
print(primes) 
Did not understand the above some operatiions.

11. Why are there mulitple if loops line by line but there is not a elif after if loop.

12. I did not understand how the above code is running i mean i did not understand the navigation of the code of where it is going first 

13. #sum of digits of a number
a = input("Enter a number")
sum = 0
for i in a:
    sum = sum + int(i)
    
print(sum)
Did not understand how this has worked.

14. number = 371
num = number
digit, sum = 0, 0
length = len(str(num))
for i in range(length):
  digit = int(num%10)
  num = num/10
  sum += pow(digit,length)
if sum==number:
  print("Armstrong")
else:
  print("Not Armstrong")
Did not understand the above code.

15. Did not understadn the below code
 def Prime_Factorial(n):
    if n < 4:
        return n
    arr = []
    while n > 1:
        for i in range(2, int(2+n//2)):
            if i == (1 + n // 2):
                arr.append(n)
                n = n // n
            if n % i == 0:
                arr.append(i)
                n = n // i
                break
    return arr


n = 210
print(Prime_Factorial(n))

