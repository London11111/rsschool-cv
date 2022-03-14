# Artsem Rydlevich
harword1234567@yandex.ru
+375259183374
Discord:Yamaha #3383(@London11111)
Code examples:
```function isPrime(num) {
    
  if (num===2){
    return true;
  }
  if (num<2){
    return false;
    }
  let newnum= Math.sqrt(num);
  let nre = Math.ceil (newnum);
  
  
    for(let i=2;  (i <= nre)  ; i+=1) {
    
    if (num%i===0 ) {
      
       return false; 
             
 } 
  }
  
    return true;
  }
  ```
  ```function breakChocolate(n,m) {

if ( n>=1 && m>=1 ){
 
 res = (n * m)-1; 

  return (res);
}  
  
return 0;
  
}
```