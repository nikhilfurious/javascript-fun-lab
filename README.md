# javascript-fun-lab
Javascript Clean Learning 


1) What are the data types in JS? 

Data Types in Javascript : 
i) Number :  
   The number type represents both Number and Floating points in javascript.
   There are many operations for number +,-,*,/.
   Besides all these there are also called sepcific value numbers: Infinity, -Infinity, Nan
   
   Infinity: represents the mathematical Infinity ∞. It is a special value that’s greater than any number.
   NaN: represents a computational error. It is a result of an incorrect or an undefined mathematical operation, for instance:
   
   Example :
     a) let n = 12.34 // number 
     b) let n = 1/0  // Infinity
     c) let n = 'a' * 1 // Nan.
     
     
 ii) String : 
       Any value which is surrounded by quotes are called Strings in javascript.
       In Javascript there are three types of  Quotes.
         a) Single Quotes - Eg: let ex = 'a' // string.
         b) Double Quotes - Eg: let ex = " Hello" // string.
         c) Bacticks -Eg: let ex = `Hello World` // string.
   
   Important Note: There is no character type in Javascript ,even if single character is represented in two single quotes. Then it will be declared as String.
   
   iii) Boolean :
      The boolean type has only two values: true and false.
      This type is commonly used to store yes/no values: true means “yes, correct”, and false means “no, incorrect".
     Eg: let n = true //  Boolean 
     
   iv)  Undefined value : 
       This data type is esepcially shown in console when the value is decalred but it is not assigned with any value :
        Exammple: 
             var a ;
            console.log(a)// undefined 
        Explanation :
             Here the variable 'a' is decalred but it is not assigned with any value. That's the reason when we console the value 'a'.
             The javascript will return 'undefined' at  run time.
             Important: This "undefined" data type is very important. Most of the time during coding,
             we at starting declare lot of global variables and some times we forget to assgin the value for it and use that variable to functions.
             This in return gives the error "Undefined".  
    vi) Bigintit : In JavaScript, the “number” type cannot represent integer values larger than (253-1) (that’s 9007199254740991),
     or less than -(253-1) for negatives. It’s a technical limitation caused by their internal representation.
    vii) Type of : This type of operator is used to check delcaration of variable.
        Eg: let n = "Nikhil",
              type of (n) // String.
             let age = 10,
                type of (age) //number.       
      viii) Objects :
       In contrast, objects are used to store keyed collections of various data and more complex entities. 
        In JavaScript, objects penetrate almost every aspect of the language.
       So we must understand them first before going in-depth anywhere else.
       An object can be created with figure brackets {…} with an optional list of properties.
       A property is a “key: value” pair, where key is a string (also called a “property name”), and value can be anything.        
     example: 
      let user = {               // an object
                  name: "John",  // by key "name" store value "John"
                  age: 30        // by key "age" store value 30
                    };
     
            
            For more reference: https://javascript.info/data-types
        
       
