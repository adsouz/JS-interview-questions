# Q-A
Q&amp;A

1 .//2nd largest number
  var x1= [1,2,3,4,4,5,6,6,6];
  var y1 = x1.filter((item,index,ar) => ar.indexOf(item) == index).sort((a,b)=>a-b)
  console.log(y1[y1.length-2]);
  
2. match a string that starts and ends with the same vowel (i.e., {a, e, i, o, u})
   var re =  /^([aeiou])[a-z]*\1/ (/1 uses backreference to match first matched set)
