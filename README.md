# Variables
JS

//  1

var   name = "Yaroslav";
      age = "22",
      hasDriverLicense = true,
      grades = [ 1, 2, 3, 4, 5 ]

     console.log( 'Variables' );
     console.log( 'My name is', name );
     console.log( 'I am', age ,'years old' );
     console.log( 'My 2nd grade is', grades[1] );
     
     
     
     
 
// 2

var a = 1; b = 2;
if (a>b) {
alert( 'Номер один больше' );
}
else {
alert('Номер 2 больше');
}

// 3

 function sum() {
  var result = 0;

  for (var i = 0; i < arguments.length; i++) {
    result += arguments[i];
  }

  return result;
}
alert( sum(1, 2, 3) );


// ES6

let   name = "Yaroslav",
      age = "22",
      hasDriverLicense = true,
      grades = [ 1, 2, 3, 4, 5 ],

     console.log( 'Variables' );
     console.log( 'My name is', name );
     console.log( 'I am', age ,'years old' );
     console.log( 'My 2nd grade is', grades[1] );
     
