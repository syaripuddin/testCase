# testCase
testCase with javascript


Soal 1 
Buatlah sebuah variabel String lalu ubahlah string tersebut dengan mengganti semua huruf vokal dengan simbol “*”. Variable bisa
langsung dibuat dengan value “The quick brown fox jumps over the lazy dog”, ataupun bisa berupa input dari user.
var nama ="The quick brown fox jumps over the lazy dog";

for (let i=0; i<nama.length; i++){

   hasil=  nama[i]= "*";
    console.log(hasil)
}

soal 2
Buatlah sebuah array yang berisi angka-angka. Berikan output yang berisi jumlah dari semua angka di dalam array tersebut, dan ketika
jumlahnya lebih dari 30, tambahkan kata “It’s big!”
Misal:
// array
let arr = [1,3,5,7,8];
// output
24
// array
let arr = [6,10,4,6,9];
//output
35
It’s big!

let arr = [1,3,5,7,8];
var total=0;

    for(let i=0; i<arr.length; i++){   
        total += arr[i];    
    }
    console.log(total)
    if(total > 30){
        console.log('It’s big!')
    }

let arr = [6,10,4,6,9];
var total=0;

    for(let i=0; i<arr.length; i++){   
        total += arr[i];    
    }
    console.log(total)
    if(total > 30){
        console.log('It’s big!')
    }

Soal 3
// array
let arr = [1,7,4,5,3];
// output
1
7
// array
let arr = [6,10,4,6,9];
//output
4
10

for(var i=0;i<nilai.length;i++){
        {  
             if(i == 0)
             { 
              var nilai_mak = nilai[i];
             }
             else if ( nilai[i] > nilai_mak){
                     nilai_mak = nilai[i];
             }
        } 
            {  
                 if(i == 0)
                 { 
                  var nilai_min = nilai[i];
                 }
                 else if ( nilai[i] < nilai_min){
                         nilai_min = nilai[i];
                 }
            }
} 

console.log(nilai_min)
console.log(nilai_mak)


