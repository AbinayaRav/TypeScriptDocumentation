**AbinayaR  
TypeScript 
Documentation**  

**##TypeScript Features**   
TypeScript is an open source, strongly typed and statically typed framework.   
It is the super set of JS.   
It is an extension of ES6 version of JS framewor with additional features.     
TypeScript code is both a client side and server side sripting language.   
TypeScript is compiled by TypeScript compiler to JS code and JS is interpreted and rendered on the browser.   
TypeScript is easy to learn and understand.   
It is object oriented.   
It has DOM manipulation.   
It supports JS libraries.    
It has compile time error checking, type checking and auto completion of the statements.    
It is portable.   

**## Components of TypeScript:**   
Language - all keywords and syntax   
TS Compiler : Transpiling.   
GTS Language services : provides features like autocompletion of the statements, typeData chekcing, error checking, formatting, coloration etc.   

**## Datatypes of TS**    
Primitive - number, string, boolean, void, null, undefined, any    
User Defined - array, function, enum, tuple, class, interface    

**### Array:**    
Arrays are homogenous collection of elements. They are dynamic.    
Declaration: let arr1:number[] = [1,2,3,4];   
let arr1:Array<number> = [1,2,3,4];     
**### Tuple:**    
Arrays of heterogenous elements with proper ordering.    
type type1 = [number,string];   
let arr1:type1 = [1,"Hi"];   
let [b,c] = arr1; (destructuring)         
**### Interface**
contract used in the application.    
interface I1
  {    
  name: string;   
  age : number;   
  display():(string) => string;   
  }   
Use implement in the class.     
  **Class**
  It is a template or blueprint of the object.    
  Inheritance is the parent child relationship.
  In a class we can have getters and setters to access the members of the class.    
  constructors are used to initialise the members of the class.    
  **Function**
  Block of code which performs a sepcific task. They accept parameters and may or may not return value.   
  function fn()   
  {  
  
  }  
  function overloading with same number of arguments with different datatypes is possible in TS.       
  Functions are of two types : named and annonymous.    
  **enum**
  It is a special datatype that holds a list of pre defined values. Enums are two tpes : String, numeric and mixed.    
  enum E1{   
  RED, ORANGE, BLUE;    
  }    
  Enums can be constant or computed.   
  **Operators**
  Arithmetic    
  Relational    
  Logical    
  Assignment    
  Type    
  Bitwise     
  
  **Spread Operator**    
  It expands the elements of an iterable object like array, list, string, map, set etc.
  let arr1 = [1,2,3,4,5]   
  let arr2 = [...arr1, 7,8]   
  o/p: arr2 = [1,2,3,4,5,7,8]    
  **Unions**   
  Join the datatypes so that the variable can use any of the types.    
  let a:number|string = [1,2,"Hi"]
  
  **String**    
  sequence of characters.   
 Strings functions are : charAt(), indexOf, lastIndex(), matches(), slice(), substring(), substr(), padStart(), padEnd(), search(), to uppdercase() tolowercase() etc.   
  **Typeinference**
    Infers the type of the variable when no explicit type annotation is provided.    
  **Condtional statement**   
  If, If..else, if..else if... else, nested if, switch    
  **Looping statement**   
  for, for..in, for..of, forEach, while, do..while   
  **Maps**      
  key value pair.   
  let map1 = new Map<string, boolean>();   
  **sets**   
  let set = new set();   
  doesn't store duplicate values.    
  **AccessModifiers**    
  public, private, protected
  readonly - makes the member of the class read only and can't set it.    
  
  
  
  Function parameters : optional, default, required, rest    
  
  **Module**    
  Used to prevent the global scope of the code and organize an dmainting a large code base.    
  use export to variables, functions, class, interface, variables.
  export let a = [10,122,122];
  use it in another file as, import a from "./xxxx.tx"
  
  **Namespace**
  logical grouping of related functionalities.    
  namespace namesp1
  {  
  export function fn1()   
  export function fn2()    
  
  }  
  use it in another file as ///<reference path ="./xxxx.tx">     
  
  
  
  
  
  
