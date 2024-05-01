DAILY PRACTICE CODES:

TO FIND THE AVERAGE OF SERIES IN NUMBER
sum=0 count=0 for i in range(3,11): sum+=i count+=1 avg=sum/count print(avg)

2.TO FIND RADIUS OF CIRCLE

r=3 PI=3.14 x=float(input("enter the radius=")) area=PIrr print("area of circle=",area)

3. FINDING DUPLICATE CHARACTERS USING STRING
str="akshatha" if(str!=2): print("it has duplicate") else: print("it has not duplicate")

4. TO FIND THE MARKS AND GRADE OF STUDENTS
count=0 marks=float(input("enter the marks in computer science:")) if marks> 90: print("grade: 0") elif marks>=80 and marks<90: print("grade: A+") elif marks>=70 and marks<80: print("grade: A") elif marks>=60 and marks<70: print("grade: B") elif marks>=50 and marks<60: print("grade: B+") else: print("grade:F")

5. TO FIND THE NUMBER IS PRIME
x=int(input("enter the number in prime")) if x<=2: print("num is prime") for i in range (2,x): if(x%i==0): print("num is not prime") break else: print("prime") break

 6.WITHOUT USING + OPERATOR
a=3 b=6 c=(a-(-b)) print(c)

7.REVERSE THE WITHOUT STEP INDEX

(i) a="akshatha"[::-1] print(a)

(ii) string=input() rev=str[::-1] for i in string: rev=it (rev) ptint (rev)

8. TO FIND THE PERFECT NUMBER.
n=6 out=0 for i in range (1,n//2+1): if n%i==0: out+=i if out==n: print("perfect no") else: print("not.perfect.no")

9. PRINT PATTER RIGHT TRIANGLE
rows=int(input("enter the number of rows")) for i in range(1,rows+1): for j in range (1,i+1): print(j, end="") print("")

TO PRINT THE 3X3 ROWS AND COLUMNS
n=int(input("enter the number:"))----3 for i in range(n): for j in range(n): print("*",end=" ") print()

11.TO THE 3X2 MATRICES

n=int(input("enter the number:"))---5 for i in range(n): for j in range(i-1): print("*",end=" ") print()

12.TO THE MATRIX 1X5

n=int(input("enter the number:")) for i in range(1,n+1): for j in range(1,i+1): print("*",end=" ") print()

 13.TO REVERSE THE MATRIX
n=int(input("enter the number:")) for i in range(n): for j in range(n-i): print("*",end=" ") print()

14.STAR IN I SHAPE

n=int(input()) for i in range(n): for j in range(n): if(i==0 or i==n-1): print("", end=" ") elif(n//2 == j): print("",end=" ") else: print( " " ,end=" ") print()

15.TO PUT THE MATRIX IN A SHAPE

n=int(input()) for i in range(n): for j in range(n-2): if j==0 or j== (n-2-1): print("", end=" ") elif i==0 or i==(n//2): print("",end=" ") else: print( " " ,end=" ") print()

16.FOR BENDING(A) SHAPE
n=int(input()) for i in range(n): for j in range(n-2): if i==0 and (j == 0 or j == (n-2-1)): print(" ", end=" ") elif j==0 or j==(n-2-1): print("",end=" ") elif i==0 or i==(n//2): print( "" ,end=" ") else: print(" ",end=" ") print()

17. D SHAPE *
row = int(input())

for i in range(row): for j in range(row-2): if i==0 or i== row-1 or j==0 or j==row-2-1: if (i==0 or i== row-1) and j==row-2-1: print(" ", end=" ") else: print("*", end=" ") else: print(" ", end=" ") print()

18. C SHAPE *

row = int(input())

for i in range(row): for j in range(row-2): if i==0 or i== row-1 or j==0: if (i==0 or i== row-1) and j==0: print(" ", end=" ") else: print("*", end=" ") else: print(" ", end=" ") print() 19. SHAPE OF E

row = int(input())

for i in range(row): for j in range(row-2): if j==0 or i==0 or i==row//2 or i==row-1: print("*", end=" ") else: print(" ", end=" ") print()

19. TO FIND THE FIBONACCI NUMBER IN FUNCTION
(i)def fib(number): count=0 first=0 second=1 temp=0 while count<= number: print(first) temp = first+second first = second second = temp count = count+1 fib(6)

(ii)def fibonacci(n): num1=0 num2=1 nxt_num=0 count=1 while count<=n: print(nxt_num, end=" ") count+=1 num1=num2 num2=nxt_num nxt_num=num1+num2 fibonacci(7)

(iii)n=int(input()) a=0 b=1 c=0 for i in range(1,n+1): print(c,end=" ") c=a+b b=a a=c

20. TO RETURN STRING WITH ITS COUNT

string=input() for i in string: count=0 for j in string: if(i==j): count+1 print(i,count,sep="",end="")

21.TO FIND THE FACTORIAL RECURSION

num=int(input()) def recur_factorial(n): if n == 1: return 1 else: return n*recur_factorial(n-1) print(recur_factorial(num))

22. MULTIPLY TWO NUMBERS WITHOUT USING*SYMBOL
num1=int(input()) num2=int(input()) product=0 for i in range(0,num2): product+=num1 print(product)

23. TO FIND IT IS LEAP YEAR OR NO LEAP YEAR(i)
n=int(input()) if (n%4==0): print("it is a leap year") else: print("it is not a leap year")

(ii) second option

n=int(input())

SORTING A NUMBER IN ASCENDING
n=[8,4,9,2,6,1] print(n.sort()) print(n)

24. FOR STRING COMPRESSION
def compress_string(string): compressed ="" count=1 prev_char=string[0]

for i in range(1,len(string)):
    if string[i]== prev_char:
        count+=1
    else:
        compressed += (prev_char  + str (count)) *  count
        count = 1
        prev_char = string[i]
compressed +=(prev_char + str(count)) * count
return compressed
string = input("enter the string :") compressed_string = compress_string(string) print("compressed_string", compressed_string)

25.TO CHECK THE STRING BRACKETS ARE VALID ?

def are_brackets_valid(s): list = [] for ch in s: if ch in ('(', '{', '['): list.append(ch) else: if list and ((list[-1] == '(' and ch == ')') or (list[-1] == '{' and ch == '}') or (list[-1] == '[' and ch == ']')): list.pop() else: return False return not list

expr = "{()}[]"

if are_brackets_valid(expr): print("Valid") else: print("Not Valid")

26.TO PRINT THE VOWELS IN UPPERCASE AND LOWER CASE
String=input() vowels for i in String: if(i=='a' or i=='e' or i=='i' or i=='o' or i=='u' or i=='A' or i=='E' or i=='I' or i=='O' or i=='U' vowels=vowels+1 print(vowels)

27.TO FIND THE STATEMENT IS TRUE OR FALSE

s=input().strip() req_string='' for index in s: if index.isalpha(): ` req_String+=index if index.isnumeric(): req_String+=index if req_String==req_string[::-1]: print("false") else: print("true")

To find the largest rectangle containing only 1's and return its area.
def maximalRectangle(matrix): if not matrix or not matrix[0]: return 0

rows, cols = len(matrix), len(matrix[0])
heights = [0] * cols
max_area = 0

for row in range(rows):
    for col in range(cols):
        if matrix[row][col] == "1":
            heights[col] += 1
        else:
            heights[col] = 0


    max_area = max(max_area, largestRectangleArea(heights))

return max_area
def largestRectangleArea(heights): stack = [] max_area = 0

for i, height in enumerate(heights + [0]):
    while stack and heights[stack[-1]] >= height:
        h = heights[stack.pop()]
        w = i if not stack else i - stack[-1] - 1
        max_area = max(max_area, h * w)
    stack.append(i)

return max_area
matrix = [["1", "0", "1", "0", "0"], ["1", "0", "1", "1", "1"], ["1", "1", "1", "1", "1"], ["1", "0", "0", "1", "0"]] print(maximalRectangle(matrix))

28. Given an m x n matrix, return all elements of the matrix in spiral order.

def spiral_order(matrix): result = [] if not matrix: return result top, bottom, left, right = 0, len(matrix) - 1, 0, len(matrix[0]) - 1 while top <= bottom and left <= right: result.extend(matrix[top][left:right+1]) top += 1 for i in range(top, bottom + 1): result.append(matrix[i][right]) right -= 1 if top <= bottom: for i in range(right, left - 1, -1): result.append(matrix[bottom][i]) bottom -= 1 if left <= right: for i in range(bottom, top - 1, -1): result.append(matrix[i][left]) left += 1 return '[' + ','.join(map(str, result)) + ']'

matrix = [[1, 2, 3], [4, 5, 6], [7, 8, 9]] print(spiral_order(matrix))

Given an integer columnNumber, return its corresponding column title as it appears in an Excel sheet.
ef convert_to_title(columnNumber): title = "" while columnNumber > 0: columnNumber -= 1 remainder = columnNumber % 26 title = chr(65 + remainder) + title columnNumber //= 26 return title

try: input_str = input() columnNumber = int(input_str.split("=")[-1].strip()) if columnNumber < 1: raise ValueError() except ValueError as ve: print(ve) else: excel_title = convert_to_title(columnNumber) print(f'"{excel_title}"')
