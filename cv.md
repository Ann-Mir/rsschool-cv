# Anna Mironovich
### *Frontend Developer*

---

## Contacts
**Phone:** +971582763522<br>
**Telegram:** @an4_m<br>

---

## Career Objective

A Front-End Developer with a desire to grow in a collaborative team environment.<br>
Experience in building web applications from the ground using JavaScript, TypeScript, React, and Redux.

___

## Skills

- HTML
- CSS (SASS, SCSS)
- JavaScript
- React
- Redux
- TypeScript
- Git

---

## Experience

### [Guitar Shop](https://guitar-shop-mu.vercel.app/guitars?_start=0&_limit=9)<br>
*An online store of musical instruments.*<br>

Collaborated with a designer, QA engineers, and a back-end developer.<br>
Set up the client side of the project from scratch.<br>
Implemented the catalogue, navigation, filters, catalogue search, pagination, and cart using React, Redux, and TypeScript.<br>
Covered the app with tests using React Testing Library and Jest.

---

## Education

### HTML Academy - *React Developer*
*September 2020 - December 2021*<br>
A comprehensive front-end development course covering all key aspects of creating accessible and responsive<br>
web applications using CSS, JavaScript, React, Redux, and Testing Libraries.



---

## Code example

```
/**
 * trimSymbols - removes consecutive identical symbols if they quantity bigger that size
 * @param {string} string - the initial string
 * @param {number} size - the allowed size of consecutive identical symbols
 * @returns {string} - the new string without extra symbols according passed size
 */
 
export function trimSymbols(string, size) {

  if (size === 0 ||  string === '') {
    return '';
  }

  if (!size) {
    return string;
  }

  const arr = [...string];
  let counter = 0;
  let match = false;
  const result = [];

  arr.forEach((letter, index) => {
    if (index > 0) {
      match = letter === arr[index - 1];
    }
    if (match && counter < size) {
      result.push(letter);
      counter++;
    }
    if (!match) {
      result.push(letter);
      counter = 1;
    }
  });

  return result.join('');
}
```

---

## Languages
- Russian - native
- English - upper-intermediate