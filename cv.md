# LILY TROFIMOVA
## Contacts
![](/rsschool-cv/My_avatar.jpg)

Discord rs-school: **Lily Trofimova (@2020Liliya)**  
E-mail: **trofimovaliliy4@gmail.com**

## About me
Hi! I'm a web designer who just graduated from university. I realized that design is not my thing for 4 years of higher education. My goal is to go through all phases of the 'JavaScript/Front-end' course to become a front-end developer because it's been a dream of mine since high school. I learned a little bit of C++, Python, and Kotlin during university. It's time to pump up my knowledge and work in IT!

## Work experience
Some freelancing experience in landing page design and social media design.

## Languages
* English level – A2
* German level – A1

## Code examples
```

month = int(input('Month: '))
day = int(input('Day: '))
if 12 >= month > 0 and 31 >= day > 0:
    if month == 2 and day > 29:
        print('Error!')
    elif ((month == 1 or month == 3 or month == 5 or month == 7 or month == 8 or month == 10 or month == 12)
          and day <= 31) \
            or ((month == 4 or month == 6 or month == 9 or month == 11)
                and day <= 30) or (month == 2 and day <= 29):
        date_1 = datetime.datetime(2020, month, day)
        date_2 = datetime.datetime(2021, 1, 1)
        new_year = date_2 - date_1
        print('There are {} days until the new year 2021!'.format(new_year.days))
    else:
        print('Error!')
else:
    print('Error!')

```