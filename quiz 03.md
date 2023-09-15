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
![](https://github.com/marinamen/quizzes/blob/main/pictures/Screenshot%202023-09-11%20at%2020.35.22.png)

#flowchart˚　　　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/quizzes/blob/main/pictures/dna.png)
   
