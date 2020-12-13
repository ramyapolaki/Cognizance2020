# *PSEUDO CODE-AMSTRONG NUMBER*
READ num

temp=num

sum=0

WHILE num>=0

    sum=sum+(num%10)*(num%10)*(num%10)
    num=num/10
ENDWHILE

IF sum==temp

    WRITE "NUMBER IS AN ARMSTRONG NUMBER"

ELSE

    WRITE "NUMBER IS NOT AN ARMSTRONG NUMBER"
