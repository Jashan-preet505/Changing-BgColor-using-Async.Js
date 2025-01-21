Answer 1: how to handle clearTimeout ?

//declare this intervalId first and outside of block to make it global

//Keep in mind that for using clearInterval there is intervalId that refer to the setInterval and add if condition to check for intervalId if it exists then clear itotherwise set interval

Answer 2: Thenable objects

//1.Having then function 

// 2.all promises are thenable objects but not all thenables are promises.

//3. then method having two callbacks. one for resolve and one for reject state.
