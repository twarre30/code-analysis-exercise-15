# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){
  for (let dog of person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| ----- | ------ |
|       |        | 
|       |        | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td></td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible

## Inputs and Outputs

| Inputs | Outputs |
| :---: | :---: |
| Tiffany, Elsa | dog |
| Emily, Maui | dog |
| Kevan, Jasmine | dog |



## Tiffany and Elsa

```js

function (person, petName){			// Tiffany, Elsa
  for (let dog of person.dogs){			// Tiffany.dogs			
    if (dog.name === petName){			// Elsa === Elsa		
      return dog				// dog
    }
  }
}

``` 
## Emily and Maui

```js

function (person, petName){                     // Emily, Maui
  for (let dog of person.dogs){                 // Emily.dogs
    if (dog.name === petName){                  // Maui === Maui
      return dog                                // dog
    }
  }
}

```

## Kevan and Jasmine

```js

function (person, petName){                     // Kevan, Jasmine
  for (let dog of person.dogs){                 // Kevan.dogs
    if (dog.name === petName){                  // Jasmine === Jasmine
      return dog                                // dog
    }
  }
}

```

## Summary

The function takes a person's name and a pet name and looks for the person.dogs to see if they have a dog and if that person's dog name matches the pet name given it returns dog. If the dog name did not match petName then it would return as undefined. 


