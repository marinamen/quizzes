**QUIZ 016** 　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦


16. Create a function that produces the average world length of the input list


#code
```.py
def averageLength(words:list)->float:
    count=0
    word=len(words)
    for w in words:
        count+= len(w)
        for i in w:
            if i == " ":
                count-=1
        
    average=count/word
    return float(average)

out = averageLength(words= ["Computer Science","Art"])
print(out)
```

#test　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/quizzes/blob/main/pictures/Screen%20Shot%202023-10-10%20at%209.57.56.png)
![](https://github.com/marinamen/quizzes/blob/main/pictures/Screen%20Shot%202023-10-10%20at%209.58.05.png)


#flowchart　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
   
