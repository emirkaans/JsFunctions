// arraydeki erroru silip ortanca değeri bulan fonksiyon;

const calcMedium = function(arr){
  let tempar = [];
  let medium;
  
  for(let i=0; i<arr.length; i++){
    if(typeof arr[i] !== "number" || isNaN(arr[i])) continue;
    tempar.push(arr[i]);
  }
  
  console.log(`New Array = ${tempar}`);
  
  if(tempar.length %2 === 0){ 
  medium = [tempar[(tempar.length)/2-1], tempar[(tempar.length)/2]];
  } else {
    medium = tempar[(tempar.length +1) /2 -1];
  }
 return medium;
}

let arr1 = [1,4,3,2,7]; // 3
let arr2 = [4,3,2,1,5,8]; // 2,1
let arr3 = [1,2,5,"error",8,3]; // 5
let arr4 = [1,3,8,"error", "error", null, undefined,NaN,2,3];
let arr5 = [1,3,6,NaN,4,NaN,2,8,NaN];

console.log(calcMedium(arr1), calcMedium(arr2), calcMedium(arr3), calcMedium(arr4), calcMedium(arr5));
