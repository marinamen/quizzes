**QUIZ 01**　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦　

  #code

    intext = input("input:  ")
    words = intext.split()
    final=""
    for word in words:
        if len(word) <= 2:
            modifiedword = word
        else:
            middle_count = len(word) - 2
            middle_chars = str(middle_count)
            modifiedword = word[0] + middle_chars + word[-1]
            final+= modifiedword + " "
    print("output: ", final.rstrip())

  #test/proof　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦　
<img width="1168" alt="Screenshot 2023-09-15 at 10 15 52" src="https://github.com/marinamen/quizzes/assets/142757957/62cae229-1ed3-4e07-8f52-761e89ccc39f">


   #flowchart　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦　

   ![IMG_1456](https://github.com/marinamen/quizzes/assets/142757957/20dbdf99-e279-43dd-b832-1fadc356d96f)
