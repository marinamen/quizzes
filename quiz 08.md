**QUIZ 08**˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

8. Create a function that receives as input a string and returns the string ciphered with shift 13.
 
#code
    
    def cipher(user_string, shift):
        result = ""
        for char in user_string:
            if char.isalpha():
                upper = char.isupper()
                char = char.lower()  # Convert to lowercase for easier manipulation
                shiftchar = chr(((ord(char) - ord('a') + shift) % 26) + ord('a'))
                if upper:
                    shiftchar = shiftchar.upper()
                result += shiftchar
            else:
                result += char
        return result
    
    user_string = input("enter: ")
    shift = int(input("enter shift: "))
    
    ciphered = cipher(user_string, shift)
    print("ciphered string:", ciphered)


#proof/test˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦


![](https://github.com/marinamen/quizzes/blob/main/pictures/Screenshot%202023-09-12%20at%2000.16.42.png)




#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/quizzes/blob/main/pictures/08.png)
