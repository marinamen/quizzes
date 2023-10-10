**QUIZ 015** 　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦


15. There are N closed doors in a school and N students present. The first student opens each door. The second student flips (open⇆close) every second door. The third student flips every third door, and so on. 


#code

```.py
def open_doors(students):
    count=0
    doors = [False] * students
    for student in range(1, students + 1):
        for door in range(student - 1, students, student):
            doors[door] = not doors[door] 

    opendoors = [i + 1 for i, is_open in enumerate(doors) if is_open]
    for n in opendoors:
        count+=1
    return count
  
students=100
out = open_doors(students)
print("Doors open after",students ," students:",out)
```

#test　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/quizzes/blob/main/pictures/Screen%20Shot%202023-10-10%20at%2010.15.24.png)
![](https://github.com/marinamen/quizzes/blob/main/pictures/Screen%20Shot%202023-10-10%20at%2010.15.16.png)

#flowchart　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
