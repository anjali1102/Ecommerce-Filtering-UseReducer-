# Ecommerce-Filtering-UseReducer (Practising)
[SEE PREVIEW 👀](https://cv321d.csb.app/)

# useReducer-

> for self understanding

BEHIND  THE SCENE OF REDUCE
![image](https://user-images.githubusercontent.com/56559378/164282878-4604ebd0-4290-4d25-b100-547e5d5901fe.png)

[GIVE CODE A TRY  🚀](https://jsfiddle.net/anjali1102/rhx7m68c/1/) 

ARRAY REDUCE METHOD
![image](https://user-images.githubusercontent.com/56559378/164284121-a43094cd-a8b0-43d2-b09a-794d3ea3124f.png)



> numbers.reduce(summarize, 0) calculates the sum of all elements in the array.

> The summarize callback is invoked for every item in the array with the accumulated sum and the iterated number. summarize callback adds the iterated item to the already accumulated sum, and returns that updated sum.

> That's how an array is reducing to a sum.

> Also, note the second argument of numbers.reduce(summarize, 0) — the sum of array items is initialized with 0.


<details>
<summary><b>What is acc here? </b></summary>
<p>

const numList = [1, 3, 55, 22, 44]

function oddAndEvenSumReducer(acc, value) {
    return acc
}

oddAndEvenSumReducer=numList.reduce(oddAndEvenSumReducer)

console.log(oddAndEvenSumReducer)

</p>
</details>

so here acc is first element in array




>Practice exc for useReducer

- [x] Find Even and Odd sum
- [x] Find Even and Odd sum without %2 logic
- [x] Cart managment 💓(tried useState, then useReducer) [SEE HERE](https://codesandbox.io/s/cart-mgmt-with-usereducer-x0xi8f?file=/src/App.js)
<details>
<summary><b>mistakes while making 😶‍🌫️ </b></summary>
<p>

>`key` needs to be assigned to a jsx element 
    
![image](https://user-images.githubusercontent.com/56559378/164563959-fb8ddc76-4cc1-442d-b00b-04d0003575ae.png)
![image](https://user-images.githubusercontent.com/56559378/164564051-0dbc2861-4e2d-4b06-9415-cf89de281be3.png)

>useReducer should be define before return only
![image](https://user-images.githubusercontent.com/56559378/164564429-60b4954d-173d-43ea-9a65-6bfe46fc8481.png)


</p>
</details>

