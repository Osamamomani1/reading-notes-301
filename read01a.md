# Review, Research, and Discussion

### Describe (in plain English) what Array.map() does .

I'ts just like a for loop, looping throw the Array and return a new Array with the same length of the origin Array

***

### Describe (in plain English) what Array.reduce() does

Array.reduce() returne value is assigned to the accumulator, whose value is remembered across each iteration throughout the array, and ultimately becomes the final, single resulting value.

we can say that the .reduce method adding the lelemnts insiide the array and return the final single value depending on the current index value 

***
### Provide code snippets showing how to use superagent() to fetch data from a URL and log the result

* With normal Promise .then() syntax
```
superagent.get(url).then(reult=>{consle.log(result)}.catch(error=>{consol.log(error)})
```

* Again with async / await syntax
```
 let getData= async()=> {let data=await superagent.get(url)
    consle.log(data.body)}; grtData();
```

***
### Explain promises as though you were mentoring a Code 301 level student

In JavaScript the default action that's the code execute line by line and if something in line need a time to execute JavaScript will not wait until it's finish, It will skip it and go to the next line

In promises using async/await we told JavaScript that's that function is asynchronous and you should wait untill it's finish then execute what's comming after the await, and we can use .them() to get same output.

***

### Are all callback functions considered to be Asynchronous? Why or Why Not?

No, they could be Asynchronous or no I'ts dose't matter fore the callback functions if the logic should be Asynchronous or no
