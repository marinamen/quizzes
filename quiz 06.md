**QUIZ 06**˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
6. A hotel has 10 floors and 10 rooms on each floor. Write a program that prints the names of all rooms.

#code

    room_number = int(input("Enter a room number (1-100): "))
    def print_roomlocation(room_number):
        if 1 <= room_number <= 100:
            floor = (room_number - 1) // 10 + 1
            room_on_floor = (room_number - 1) % 10 + 1
            room_location = f"{floor}-Room {floor}F{room_on_floor:02}"
            print(room_location)
        else:
            print("error,please enter a room number between 1 and 100.")
    
    print_roomlocation(room_number)
#proof/test˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦


![](https://github.com/marinamen/quizzes/blob/main/pictures/Screenshot%202023-09-11%20at%2021.21.31.png)




#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

#missing a input before the main code start: 
room int input:

![](https://github.com/marinamen/quizzes/blob/main/pictures/hotel.png)
