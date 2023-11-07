# Ivan Kotov

## Contact information:
* Phone:
  * +375295635835
* E-mail:
  * ivankotov12345@gmail.com
* Telegram: 
  * Jean Cat
* Viber:
  * +375295635835

  ## About myself:
Started my career as engineer in 2019, and worked for some local factories untill now. Proved myself like capable, flexible team worker wich have abilities to learning.
 
 Free time i spend with literature and with my film camera. Have nice library wich includes books of Hemingway, Camus, Kafka, Tolstoy.
 
## Skills and Proficiency:
* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code

## Code example:
Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.

```function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
} 
```

## Education:
Belarussian-Russian univercity - cutting tools design

## languages:
* English - Upper Intermediate
* Russian - Native
* Polish - Elementary
* French - Elementary