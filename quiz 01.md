**QUIZ 01**　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦　
1. Black Box:Describe a program that  produces the output shown with the input provided.

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
   ![](https://github.com/marinamen/quizzes/blob/main/pictures/Screenshot%202023-09-15%20at%2010.15.52.png)


   #flowchart　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦　

![](https://github.com/marinamen/quizzes/blob/main/pictures/01word.png)
