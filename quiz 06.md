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
#missing a input before the main code start: 
room int input:

![IMG_9895](https://github.com/marinamen/quizzes/assets/142757957/f7c2e3ab-2211-45ba-91ef-15071bed0b86)



#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

<img width="1160" alt="Screenshot 2023-09-11 at 21 21 31" src="https://github.com/marinamen/quizzes/assets/142757957/17c7b6e6-c910-44f5-b8f2-0239d9112206">
