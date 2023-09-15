**QUIZ 05**˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
5. Given a string, create a program that produces the sum of the characters in the string.

#code

    def letter_sum(text:str)->int:
        abc="abcdefghijklmnopqrstuvwxyz"
        total=0
    
        for let in text.lower():
            index= -1
            for i in range(len(abc)):
                if let == abc[i]:
                    index = i + 1
                    total += index
        return total
    case1 = letter_sum(text="Math")
    print(case1)

#proof/test˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/quizzes/blob/main/pictures/Screenshot%202023-09-11%20at%2022.31.35.png)


#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/quizzes/blob/main/pictures/letter%20sum.png)
