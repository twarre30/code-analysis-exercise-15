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
| Elsa | dog |
| Maui | dog |
| Annie | undefined |



## Elsa

```js

const person {
	dogs: ["Elsa", "Maui", "Jasmine"],
	cats: ["Annie", "Carly"],
}

function (person, petName){			// Elsa
  for (let dog of person.dogs){			// person.dogs			
    if (dog.name === petName){			// Elsa === Elsa 		
      return dog				// dog
    }
  }
}

``` 
## Maui

```js

const person {
        dogs: ["Elsa", "Maui", "Jasmine"],
        cats: ["Annie", "Carly"],
}

function (person, petName){                     // Maui
  for (let dog of person.dogs){                 // person.dogs
    if (dog.name === petName){                  // Maui === Maui
      return dog                                // dog
    }
  }
}

```

## Annie

```js

const person {
        dogs: ["Elsa", "Maui", "Jasmine"],
        cats: ["Annie", "Carly"],
}

function (person, petName){                     // Annie
  for (let dog of person.dogs){                 // person.dogs
    if (dog.name === petName){                  // dog.name === Annie
      return dog                                // undefined
    }
  }
}

```

## Summary

The function takes a person's name and a pet name and looks for the person.dogs to see if they have a dog and if that person's dog name matches the pet name given it returns dog. If the dog name did not match petName then it would return as undefined. 


