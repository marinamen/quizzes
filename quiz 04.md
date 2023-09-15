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

<img width="1145" alt="Screenshot 2023-09-11 at 21 01 35" src="https://github.com/marinamen/quizzes/assets/142757957/4e9baae5-57ec-457c-b461-c5d0c41d56b1">

#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![quiz4](https://github.com/marinamen/quizzes/assets/142757957/fc69f13f-13d0-4365-92fd-808e8dfe5c69)
