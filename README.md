# Q-A
Q&amp;A

1 .//2nd largest number
  var x1= [1,2,3,4,4,5,6,6,6];
  var y1 = x1.filter((item,index,ar) => ar.indexOf(item) == index).sort((a,b)=>a-b)
  console.log(y1[y1.length-2]);
  
 2.  
