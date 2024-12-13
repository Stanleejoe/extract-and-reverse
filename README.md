# extract-and-reverse
function extractAndReverse(array) {    
    const subArray = array.slice(2, 5);  
    const reversedSubArray = subArray.reverse();  
      return reversedSubArray;  
}  
 
const numbers = [15, 30, 45, 60, 75, 90];  
const result = extractAndReverse(numbers);  
console.log(result); 
console.log(numbers);
