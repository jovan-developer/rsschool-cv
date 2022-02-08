# Ivan Dyadyura
## Frontend developer

***

### Skills

* HTML and CSS
* SASS (SCSS)
* Gulp (webpack for JS)
* Javascript
* Vue JS 2,3 (basic knoweledges and some commercial experience)
* Git, Github (Have experience working in a team)

***
### Code examples
#### Array.diff

Your goal in this kata is to implement a difference function, which subtracts one list from another and returns the result.

It should remove all values from list a, which are present in list b keeping their order.

```
function arrayDiff(a, b) {
  let resArr = a;

  for (let i = 0; i < b.length; i++) {
    for (let k = 0; k < a.length; k++) {
      if (resArr.find(el => el === b[i])) {
        let index = resArr.indexOf(b[i]);
        resArr.splice(index, 1);
      }
    }
  }

  return resArr;
}
``` 
***

### Education

* Took HTML and CSS courses almost 3 years ago
* Work in Frilance about 2 years
* I've been working for the company for the last year as frontend dev (vue and html + css)

***

### Languages

* __Russian__ - native speaker
* __English__ - A2 or b1 (not sure)