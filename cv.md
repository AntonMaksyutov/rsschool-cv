# Anton Maksyutov

## Location
Russia, Yekaterinburg

## Contacts:
* Email: ant87m@yandex.ru
* Discord: Last#3984
* Telegram: @Ant87M
* GitHub: Anton Maksyutov

## About Me

My goal is to become a front-end developer and enjoy my work,
I always strive for new knowledge and try to improve the skills already acquired.


## Code example


### CodeWars Kata 8:

Given an array of integers.

Return an array, where the first element is the count of positives numbers and the second element is sum of negative numbers. 0 is neither positive nor negative.

If the input is an empty array or is null, return an empty array.

Example
For input [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, -11, -12, -13, -14, -15], you should return [10, -65].

```
function countPositivesSumNegatives(input) {
  
  let countPositiv = 0;
  let sumNegative = 0;
  let arr = [];
  
  if (input === null) return [];
  
    for (let i = 0; i < input.length; i++) {
        if (input[i] > 0) {
            countPositiv ++;
        }
        if (input[i] < 0) {
            sumNegative += input[i];
        }
    }
  
    arr.push(countPositiv);
    arr.push(sumNegative);
  
    if (arr[0] === 0 && arr[1] === 0) return [];

    return arr;
}
```


## Basic Skills and Courses
* HTML,CSS on the code-basics.com
* JavaScript on the learn.javascript.ru, freeCodeCamp
* Git, GitHub
* Markdown
* VS code

## Languages:

* Russian - Native
* English A2