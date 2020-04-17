- # Javascript
  - ## ES5
    - ### Basic Language Features
      - [Expressions Versus Statements](http://www.leadonet.com)

      - [Control Flow Statements](http://www.leadonet.com) and [Blocks]http://www.leadonet.com)

      - #### Comments
        - How to write good comments

        - Why comment should not be written

        - Links: [[1](http://www.leadonet.com), [2](http://www.leadonet.com), [3](http://www.leadonet.com)]

      - #### [Strict Mode](http://www.leadonet.com)

      - #### [JavaScript’s Type System](http://www.leadonet.com)
        
        - Static Versus Dynamic

        - JS Types

        - Static Typing Versus Dynamic Typing
        
        - Static Type Checking Versus Dynamic Type Checking
        
        - Coercion
        
        - [An explanation of JavaScript’s weird type system](http://www.leadonet.com)

      - #### Primitive Values Versus Objects

        - [JavaScript Primitive vs. Reference Values](http://www.leadonet.com)

        - [The Difference Between Boolean Objects and Boolean Primitives in JavaScript](http://www.leadonet.com)

      - #### undefined and null
        - [What’s the difference between Null & Undefined?](http://www.leadonet.com)

      - #### [Equality Operators: === Versus ==](5)

      - #### [Logical Operators](http://www.leadonet.com)

      - #### [Truthy vs Falsy values](http://www.leadonet.com)

      - #### [Bitwise Operators](http://www.leadonet.com)

        - [Using JavaScript’s Bitwise Operators in Real Life](http://www.leadonet.com)

      - #### String
        - Unicode

          - Code Points

          - Size in bytes of a single char

          - [Unicode and javascript](http://www.leadonet.com)

        - Constructing Strings

        - Manipulation

        - Concatenation

      - #### Statements
      
        - Loops

          - for

          - while
o
          - do while

          - for in

        - if else

        - Switch

        - debugger statement
        
      - #### Functions ([details](http://www.leadonet.com))

        - #### [Roles of functions]http://www.leadonet.com)

        - #### [Defining Functions](http://www.leadonet.com)

            - [Function Expressions](http://www.leadonet.com)

            - [Function Declarations](http://www.leadonet.com)

            - [The Function Constructor](http://www.leadonet.com)

        - #### [Params vs Arguments]http://www.leadonet.com)
        - #### [Hoisting](http://www.leadonet.com)

        - #### [More Control over Function Calls: call(), apply(), and bind()](http://www.leadonet.com)

        - #### [Arguments Object](http://www.leadonet.com)

        - #### [Closures](http://www.leadonet.com)

      - #### global/window object

        - [console](http://www.leadonet.com)
          
          - log
          
          - formatted output
        
        - [setTimeout](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setTimeout)

          - [A good question on setTimeout](http://www.leadonet.com)

        - [setInterval](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setInterval)

        - [clearInterval](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/clearInterval)

      - #### [Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)

        - Property Accessors ([Dot and square notation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_accessors))

        - [`this` in objects]http://www.leadonet.com)
          - Losing this When Extracting a Method
          - Functions Inside Methods Shadow this
          - Other [gotchas when using this](http://www.leadonet.com)

        - [Inheritance](http://www.leadonet.com)

          - [Prototypal Chain](http://www.leadonet.com)

          - Sharing Data Between Objects via a Prototype

          - Setting and Deleting Affects Only Own Properties

          - [Javascript inheritance by examples](http://www.leadonet.com)

        - Object reflective methods

          - [.keys](http://www.leadonet.com)

          - Check out all the methods of Object [here](http://www.leadonet.com)

        - Accessors ([Getters](http://www.leadonet.com))

        - [Property Attributes and Property Descriptors](http://www.leadonet.com)

        - [Protecting Objects](http://www.leadonet.com)

          - Sealing

          - Extensions

          - Freezing

          - Protection Is Shallow

      - #### Exception Handling

        - What Is Exception Handling?

        - Exception Handling in JavaScript

          - throw

          - [try-catch-finally](Languages  Edit  Advanced try...catch)

        - Error Constructors

        - Stack Traces
        
        - All these are explained [`here`](http://www.leadonet.com)

      - #### Arrays
        - Forms of objects

          > Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Neither the length of a JavaScript array nor the types of its elements are fixed. Since an array's length can change at any time, and data can be stored at non-contiguous locations in the array, JavaScript arrays are not guaranteed to be dense; this depends on how the programmer chooses to use them. In general, these are convenient characteristics; but if these features are not desirable for your particular use, you might consider using typed arrays.

          Arrays cannot use strings as element indexes (as in an associative array) but must use integers. Setting or accessing via non-integers using bracket notation (or dot notation) will not set or retrieve an element from the array list itself, but will set or access a variable associated with that array's object property collection. The array's object properties and list of array elements are separate, and the array's traversal and mutation operations cannot be applied to these named properties.

        - Array Methods

          - [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

          - [Reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

          - [Filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

          - [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

        - [mutating and non-mutating methods](http://www.leadonet.com)

      - #### [Regular Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)

        - Quantifiers

        - Capture Groups

        - Flags

        - [.test](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/test)

        - [.match](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match)

        - [.exec](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/exec)

        - [A simple tool to play with regex](http://www.leadonet.com)

        - [Javascript regex in depth](http://www.leadonet.com)

      - #### [Date object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)

        - Epoch time

        - [Understanding Date and Time in JavaScript](http://www.leadonet.com)

      - #### [JSON](https://www.json.org/)

        - [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)

        - [parse](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse)

        - [stringify](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify)

        - [difference between objects and JSON](http://www.leadonet.com)

    - #### Modules
      - [JavaScript Modules: A Beginner’s Guide](http://www.leadonet.com)

      - [In-depth](http://www.leadonet.com)

    - #### Shallow copy and Deep Copy

      - [Copying objects in javascript](http://www.leadonet.com)

      - How to deep copy

      - Why it's required

    - #### [instanceof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/instanceof), [typeof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof), [new](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new)

      - [More about 'new'](http://www.leadonet.com)

    - #### Pure, total and partial functions
      - [What are pure functions and why use them?](http://www.leadonet.com)

      - [Pure versus impure functions](http://www.leadonet.com)

      - Partial Functions

      - Functional perspective

        - [Decoupling methods from their objects](http://www.leadonet.com)

        - [Function Composition For Every Day Use.](http://www.leadonet.com)

      - Why it's better than loops

        - [map vs forEach vs for](http://www.leadonet.com)

        - [Rethinking JavaScript: Death of the For Loop](http://www.leadonet.com) (Also read comments from the author for more context and why loops are a better choice in some cases)

    - #### Built In Modules

      - Boolean

      - Date

      - Error

      - Function

      - JSON

      - Math

        - NaN

        - Infinity

      - Number

    - [Concurrency Model and Event Loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop)

  - ## ES6
    - #### [Let](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) and [Const](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)
      - Lexical Scope vs Function Scope
      - Why const?
      - Only references are const
      - Temporal Dead Zone
      - [Variables and scoping in ECMAScript 6](http://www.leadonet.com)
    - #### [Template Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
    - #### [Arrow Functions Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
      - this is lexical instead of bind
      - [versus normal functions](http://www.leadonet.com)
    - #### [for-of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of)
    
    - #### [default parameters](http://www.leadonet.com)
    
    - #### [Named Params](http://www.leadonet.com)
    
    - #### [Rest Params](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)
    
    - #### [Tagged Templates](http://www.leadonet.com)
    
    - #### [De-structuring Assignment](http://www.leadonet.com)
    
    - #### [Shorthand Properties](http://www.leadonet.com)
    
    - #### [ES6 Modules](http://www.leadonet.com)

      - CJS

      - AMD

    - #### [Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)

      - [then](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/then)

      - [catch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/catch)

      - [finally](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/finally)

      - [all](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all)

    - #### [Classes in ES6](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

      - How it's same as new Function

      - [In-Depth](http://www.leadonet.com)

    - #### [Computed Object properties](http://www.leadonet.com)
    - #### [Object.assign](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)
    - #### [Async/Await](http://www.leadonet.com) (Promises)
      - How it's based on Promises
    - #### [Symbols](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol)
    - #### [Maps](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map) and [WeakMaps](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap)
    - #### [Sets](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set) and [WeakSets](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakSet)
    - #### [Iterator Protocol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#The_iterator_protocol)
    - #### [Proxy](http://www.leadonet.com)
    - #### [Generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator)
    - #### [Iterators and generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators)
    - #### [function*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*)
    - #### [yield](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield)
    - #### [yield*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield*)
  - ## Style Guides
    - #### [AirBnB](https://github.com/airbnb/javascript)
      - [Breathing air into AirBnB’s JavaScript Style Guide](https://medium.freecodecamp.org/adding-some-air-to-the-airbnb-style-guide-3df40e31c57a)
      
      - [5 JavaScript Style Guides — Including AirBnB, GitHub, & Google](https://codeburst.io/5-javascript-style-guides-including-airbnb-github-google-88cbc6b2b7aa)
    - #### [Google](http://www.leadonet.com)
    - #### [Standard JS](https://standardjs.com/rules.html)
