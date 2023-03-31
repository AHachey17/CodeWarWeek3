# CodeWarsWeek3
## Every week I will be posting a weekly Repo that I update daily with complete CodeWar Katas
### Week3
Day 11: 8KYU, UNFINISHED LOOP (debugging) - added afterthough/end of for Loop, it was missing
```
function createArray(number){
  var newArray = [];
  
  for(var counter = 1; counter <= number; counter++){
    newArray.push(counter);
  }
  
  return newArray;
}
```
Day 12: 8KYU, ADD LENGTH - created a function that takes an string and returns the array with a count of each word added with it's element in the array.
Thus, "apple ban" --> ["apple 5", "ban 3"]
```
function addLength(str) {
const arrOfwords = str.split(" ")
for (let i = 0; i < arrOfwords.length; i++){
  const wordLength = arrOfwords[i].length
  arrOfwords[i] = `${arrOfwords[i]} ${wordLength}`
  }
  return arrOfwords
}
```
Day 13: 8KYU, GET THE MEAN OF ARRAY - created a function that takes an array of numbers and returns the average.
```
function getAverage(marks){
  let total = 0
  for (let i = 0; i < marks.length; i++){
    total += marks[i] //remember the += 
  }
  return total / marks.length

}
```
Day 14: 8KYU, FILTER OUT THE GEESE - created a function that takes an array of birds but removes any geese ("African", "Roman Tufted", "Toulouse", "Pilgrim", "Steinbacher")
```
function gooseFilter (birds) {
  const geese = ["African", "Roman Tufted", "Toulouse", "Pilgrim", "Steinbacher"]
  return birds.filter(bird => !geese.includes(bird)) 
  
}
gooseFilter()
```
Day 15: 8KYU, My head is at the wrong end! - created a function that reverses an array. After reading the direction I thought this would be a little more difficult but was pretty easy.
```
function fixTheMeerkat(arr) {
 return arr.reverse()
}

fixTheMeerkat(["tail", "body", "head"])
```


