**QUIZ 04**˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
4. Given a number, create a program that produces the output factors.

#code

    number = int(input("enter a integer: "))
    if number <= 0:
        print("enter a integer.")
    else:
        factors = [i for i in range(1, number + 1) if number % i == 0]
        sumf=sum(factors)
        print("Factors of", number, "are:", factors)
        if len(factors) >= 3:
            print(number,"true")
        else:
            print(number,"false")

#proof/test˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/quizzes/blob/main/pictures/Screenshot%202023-09-11%20at%2021.01.35.png)

#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/quizzes/blob/main/pictures/quiz4.jpg)
