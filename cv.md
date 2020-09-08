# JUNIOR WEB DEVELOPER

### Rinat Nassibullin

---

### Contacts

1. Telegram - _@Nilubisan_
2. VK - vk.com/make_it_simply
3. Whatsapp - _+77772676795_

---

#### Summary

Self-motivated, enthusiastic, obsessive with Web, passionate beginning Frontend-developer. My aim is to become a skilled and proficient full-stack developer and be able to write perfect code. I enjoy gaining interesting and useful knowledge and share it with other people.

---

#### Skills

- HTML
- CSS, Sass
- Vanila JS, jQuery
- GIT
- BEM methodology

My portfolio at [GitHub](https://nilubisan.github.io/)

---

#### Code

Here's a solution of the task from CodeWars. Function below identifies valid IPv4 addresses in dot-decimal format

```javascript
function isValidIP(str) {
  let result = str.match(/^(\d{1,3})\.(\d{1,3})\.(\d{1,3})\.(\d{1,3})$/);
  if (!Boolean(result)) return false;
  else {
    result = result.slice(1);
    for (let item of result) {
      if (
        result.length !== 4 ||
        item > 255 ||
        (item.length > 1 && item[0] == 0)
      )
        return false;
    }
    return true;
  }
}
```

The aim of next code is to count duplicates of letters in a string.

```javascript

let arrOfItems = text.toLowerCase().split('');
let arrOfSameItems = [];
for (let i = 0; i < arrOfItems.length; i++) {
  if (arrOfItems.includes(arrOfItems[i], i+1)) {
    if (!arrOfSameItems.includes(arrOfItems[i])) arrOfSameItems.push(arrOfItems[i]);
  }
}
return arrOfSameItems.length;
}
```

---

#### Education

Courses:

- [freeCodeCamp](https://www.freecodecamp.org/)
- [CodeAcademy](https://www.codecademy.com/)
- [W3Schools](https://www.w3schools.com/)
- [HTMLAcademy](http://htmlacademy.ru/)

---

### English

_Intermediate (**B2**)_
