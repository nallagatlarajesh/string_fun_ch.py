# string_fun_ch.py
# count the character ,how many times its repeat.
#requirements
#function  charcount
# parametres  ch,st (character,string)
#count=0

#code
def charcount(ch,st):
    count=0
    for character in st:
        if character==ch:     
            count+=1
    return count
#function end here
st=input("enter  a string:")
ch=input("enter the character to be searched:")
#function calling
charcount(st,ch)
print("string is: ",st)                   #optional
print("searching character is:",ch)    #optional
print("number of times charecter " ,ch,"occurs iin the string is :",charcount(ch,st))




#input and output
#string is:  hai  rajesh how are you,and  where are you
#searching character is: a
#number of times charecter  a occurs iin the string is : 5



