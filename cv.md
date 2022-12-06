# Jelizaveta Aia

![photo](photo.jpg "My photo")
******
## Contacts:
**Phone:** +372 562 158 57

**E-mail:** jelizaveta05@gmail.com 

**GitHub:** @veta05

**Discord:** Evetta#3496

******

## About myself

I am studying at a technical school to become a junior software developer. There I realized that I wanted to choose the direction of the front-end. At the moment I devote time to this and I want to develop in this direction.
I love to learn, I love teamwork and I am stress tolerant.

## Skills
* HTML
* CSS
* JavaScript
* Python
* PHP
* C#

******
## Code example
```
id=""
while len(id)!=11 or ik.isdigit()!=True:
    try:
        id=input("Enter your id: ")
    except ValueError:
        print("Error!")
print("id analys: ".center(50,"-"))
print("First symbol: ")
id_list=list(id)
if int(id_list[0]) not in [1,2,3,4,5,6]:
    print(ik_list[0], " - wrong number")
else:
    print(id_list[0], " - correct number!")
    month=id_list[3]+id_list[4]
    month=int(month)
    if month>0 and month<13:
        print(id_list[3], id_list[4], "Correct data!")
        day=int(id_list[5]+id_list[6])
        #1,3,5,7,8,10,12 - 31 days
        #2,4,6,9,11 - 28-29, 30 days
        #1,2-"18", 3,4-"19", 5,6-"20" + id_list[1]+id_list[2]
        if int(id_list[0])==1 or int(id_list[0])==2:
            year=int("18" + id_list[1]+id_list[2])
        elif int(id_list[0])==3 or int(id_list[0])==4:
            year=int("19" + id_list[1]+id_list[2])
        elif int(id_list[0])==5 or int(id_list[0])==6:
            year=int("19" + id_list[1]+id_list[2])
        if month in[1,3,5,7,8,10,10] and day>0 and day<32:
            print(id_list[5], id_list[6], "correct day!")
        elif (month in [2,4,6,9,11] and day>0 and day<31) or (month==2 and day>0 and day<29):
            print(id_list[5], id_list[6], "correct day!")
        elif tear% 4==0 and month ==2 and day >0 and day<30:
            print(id_list[5], id_list[6], "correct day! 29 february.")
        else:
            print(id_list[3], id_list[4], "Wrong days")
    else:
        print(id_list[3],id_list[4], "wrong datas")
sum=0
for i in range(1,11):
    if i<10:
        sum+=i*int(id_list[i-1])
    else:
        sum+=(i-9)*int(id_list[i-1])
    sum+=i*int(id_list[i-1])
print("Summ: ", sum)
remainder=sum//11
print(remainder)
if remainder==10:
    sum=0
    for i in range(3,13):
        if i<=9:
            sum+=i*int(id_list[i-1])
        else:
            sum+=(i-9)*int(id_list[i-1])
    remainder=sum//11
remainder=sum-remainder*11
print("Control number: ", remainder)
if remainder==int(id_list[10]):
    print("Tour ID number is correct!!!!")
else:
    print("Your ID number is wrong!")
```

******
## Education
*2019* Gamma Inteligence, Python Courses

*2021-...* Technical school - junior software developer

******
## Languages
**Russian** native

**Estonian** advanced

**English** intermediate

**Spanish** starter