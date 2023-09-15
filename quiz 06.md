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

<img width="1160" alt="Screenshot 2023-09-11 at 21 21 31" src="https://github.com/marinamen/quizzes/assets/142757957/d13d1b70-5d21-4a98-bc34-5626cbe4ba73">





#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

<img width="922" alt="Screenshot 2023-09-15 at 10 37 46" src="https://github.com/marinamen/quizzes/assets/142757957/26b333cf-4ad0-43ba-b07e-a02cc5011a4c">
