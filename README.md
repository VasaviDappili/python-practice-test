# python-practice-test

## 1.Write a Python program which accepts a sequence of comma separated 4 digit binary numbers as its input and then check whether they are divisible by 5 or not.
### The numbers that are divisible by 5 are to be printed in a comma separated sequence.Example:0100,0011,1010,1001Then the output should be:1010
## Code:
```
numbers = input().split(",")

result = []

for num in numbers:
    if int(num, 2) % 5 == 0:
        result.append(num)

print(",".join(result))
```
## output:
<img width="1600" height="900" alt="WhatsApp Image 2026-09-23 at 9 32 40 PM" src="https://github.com/user-attachments/assets/ee7f398b-af29-42f4-b084-b6391ddeb474" />

## 2.Write a Python program that accepts a sentence and calculate the number of letters and digits.
### Suppose the following input is supplied to the program: hello world! 123 Then, the output should be: LETTERS 10 DIGITS 3
## Code:
```
sentence = input()

letters = 0
digits = 0

for ch in sentence:
    if ch.isalpha():
        letters += 1
    elif ch.isdigit():
        digits += 1

print("LETTERS", letters)
print("DIGITS", digits)
```
## Output:
<img width="1600" height="900" alt="WhatsApp Image 2026-09-23 at 9 35 07 PM" src="https://github.com/user-attachments/assets/8f2589f5-a4ea-4d1b-a812-218ce23ace35" />

## 3.Write a program which can compute the factorial of a given numbers.
### The results should be printed in a comma-separated sequence on a single line.Suppose the following input is supplied to the program:8 Then, the output should be:40320
## Code:
```
n = int(input())

factorial = 1

for i in range(1, n + 1):
    factorial = factorial * i

print(factorial)
```
## Output
<img width="1600" height="900" alt="WhatsApp Image 2026-09-23 at 9 39 57 PM" src="https://github.com/user-attachments/assets/97089da6-6679-4d54-bfa9-8291afd12bbf" />
