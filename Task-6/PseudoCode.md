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
    
 ![alt](https://lh6.googleusercontent.com/Y2bLIhGd9CKU4FDCIGccnJSyuUhWBNHCXvh6v_5jlii01udgqzNVcBDPHgeSgMQJViXd450SGUhPZV-Z1U6b5CBbxdw5qfwtm9oPbv9jGjyFefnnHhc=w1280)
