_**Disclaimer:** Personal data provided below are fictional, as I'm currently not interested in the career opportunities offered by EPAM, and therefore not willing to disclose my true identity._

# Siarhei Kuzniatsou

## Contacts

- **Email:** 7ab901a7933419b5@protonmail.com
- **Github:** [7ab901a7933419b5](https://github.com/7ab901a7933419b5)
- **Location:** Minsk, Belarus

## About me

Yet another aspiring front-end developer.

## Skills

- HTML + CSS
- JavaScript
- Git

## Code example

Count strings in objects - a [Codewars problem](https://www.codewars.com/kata/count-strings-in-objects):
```javascript
function strCount(obj) {
  switch (typeof obj) {
    case "string": return 1;
    case "object": return Object.values(obj)
      .filter(x => x)
      .map(strCount)
      .reduce((a, b) => a + b, 0);
    default: return 0;
  }
}
```

## Experience

Nothing relevant so far.

## Education

- In progress: [RS School JS / Front-end, stage 0](https://rs.school/js-stage0)

## Language proficiency

- English – upper-intermediate (B2)
