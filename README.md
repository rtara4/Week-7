# Week-7
f = open('marks.txt','wt')
mark = []
total = 0
student_marks = int(input('Enter Number of student marks: '))

print("Enter Marks Obtained in " + str(student_marks) + " Subjects: ")
for student in range(student_marks):
    mark.append(input()) 
print(mark)
string = ','.join(mark)
print(string)
f.write(string)
f.close()
