- 👋 Hi, I’m @Narsi9176
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Narsi9176/Narsi9176 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Python
1a). Students test marks for each course is considered as the best of two test average marks out of three test’s 
marks, implement a python program to find the test average marks, take input from the user.
Solution:
m1 = int(input("Enter the marks in the first test: "))
m2 = int(input("Enter the marks in second test: "))
m3 = int(input("Enter the marks in third test: "))
if (m1 > m2):
 if (m2 > m3):
 total = m1 + m2
 else:
 total = m1 + m3
elif (m1 > m3):
 total = m1 + m2
else:
 total = m2 + m3
Avg = total / 2
print("The average of the best two test marks is: ", Avg)
output:
Case 1:
Enter the marks in the first test: 20
Enter the marks in the second test: 15
Enter the marks in the third test: 22
The average of the best two test marks is: 21.0
Case 2:
Enter the marks in the first test: 20
Enter the marks in the second test: 23
Enter the marks in the third test: 18
The average of the best two test marks is: 21.5
Case 3:
Enter the marks in the first test: 15
Enter the marks in the second test: 20
Enter the marks in the third test: 21
The average of the best two test marks is: 20.5
