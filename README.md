# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (numbers){
  let sum = 0

  for (let number of numbers){
    sum += number
  }

  return +(sum / numbers.length)
}
```

Inputs and outputs should be valid JavaScript values!

| Input          | Output |
| [1, 2, 3]      |   2    |
|[0, -1, -2]     |   -1   | 
|[10, 15, 20, 25]|   17.5 | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes an array of numbers as an input and returns quotient of the sum of the numbers in the array divided by the amount of number in the array.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
