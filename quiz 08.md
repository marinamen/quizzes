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


<img width="1330" alt="Screenshot 2023-09-12 at 00 16 42" src="https://github.com/marinamen/quizzes/assets/142757957/3401a459-0991-4e68-ba4d-a43080b9ef97">





#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
<img width="679" alt="Screenshot 2023-09-15 at 10 47 30" src="https://github.com/marinamen/quizzes/assets/142757957/31e0a4fc-8c33-406d-885f-abd9f95c828e">

