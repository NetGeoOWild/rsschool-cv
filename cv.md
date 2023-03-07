# Georgiy Bashirov
![Avatar](https://avatars.githubusercontent.com/u/93530714?v=4)

---
### Future Frontend Developer
---
### Contact information:
* **Phone:** *8(928)-247-87-29*
* **Email:** *goshan397@gmail.com*
* **Telegram:** *@NetGeo0Wild*
* **Discord:** *NetGeoOWild#4628*
---
### About Me
I studied and graduated from the institute as an engineer of medical equipment. After that, I served a year in the armed forces of the Russian Federation.

When I returned home from the army, I started working, worked in various fields of activity and for a long time could not find what I like.

Once I saw about such a profession as a web developer, I saw that people create Internet sites, to be honest, I thought that this was not for me, but I was very interested and about a year ago, I started learning the basics of Html Language, CSS Style , and I liked it, I got involved and started learning Java Script, I used various plugins.

After that, I found the first job in this area, it is not directly related to frontend development, for the most part we are engaged in layout of ready-made projects, changing and filling them.

I want to move on and get knowledge of a developer to start a new stage in my life and get a new job where there will be more interesting projects where I can improve my skills.

I believe that every person can achieve good results and learn something new, the main thing is that there is a desire and it is necessary to move forward, you cannot stop.

---
### My Skills

* **HTML**
* **CSS**
* **JS Basics**
* **VScode IDE**
* **Git Basics**
* **SCSS Basics**
* **BootsTrap Basics**

### Code example:

##### CodeWars:
---
##### Kata Take a Number And Sum Its Digits Raised To The Consecutive Powers And ....¡Eureka!!
---
**DESCRIPTION:**
The number 89 is the first integer with more than one digit that fulfills the property partially introduced in the title of this kata. What's the use of saying "Eureka"? Because this sum gives the same number:89 = 8^1 + 9^2
The next number in having this property is 135 = 1^1 + 3^2 + 5^3
##### Task
We need a function to collect these numbers, that may receive two integers a,b
that defines the range \[a,b] (inclusive) and outputs a list of the sorted numbers in the range that fulfills the property described above.
##### Examples
Let's see some cases (input -> output):
1, 10  --> [1, 2, 3, 4, 5, 6, 7, 8, 9]
1, 100 --> [1, 2, 3, 4, 5, 6, 7, 8, 9, 89]
```
function sumDigPow(a, b) {
    let result = [];

    for (let i = a; i < b; i++) {

        if (i < 10) {
            result.push(i);
        } else {
            let str = String(i);
            let number = 0;

            for (let j = 0; j < str.length; j++) {
                number += Number(Math.pow(str[j], j + 1));
                if (number === i) {
                    result.push(i);
                }
            }
        }

    }

    return result;
}
```
### Courses:
RS Schools Course «JavaScript/Front-end. (in progress)

### Languages:
* **Russian**
* **English A2**
