### PSEUDO CODE-AMSTRONG NUMBER

 Start

 num 

 temp=num
 
 order=num.length

 sum=0

WHILE num>0
     
    digit=numMOD10
    sum=sum+(digit^order)
    num=numDIV10
    
ENDWHILE

IF sum==temp then

    WRITE "NUMBER IS AN ARMSTRONG NUMBER"

ELSE then

    WRITE "NUMBER IS NOT AN ARMSTRONG NUMBER"
    
 ### FLOWCHART-ARMSTRONG NUMBER 
    
 ![alt](https://lh6.googleusercontent.com/mB75Puw5FgyNPx--5MkdfnuIV4omEeXmFdg5dlYN1Sk5CzEfAKcRcivJGj1-KEilbSpRLiy1Ujc-EvJcSYslosEJWhtG3BHOMqk6yQBNFjoFK4USwQ=w1280)
