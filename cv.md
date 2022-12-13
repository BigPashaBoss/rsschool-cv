# Pavel Zaitsau

## Contacts
* **Email**: zaitsaup@gmail.com
* **Address**: Homel, Belarus
* **Discord**: BigPashaBoss

## About me:
My goal is to understand the frontend and get a job. I like to learn something new and most importantly immediately put it into practice. My desire to study is reflected in some diplomas and completed java courses.

## My skills:
* Java 8, SQL, Regular Expressions, Git, JDBC, JUnit 5, Mockito, Spring Core, Spring MVC, Apache Maven, XSLT, XPath, SOLID.

## Code example:
```
function wave(str){
    if (!str) return [];
    return Array.from({length: str.length}, (e,i) => str.charAt(i) != ' ' ?
                    str.substring(0,i) + str.charAt(i).toUpperCase() + str.substring(i+1) : '')
                .filter(e=>e);
}
```
```
function isValidIP(str) {
  let reg = /^\d$|^[1-9]\d$|^1\d\d$|^2[0-4]\d$|^25[0-5]$/
  let numbersArr = str.split('.')
  return numbersArr.length == 4 && numbersArr.every(e => reg.test(e))
}
```

## Work experience:
* EPAM Pre-production, 3 months.

## Educations:
* Belarusian State University of Transport.

## English:
My English level is A2.