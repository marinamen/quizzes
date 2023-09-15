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
<img width="614" alt="Screenshot 2023-09-11 at 22 31 35" src="https://github.com/marinamen/quizzes/assets/142757957/0bc1aec3-debf-47eb-b78d-7b579418b262">



#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![IMG_1467](https://github.com/marinamen/quizzes/assets/142757957/d3eb2ea6-430b-4f4f-904f-384f83af9609)
