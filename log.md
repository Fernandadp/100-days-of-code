# 100 Days Of Code - Log

### Day 0: May 26, 2019, Sunday

**Today's Progress:** setting up everything to start coding tomorrow!

### Day 1: May 27, 2019, Monday

**Today's Progress:** Found my old FreeCodeCamp projects, and continue working towards the Responsive Web Design Certification. Currently I'm working on the Technical Documentation Page.

**Thoughts:** I really need to learn some design skills.

**Link to work:** https://codepen.io/Fernandadp/pen/gJKEKE

### Day 2: May 28, 2019, Tuesday

**Today's Progress:** I finished the Technical Documentation Page of FreeCodeCamp's Web Design Certification.

**Thoughts:** Apart from design skills, I should definitely spend some time learning more css. I thought I was quite comfortable with it, but today I struggle with some little things, like avoiding two divs to overlap. So far I am not so happy with the result tbh.

### Day 3: May 29, 2019, Wednesday

**Today's Progress:** I have started the Portfolio Page of FreeCodeCamp. I have added all html elements, I only need to add some content. Also I have started adding some styling, so far I have done the header and a bit of nav bar.

**Thoughts:** I enjoy doing this so much! Style is always an issue, but I think with practice and observation (meaning looking at other websites) I can improve it. Also I like photography a lot, I should definitely pick it up again.

### Day 4: May 30, 2019, Thursday

**Today's Progress:** I continued working on the Portfolio Page, I am almost done, only few details to make all the tests pass. 
So, i came back for a second round today and finally got my FreeCodeCamp Responsive Web Design Certification! (https://www.freecodecamp.org/certification/fernandadp/responsive-web-design)

**Thoughts:** Although I am almost done, I've done actually almost enough to fullfill the requirements for making the test pass. Designwise of course it looks horrible, and there are details like margins and stuff that should definitely be improved.


### Day 5: May 31, 2019, Friday

**Today's Progress:** Continue with FreeCodeCamp Front End Libraries Certification.

**Thoughts:** Didn't have time to start with some React project, so I will continue with this for now. I didnt remember that I had already done some of this.


### Day 6: June 1, 2019, Saturday

**Today's Progress:** Continue the Front End Libraries Certification of FreeCodeCamp. Finished the jQuery section. Learned about some jQuery functions, function chaining (sticking two jQuery functions together). Started the React section (Sass I had already done it some months ago). To use JS inside JSX, simply include the code that is wanted to be treated as JavaScript within curly braces: { 'this is treated as JavaScript code' }. Babbel is used to transpile jsx into js. Nested JSX must always return a single element (This one parent element would wrap all of the other levels of nested elements). Comments in jsx: {/* */}.The naming convention for all HTML attributes and event references in JSX become camelCase (for example onclick is onClick in jsx). `<hr>` defines a thematic break.

**Thoughts:** Finally started with React. I had forgotten how helpful and easy jQuery is.
 
### Day 7: June 2, 2019, Sunday

**Today's Progress:** Continue working on the React section of FCC. When rendering to the ReactDOM: `ReactDOM.render(element, document.getElementById('root'));`. To render: first call `Render(){}` method, and then return inside it the jsx. Learned how to pass props (properties) to the components.  
 
**Thoughts:** I should be a lot more confident and skillful using React, especially after de last 2 months where my job was mainly working with React components, but here I am, still struggling a bit, but now is making a lot more sense.

### Day 8: June 3, 2019, Monday

**Today's Progress:** Continue with React from FCC. Passing default props, I can pass a default prop just in case no value is expliciti provided, but if I pass `null` it will remain `null`. Defining `propTypes`, so it will throw an error if the type is different to what I'm expecting. A _stateless functional component_ is any function which accepts props and returns JSX, no need of `render()` method before the `return`. A _stateless component_, on the other hand, is a class that `extends React.Component`, but does not use internal state. A _stateful component_ is any component that does maintain its own internal state (normally referred to simply as components or React components). `State` consists of any data the application needs to know about, that can change over time. 

**Thoughts:** Understanding more this that i've already used before, but I think I will really understand this whe I have to work in a project from scratch.

### Day 9: June 4, 2019, Tuesday

**Today's Progress:** Continue the Javascript Data Structures and Algorithms Certification of FreeCodeCamp. I finished the (already started months ago) Basic JavaScript section, and started with ES6.

**Thoughts:** I always think I still have so much more to learn, but today I think that I also have learnt so much in the last year.

### Day 10: June 5, 2019, Wednesday

**Today's Progress:** Continue the Javascript Data Structures and Algorithms Certification of FreeCodeCamp, ES6. Learnt about the **Rest Operator** `...`, it is useful because I can create functions that take a **variable number of arguments**. These arguments are stored in an array that can be accessed later from inside the function. Also the **Spread Operator**, `...`, allows us to expand the elements of an array (or get the elements out of the array ). Something similar can be made with objects, it is called _destructuring_ an object. If I have an object: `voxel = {x: 3.6, y: 7.4, z: 6.54 };` I can use the spread operator like this: `const { x, y, z } = voxel;`, but I I want to change the key names, I have to do it like this: `const { x : a, y : b, z : c } = voxel` ("get the field x and copy the value into a..."). One **key difference between the spread operator and array destructuring** is that the spread operator unpacks **all** contents of an array into a comma-separated list. Consequently, you cannot pick or choose which elements you want to assign to variables. Desctructuring an array: `const [a, b] = [1, 2, 3, 4, 5, 6];` a get assigned the first value of the array and b the second. It is also possible to access the value at any index in an array with destructuring by using commas to reach the desired index: `const [a, b,,, c] = [1, 2, 3, 4, 5, 6];` (logs [1, 2, 5]). Destructuring can also be used to choose the fields of an object that I want to work with, instead of having to work with the whole object. Template literals, ` `` ` and string interpolation `${variable(s)}`. The `class` key word, which it is used to create constructor objects/functions. **Getters** and **Setters**, the first are meant to simply return (get) the value of an object's private variable to the user without the user directly accessing the private variable. The Setters are meant to modify (set) the value of an object's private variable based on the value passed into the setter function. Difference between **require()** and **import**, require() allows me to bring functions and code from one file to another, but with import I can choose _which_ functions or code I want to bring. **Export**, when is a default export, I can only have one value to be default and it cannot be used with `var`, `let`, or `cons`. When I am importing a default value, it is not necessary to use `{}`. Finished **ES6** section!

**Thoughts:**  ES6 makes so many things so much easier! also it is used in React, so it is very important to learn it well.

### Day 11: June 6, 2019, Thursday

**Today's Progress:** Started the RegEx section of FreeCodeCamp Javascript Data Structures and Algorithms Certification. `test()` method is used to check if my RegEx (the pattern I want to test) is found in the string I am passing. The pattern must go inside two slash `//`. With the _or_ operator, `|`, I can look for for than one pattern. Tha flag `i` ignores de letter case, for example, `/Hola/i` will match 'hola', 'Hola', 'HOLA'... The `match()` method extracts the matches into an array. To match or extract a pattern more than once I can use `g` (without this, the method would stop at the first match). Multiple flags can be used together, `/pattern/gi`. The wildcard character (dot or period) `.` is equivalent to any one character. _Character classes_ allow me to define a group of characters I wish to match by placing them inside square  brackets `[]` (don't use `,` to separate elements inside the brackets!). A character set uses `-` to define a range of characters,letters or numbers, and they can also be use together `/[a-z0-9]/`. To create a negated character set, place a _caret character_ (^) after the opening bracket and before the characters I do not want to match (for example `/[^aeiou]/gi`). The `+` is used character to check if one character or pattern is repeated more than one time consecutively. To check matches that occur zero or more time we use `*`. _Greedy_ match finds the longest possible part of a string that fits the regex pattern and returns it as a match. _Lazy_ match finds the smallest possible part of the string that satisfies the regex pattern. By default matches are greedy, but to convert it to a lazy match we use `?`. (greedy: /t[a-z]*i/, lazy: /t[a-z]*?i/).
The caret `^` is also used to search for patterns at the beginning of strings, for this it is used outside a set (outside the brackets). To search the end of strings we use `$`. `\w` = `[A-Za-z0-9_]` (all letters and numbers and `_`). The opposite of `\w` is `\W`. Digit shortcut `\d` = `/[0-9]/`. The opposite of `\d` is `\D`, it returns all non digit characters. `\s` check for any kind of space. `\S` check for non-whitespace

**Thoughts:** Interesting for of creating patterns, I've already used them before and is useful, but it can be quite confusing as well.

### Day 12: June 7, 2019, Friday

**Today's Progress:** Finished the Regular Expressions section of FreeCodeCamp. **Quantity specifiers** are used with curly brackets (`{min, max}`). You put two numbers between the curly brackets - for the lower and upper number of patterns, it is used with `test()`. Also only the minimum quatity can be specified, `{min,}`, the number must be followed by a comma, and it will match everything that's equal to that number and more. To match specific quantities a single number goes into the brackets `{num}`. `?` is ised to check if an element is present 0 or 1 time, it's like the element is optional. **Lookahead** _positive_ (`(?=pattern)`)checks if the pattern is present, but doesn't return it, _negative_ (`(?!pattern)`) checks if the pattern is **not** there. Using `match()` they will return the previous string, using `test()` will return a boolean. `replace(pattern, string)` it will look for the pattern and relpace it with the string provided. Started with **Debugging**. 
There are generally three types of errors: _syntax error_, _runtime errors_ and _semantic (or logical) errors_. Finished the Debugging section. Started with **Basic Data Structures** One, for example, _array_ that doesn't have any objects nested in it (one has one level) is known as _one-dimensional array_. If there is nesting it is called _multi-dimensional array_. `push()` adds elements at the end of the array, `unshift()` adds elements at the beginning. `pop()` removes an element from the end of the array, `shift()` removes it from the beginning, they don't take parameters, and modifie the array one element at a time. `splice()` can take up to three parameters, the first two are integers which represent indexes of the array. The first parameter represents the index on the array from which to begin removing elements (that index inclusive), while the second parameter indicates the number of elements to delete. The `splice()` method modifies the array and returns a new array cointaining the removed items. The third parameter is used to add elements to the array, if there are more than one elements being added to the array, there is no need to use parenthesis to wrap them. `slice()` doesn't modify the original array, but copies, or extracts, a given number of elements to a new array. It takes 2 parameters, the first is the index where I want to start the extraction (inclusive) and the second where I want to stop it (not inclusive). I did the first challenge.

**Thoughts:** RegEx can be super confusing, to abstract for me, but I now they can be useful and if you really understand them, they can simplify things. I feel that the debugging section was quite vague, because it is a super important part of programming, and I think I didn't learnt anything new, it was a very short section, but I guess the problems are pretty much always the same, so is just practice to be able to catch them soon. 

### Day 13: June 8, 2019, Saturday

**Today's Progress:** Start React project with Sass. Just created one component so far and one sass file for the styling.

**Thoughts:** It seems that I haven't done anything, but configuration can take time (especially if it's the first time you do it!)

### Day 14: June 9, 2019, Sunday

**Today's Progress:** Continue with Data Structures. `key in obj` is new for me, I had always used `hasOwnProperty()` to check if a key exists in an object. Objects do not mantain an ordering to stored keys like arrays. I finished the Basic Data Structures section.

**Thoughts:** Getting confused with accessing nested properties in objects when creating a function or when using a `for in` loop, but `console.log()` and https://repl.it/languages/javascript help so so so much!!

### Day 15: June 10, 2019, Monday

**Today's Progress:** I continue working on my React-Sass project.

**Thoughts:** I need more RAM memory, I was so inspired and motivated until my computer froze :(

### Day 16: June 11, 2019, Tuesday

**Today's Progress:** Continue with Basic Algorithm Scripting of FCC.

**Thoughts:** Late I realized that I should've kept a copy of my solutions somewhere, as they are not being saved on FCC. It would have been good, to the go back and discuss them with someone or just to be able to improve them some day.

### Day 17: June 12, 2019, Wednesday

**Today's Progress:** I finished the Basic Algorithm Scripting and started Object Otiented Programming section. Similar objects share the same properties, but may have different values for those properties (for example, all cars have wheels, but not all cars have the same number of wheels). Objects in JavaScript are used to model real-world objects, giving them properties and behavior just like their real-world counterparts. The especial property _method_ in an object is a function. _This_ is used to reference the object where the method is defined. _Constructors_ are functions that create new objects. They define properties and behaviors that will belong to the new object. **Constructors:** are defined with a capitalized name to distinguish them from other functions that are not constructors, they use the keyword _this_ to set properties of the object they will create. Inside the constructor, this refers to the new object it will create. Constructors define properties and behaviors instead of returning a value as other functions might. `instanceof` allows to compare an object to a constructor, returning true or false. The _prototype_ is an object that is shared among ALL instances of my object, if I add something to the prototype, it gets added to all instances as well. _Own_ properties are defined directly on the object instance itself. And _prototype_ properties are defined on the prototype. When a prototype is manually set to a new object, I need to add the constructor first! otherwise it disappears. Instead of using `new Class()` syntax, sometimes is better to use `Object.create(Class.prototype);`.

**Thoughts:** Finally learning about Prototypes!

### Day 18: June 13, 2019, Thursday

**Today's Progress:** Continuing with OOP. When an object inherits its prototype from another object, it also inherits the supertype's constructor property. This can be overwritten by setting manually a constructor to the parent class. `ChildObject.prototype = Object.create(ParentObject.prototype);` To override a method from a parent: `ChildObject.prototype.methodName = function() {...};` A **mixin** allows other objects to use a collection of functions (`let mixin = (obj) => {obj.mixin = () => 'something'}` and then call the mixin function `mixin(obj)` to transfer the method to the object). **Closure** is used to protect properties within an object from being modified externally. In JavaScript a function always has access to the context in which it was created (this is called closure).The simplest way to make  a property to be private is by creating a variable within the constructor function. This way the scope of that variable is changed to be available only within the constructor function. This way, the property can only be accessed and changed by methods also within the constructor function. _Immediately Invoked Function Expression_ (IIFE) they must not have a name nor be stored in a variable. The whole anonymous function is wrapped into parenthesis and another set is written at the end to immediately call it ( `(function(){   })()`). **Functional Programming** Functions are independent from the state of the program or global variables. They only depend on the arguments passed into them to make a calculation. Functions try to limit any changes to the state of the program and avoid changes to the global objects holding data. Functions have minimal side effects in the program.
The functional programming software development approach breaks a program into small, testable parts. _Callbacks_ are the functions that are slipped or passed into another function to decide the invocation of that function (they are used, for example, in the filter method). All functions in JavaScript are _first class functions_. The functions that take a function as an argument, or return a function as a return value are called _higher order functions_. When the functions are passed in to another function or returned from another function, then those functions which gets passed in or returned can be called a _lambda_. One of the core principle of functional programming is to **not** change things. Changes lead to bugs. In functional programming, changing or altering things is called _mutation_, and the outcome is called a _side effect_. _Pure functions_ don't have side effects. Another principle of functional programming is to always declare your dependencies explicitly. This means if a function depends on a variable or object being present, then pass that variable or object directly into the function as an argument.

**Thoughts:** Functional programming is what I am used to, so is so much easier for me than OOP. This is more 'tangible' and OOP seems to be more abstract.

### Day 19: June 14 2019, Friday

**Today's Progress:** Went back to my React project, didn't do much, I mean I did, but then undid what I had started, with the hamburguer menu.

**Thoughts:** :( not much progress.

(I skipped on June 15, 2019, Saturday, I did only about 20 minutes)

### Day 20: June 16, 2019, Sunday

**Today's Progress:** Continuing with Functional programming on FCC. _Map_ is a pure function (it doesn't alter the original array). The _slice method_ returns a copy of certain elements of an array. If the arguments are not provided, the default is to start at the beginning of the array through the end, which is an easy way to make a copy of the entire array. 

**Thoughts:** Too slow progress.

### Day 21: June 17, 2019, Monday

**Today's Progress:** Continuing with Functional programming on FCC. Use different methods like sort, reduce, split, slice, concat. Whatever goes into the parenthesis (that is called delimiter) of the _split_ method will be removed, and the resulting strings will be the ones before and after that. For example `const x = 'Hello hello'; console.log(x.split('e'); //[ 'H', 'llo h', 'llo' ]`. _Join_ method creates a string from an array, the elements of the array will be separated by the delimiter .

**Thoughts:**

### Day 22: June 18, 2019, Tuesday

**Today's Progress:**

**Thoughts:**

### Day 23: June 19, 2019, Wednesday

**Today's Progress:**

**Thoughts:**

### Day 24: June 20, 2019, Thursday

**Today's Progress:**

**Thoughts:**
