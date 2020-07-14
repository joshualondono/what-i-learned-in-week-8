# what-i-learned-in-week-8

# What I learned

       1. Reduce 
       2. Filter
       3. For Of


# Reduce 

1. Reducing multiple values to output a single vaue  
  	
~~~~ js

const array1 = [1, 2, 3, 4];
const reducer = (accumulator, currentValue) => accumulator + currentValue;

// 1 + 2 + 3 + 4
console.log(array1.reduce(reducer));
// expected output: 10

// 5 + 1 + 2 + 3 + 4
console.log(array1.reduce(reducer, 5));
// expected output: 15

~~~~

# Filter

2. Filter creates a new array with all elements that pass the test implemented by the provided function.   

~~~~ js

const words = ['spray', 'limit', 'elite', 'exuberant', 'destruction', 'present'];

const result = words.filter(word => word.length > 6);

console.log(result);
// expected output: Array ["exuberant", "destruction", "present"]

~~~~

# For Of

3. For Of allows us to save n=time by not needing to constantly write a for loop when you don't need access to the index

~~~~ js

const array1 = ['a', 'b', 'c'];

for (const element of array1) {
  console.log(element);
}

// expected output: "a"
// expected output: "b"
// expected output: "c"


~~~~

