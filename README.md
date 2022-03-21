# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){
  for (dog in person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

|        Input        |          Output          |
| ------------------- | ------------------------ |
|   Blair, Tugger     |   [petName:"Tugger", petBreed: "Labradoodle]     | 
|   Jaclyn, Annie     |   [petName:"Annie", petBreed: "Calico"]           | 
|   Bridget, Rosie    |   [petName:"Rosie", petBreed: "Hound]           | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>
    This program checks the array for the value passed for person and locates the variable dog which is 
    also an array. That array is then checked for the name value and if that value is equal to the initial 
    arguemnt passed for petName, it return the dog array.
    </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
