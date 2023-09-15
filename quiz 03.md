**QUIZ 03**˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
3. Create a program that translate the proteins in the DNA chain as shown below

#code

    def dnatorna (inprotein:str):
        string = inprotein
        outprotein= ""
        for letter in string:
            if letter=="A":
              outprotein+="T"
            elif letter=="G":
                outprotein+="C"
            elif letter=="T":
                outprotein+="A"
            elif letter=="C":
                outprotein+="G"
    
        return outprotein
    inprotein = "AGCT"
    outprotein= dnatorna(inprotein)
    print(outprotein)


#proof/test˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
<img width="1253" alt="Screenshot 2023-09-11 at 20 35 22" src="https://github.com/marinamen/quizzes/assets/142757957/9a1a24f3-59f6-40f3-b013-fba5824e51dd">


#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![IMG_1465](https://github.com/marinamen/quizzes/assets/142757957/5ea214f2-1b97-4e31-9c33-97f8ff3a2799)

   
